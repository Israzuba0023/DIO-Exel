# 📊 Dashboard de Vendas - Excel

![Status](https://img.shields.io/badge/Status-Completo-success)
![Excel](https://img.shields.io/badge/Excel-2016+-blue)
![DIO](https://img.shields.io/badge/DIO-Desafio-orange)

## 📋 Sobre o Projeto

Dashboard interativo de vendas desenvolvido em **Microsoft Excel** com foco na visualização de dados e análise de desempenho comercial. O projeto transforma dados brutos de vendas em insights visuais claros, permitindo tomada de decisões baseadas em dados.

Este dashboard foi desenvolvido como parte do desafio da **DIO (Digital Innovation One)**, demonstrando habilidades em análise de dados, visualização de informações e domínio de ferramentas Excel.

## 🎯 Objetivo

Criar um dashboard profissional que permita:
- ✅ Visualizar métricas-chave de vendas (KPIs)
- ✅ Analisar desempenho por categoria, região e vendedor
- ✅ Identificar produtos mais vendidos
- ✅ Facilitar a tomada de decisões estratégicas
- ✅ Apresentar dados de forma clara e visual

## ✨ Funcionalidades

### 📊 KPIs Principais
- **Receita Total**: Soma de todas as vendas realizadas
- **Total de Vendas**: Quantidade total de transações
- **Ticket Médio**: Valor médio por venda

### 📈 Análises Disponíveis
- **Vendas por Categoria**: Distribuição da receita entre Informática, Eletrônicos e Móveis
- **Vendas por Região**: Performance de vendas em Norte, Sul, Leste, Oeste e Centro
- **Top 5 Vendedores**: Ranking dos vendedores com melhor desempenho
- **Top 5 Produtos**: Produtos mais vendidos em quantidade

### 📉 Visualizações
- **Gráfico de Pizza**: Vendas por Categoria
- **Gráficos de Barras**: Vendas por Região, Top Vendedores, Top Produtos
- **Cores Profissionais**: Paleta de cores harmônica e profissional
- **Layout Responsivo**: Organização clara e intuitiva

## 📁 Estrutura do Arquivo

```
Dashboard_Vendas.xlsx
├── Base de Dados
│   └── 500 registros de vendas
│       ├── ID, Data, Produto
│       ├── Categoria, Vendedor, Região
│       ├── Quantidade, Preço, Valor Total
│       └── Cliente, Forma de Pagamento
├── Análise
│   └── Tabelas dinâmicas com fórmulas
│       ├── Vendas por Categoria
│       ├── Vendas por Região
│       ├── Top 5 Vendedores
│       └── Top 5 Produtos
└── Dashboard
    └── Visualização interativa
        ├── KPIs destacados
        └── 4 gráficos principais
```

## 📊 Dados Utilizados

### Base de Dados Simulada
O dashboard utiliza uma base de dados fictícia com **500 registros** de vendas, contendo:

#### Produtos (15 itens)
**Informática:**
- Notebook (R$ 3.500)
- Mouse (R$ 45)
- Teclado (R$ 120)
- Monitor (R$ 850)
- Webcam (R$ 280)

**Eletrônicos:**
- Smartphone (R$ 1.800)
- Tablet (R$ 1.200)
- Fone Bluetooth (R$ 180)
- Smartwatch (R$ 950)
- Carregador (R$ 65)

**Móveis:**
- Cadeira Gamer (R$ 1.100)
- Mesa (R$ 450)
- Luminária (R$ 85)
- Suporte Monitor (R$ 120)
- Estante (R$ 380)

#### Equipe de Vendas (8 vendedores)
- Ana Silva
- Carlos Santos
- Maria Oliveira
- João Pereira
- Paula Costa
- Ricardo Lima
- Fernanda Souza
- Pedro Alves

#### Regiões (5 áreas)
- Norte
- Sul
- Leste
- Oeste
- Centro

#### Período
- **Início**: 01/01/2025
- **Fim**: 15/02/2025
- **Total**: 46 dias de operação

## 🔧 Recursos Técnicos

### Fórmulas Excel Utilizadas
- **SUMIF**: Soma condicional para análises por categoria, região e vendedor
- **COUNTA**: Contagem de registros
- **SUM**: Totalização de valores
- **Referências entre abas**: Dados integrados entre Base de Dados, Análise e Dashboard

### Formatação
- ✅ Formatação monetária brasileira (R$)
- ✅ Formatação numérica com separador de milhares
- ✅ Cores profissionais e consistentes
- ✅ Bordas e alinhamentos padronizados
- ✅ Células mescladas para títulos
- ✅ Fontes hierárquicas (títulos, subtítulos, dados)

### Gráficos
- **4 gráficos interativos**:
  - 1 Gráfico de Pizza (Vendas por Categoria)
  - 3 Gráficos de Barras (Região, Vendedores, Produtos)
- Títulos descritivos
- Eixos rotulados
- Cores diferenciadas
- Tamanhos otimizados

## 🚀 Como Utilizar

### Pré-requisitos
- Microsoft Excel 2016 ou superior
- Ou Google Sheets (com limitações em gráficos)
- Ou LibreOffice Calc

### Passo a Passo

#### 1️⃣ Download
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/dashboard-vendas-excel.git

# Ou faça download direto do arquivo
Dashboard_Vendas.xlsx
```

#### 2️⃣ Abertura
- Abra o arquivo no Excel
- Permita edição se solicitado
- Aguarde o carregamento dos gráficos

#### 3️⃣ Navegação

**Aba "Dashboard"** (Principal)
- Visualize os KPIs no topo
- Analise os 4 gráficos principais
- Esta é a aba de apresentação

**Aba "Análise"**
- Veja as tabelas com fórmulas
- Dados agrupados e organizados
- Base para os gráficos do dashboard

**Aba "Base de Dados"**
- 500 registros de vendas
- Dados brutos organizados
- Fonte de dados para análises

#### 4️⃣ Personalização

**Para usar com seus próprios dados:**

1. Vá para a aba "Base de Dados"
2. Substitua os dados mantendo o formato:
   - Cabeçalhos nas mesmas colunas
   - Tipos de dados consistentes
   - Datas no formato DD/MM/YYYY
3. As análises e gráficos serão atualizados automaticamente
4. Verifique os totais na aba "Análise"
5. Confira o dashboard atualizado

## 📈 Métricas do Projeto

### Estatísticas da Base de Dados
- **Registros**: 500 vendas
- **Período**: 46 dias
- **Produtos**: 15 itens diferentes
- **Vendedores**: 8 profissionais
- **Regiões**: 5 áreas de atuação
- **Clientes**: 10 diferentes
- **Formas de Pagamento**: 5 opções

### Complexidade Técnica
- **Abas**: 3
- **Fórmulas**: 21
- **Gráficos**: 4
- **Células formatadas**: 1.500+
- **Referências cruzadas**: Múltiplas entre abas

## 🎨 Paleta de Cores

| Cor | Uso | Hex Code |
|-----|-----|----------|
| 🔵 Azul Escuro | Cabeçalhos e Títulos | #2F5496 |
| 🟢 Verde | KPIs e Destaques | #70AD47 |
| 🟡 Amarelo | Totalizadores | #FFC000 |
| 🔷 Azul Claro | Campos de dados | #D9E1F2 |
| ⚪ Branco | Fundo e texto | #FFFFFF |

## 📊 Insights Possíveis

Com este dashboard você pode responder:

### Perguntas Estratégicas
- ❓ Qual categoria gera mais receita?
- ❓ Qual região tem melhor desempenho?
- ❓ Quem são os melhores vendedores?
- ❓ Quais produtos têm mais saída?
- ❓ Qual o ticket médio das vendas?
- ❓ Qual forma de pagamento é mais usada?

### Análises Possíveis
- 📈 Tendência de vendas ao longo do tempo
- 📉 Comparativo de performance entre regiões
- 🎯 Identificação de oportunidades de crescimento
- 💰 Análise de rentabilidade por categoria
- 👥 Avaliação de desempenho da equipe

## 🔄 Melhorias Futuras

Possíveis expansões do projeto:
- [ ] Adicionar filtros interativos (slicers)
- [ ] Incluir análise temporal (vendas por mês)
- [ ] Gráfico de linha para tendência
- [ ] Análise de sazonalidade
- [ ] Comparativo ano a ano
- [ ] Metas e projeções
- [ ] Análise de margem de lucro
- [ ] Dashboard mobile-friendly
- [ ] Exportação para PDF
- [ ] Integração com Power BI

## 📚 Conceitos Aplicados

### Excel Avançado
- ✅ Fórmulas condicionais (SUMIF)
- ✅ Referências entre planilhas
- ✅ Criação de gráficos
- ✅ Formatação condicional
- ✅ Organização de dados

### Análise de Dados
- ✅ KPIs (Key Performance Indicators)
- ✅ Agregação de dados
- ✅ Segmentação por dimensões
- ✅ Ranking e top performers
- ✅ Métricas de negócio

### Design de Dashboards
- ✅ Hierarquia visual
- ✅ Escolha de gráficos adequados
- ✅ Paleta de cores profissional
- ✅ Layout organizado
- ✅ Destaque de informações-chave

## 🎓 Aprendizados

Este projeto permitiu desenvolver:
- 📊 Habilidades em visualização de dados
- 🔢 Domínio de fórmulas Excel avançadas
- 🎨 Senso de design e UX
- 📈 Compreensão de métricas de negócio
- 🧮 Organização e estruturação de dados
- 💡 Pensamento analítico

## ⚠️ Observações Importantes

### Dados Fictícios
- ⚠️ Os dados são **simulados** para fins educacionais
- ⚠️ Valores e nomes são **fictícios**
- ⚠️ Não representam uma empresa real

### Compatibilidade
- ✅ Totalmente compatível com Excel 2016+
- ⚠️ Google Sheets pode ter limitações em gráficos
- ✅ LibreOffice Calc compatível com funcionalidades básicas

### Performance
- Arquivo leve (~50 KB)
- Carregamento rápido
- Fórmulas otimizadas
- Sem macros ou VBA

## 🤝 Contribuições

Este projeto é open source e contribuições são bem-vindas!

### Como Contribuir
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Sugestões de Contribuição
- 🐛 Reportar bugs
- 💡 Sugerir novas funcionalidades
- 📊 Adicionar novos tipos de análise
- 🎨 Melhorar o design visual
- 📚 Melhorar a documentação

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

```
MIT License

Copyright (c) 2026 [Seu Nome]

É concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia
deste software e arquivos de documentação associados (o "Software"), para lidar
com o Software sem restrições, incluindo, sem limitação, os direitos de usar,
copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender
cópias do Software...
```

## 👨‍💻 Autor

**Desenvolvido para DIO**
- 🎓 Plataforma: Digital Innovation One
- 📚 Desafio: Dashboard de Vendas
- 📅 Ano: 2026
- 🏆 Status: Completo

## 📞 Contato

Para dúvidas, sugestões ou feedback:
- 💬 Abra uma issue no GitHub
- 📧 Entre em contato pelo LinkedIn
- 🌐 Visite meu portfólio

## 🙏 Agradecimentos

- **DIO (Digital Innovation One)** pela oportunidade e desafio
- **Comunidade de dados** pelas melhores práticas
- **Instrutores** pelos ensinamentos valiosos

## 📖 Referências

- [Documentação Excel - Microsoft](https://support.microsoft.com/pt-br/excel)
- [Melhores Práticas de Dashboard](https://www.tableau.com/pt-br/learn/articles/dashboard-design-best-practices)
- [Visualização de Dados](https://www.storytellingwithdata.com/)
- [KPIs de Vendas](https://blog.hubspot.com/sales/sales-kpis)

## 📸 Screenshots

### Dashboard Principal
![Dashboard](screenshots/dashboard.png)
*Visão geral com KPIs e gráficos*

### Análises
![Análises](screenshots/analises.png)
*Tabelas com fórmulas e agregações*

### Base de Dados
![Dados](screenshots/dados.png)
*500 registros organizados*

---

## 🎯 Conclusão

Este dashboard demonstra:
- ✅ Capacidade de transformar dados em insights
- ✅ Domínio de ferramentas Excel
- ✅ Habilidades de visualização de dados
- ✅ Pensamento analítico e estratégico
- ✅ Atenção a detalhes e qualidade

**Ideal para apresentações executivas, análises gerenciais e tomada de decisões baseadas em dados!**

---

*Última atualização: Fevereiro 2026*  
*Versão: 1.0*  
*Made with ❤️ for DIO*
