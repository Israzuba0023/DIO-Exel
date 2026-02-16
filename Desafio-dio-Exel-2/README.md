# 📊 Organizador de Declaração de Imposto de Renda

![Status](https://img.shields.io/badge/Status-Completo-success)
![Excel](https://img.shields.io/badge/Excel-2016+-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Sobre o Projeto

Este projeto consiste em uma ferramenta completa desenvolvida em **Microsoft Excel** para organizar e centralizar todas as informações necessárias para a Declaração de Imposto de Renda de Pessoa Física (IRPF). 

A solução oferece uma interface profissional, intuitiva e com validações automáticas que facilitam o processo de coleta e organização dos dados fiscais, preparando o contribuinte para realizar sua declaração com segurança e eficiência.

## 🎯 Objetivos

- ✅ Centralizar todas as informações relevantes para a declaração de IR em um único arquivo
- ✅ Facilitar o preenchimento através de validações e listas suspensas
- ✅ Organizar dados de forma estruturada e profissional
- ✅ Reduzir erros através de validações automáticas e fórmulas
- ✅ Proporcionar navegação intuitiva entre diferentes seções
- ✅ Gerar resumo consolidado automaticamente
- ✅ Calcular totalizadores de forma automática

## ✨ Funcionalidades

### 🏠 Menu de Navegação
- Hub central com acesso direto a todas as seções
- Interface visual organizada com código de cores
- Indicação clara do ano base e exercício

### 👤 Dados do Titular
- Cadastro completo de informações pessoais
- Validação automática de campos (CPF, UF, sexo, estado civil)
- Organização por categorias: Identificação, Endereço e Contato
- Formatação profissional com campos destacados

### 👨‍👩‍👧‍👦 Dependentes
- Registro de até 10 dependentes
- Campos: Nome, CPF, Data de Nascimento, Parentesco
- Validação de parentesco (filho, cônjuge, pai/mãe, etc.)
- Indicação se reside com o titular

### 💰 Informes de Rendimentos
- Registro de múltiplas fontes pagadoras
- Campos organizados: Rendimentos Tributáveis, Contribuição Previdenciária, IR Retido, 13º Salário
- **Totalização automática** de todos os valores
- Formatação monetária brasileira (R$)
- Capacidade para até 15 fontes pagadoras

### 🏥 Despesas Dedutíveis

#### Despesas Médicas e de Saúde
- 10 registros disponíveis
- Tipos: Consulta, Exame, Plano de Saúde, Dentista, Psicólogo, Fisioterapia, Cirurgia
- **Subtotal automático** calculado

#### Despesas com Educação
- 10 registros disponíveis
- Tipos: Educação Infantil, Ensino Fundamental, Médio, Superior, Pós-graduação, Curso Técnico
- **Subtotal automático** calculado

#### Outras Deduções
- Previdência Privada (PGBL)
- Pensão Alimentícia
- Livro Caixa (Autônomos)
- **Total Geral de Deduções** calculado automaticamente

### 🏠 Bens e Direitos
- Registro de até 20 bens
- Campos: Código, Discriminação, Localização
- Valores comparativos: 31/12/2024 e 31/12/2025
- Categorias: Imóveis, Veículos, Contas Bancárias, Investimentos, Participações
- **Totalização automática** do patrimônio

### 📈 Resumo Geral
- Dashboard consolidado com visão geral de todos os dados
- **Fórmulas interligadas** com todas as outras abas
- Cálculo automático de:
  - Total de Rendimentos Tributáveis
  - Total de IR Retido na Fonte
  - Contribuição Previdenciária
  - Outros Rendimentos
  - Total de Deduções
  - Patrimônio (anos 2024 e 2025)
  - Base de Cálculo Estimada

## 🛠️ Recursos Técnicos

### Validações Automáticas
- ✅ Listas suspensas para seleção rápida
- ✅ Validação de dados em campos críticos
- ✅ Prevenção de erros de digitação
- ✅ Formatação condicional

### Fórmulas Excel
- ✅ Totalizadores automáticos (SUM)
- ✅ Referências cruzadas entre abas
- ✅ Cálculos de base tributária
- ✅ Zero erros de fórmula

### Formatação Profissional
- 🎨 Código de cores consistente
- 🎨 Cabeçalhos destacados
- 🎨 Campos de entrada claramente identificados
- 🎨 Bordas e alinhamentos padronizados
- 🎨 Formatação monetária brasileira

## 📁 Estrutura do Arquivo

```
Organizador_IR_2026_Completo.xlsx
├── Menu Principal
│   └── Navegação central
├── Dados do Titular
│   ├── Identificação
│   ├── Endereço
│   └── Contato
├── Dependentes
│   └── Lista de até 10 dependentes
├── Informes de Rendimentos
│   └── Até 15 fontes pagadoras
├── Despesas Dedutíveis
│   ├── Saúde (10 registros)
│   ├── Educação (10 registros)
│   └── Outras Deduções
├── Bens e Direitos
│   └── Até 20 bens registrados
└── Resumo Geral
    └── Dashboard consolidado
```

## 🚀 Como Utilizar

### Pré-requisitos
- Microsoft Excel 2016 ou superior
- Ou Google Sheets (compatível)
- Ou LibreOffice Calc

### Passo a Passo

#### 1️⃣ **Download**
- Faça o download do arquivo `Organizador_IR_2026_Completo.xlsx`
- Salve em local seguro no seu computador

#### 2️⃣ **Abertura**
- Abra o arquivo no Excel, Google Sheets ou LibreOffice
- Se solicitado, habilite macros (não há macros neste arquivo, mas pode aparecer o aviso)

#### 3️⃣ **Navegação**
- Comece pela aba **"Menu"** para ter uma visão geral
- Navegue pelas abas usando os botões do menu ou clicando nas abas na parte inferior

#### 4️⃣ **Preenchimento**

**Dados do Titular**
- Preencha todas as informações pessoais
- Use as listas suspensas para campos validados (Sexo, Estado Civil, UF)

**Dependentes**
- Cadastre todos os seus dependentes
- Selecione o parentesco na lista suspensa
- Indique se reside com você

**Informes de Rendimentos**
- Registre cada fonte pagadora em uma linha
- Os totais são calculados automaticamente

**Despesas Dedutíveis**
- Preencha todas as despesas de saúde e educação
- Adicione valores de outras deduções (PGBL, pensão, etc.)
- Observe os subtotais e total geral

**Bens e Direitos**
- Liste todos os seus bens e direitos
- Informe o código correspondente (consulte tabela da Receita)
- Preencha valores de 31/12/2024 e 31/12/2025

**Resumo Geral**
- Esta aba é automática - apenas visualize os resultados
- Confira se todos os valores estão corretos

#### 5️⃣ **Verificação**
- Revise todos os dados preenchidos
- Confira os totalizadores
- Verifique o resumo geral

#### 6️⃣ **Backup**
- Faça cópias de segurança regulares
- Mantenha o arquivo em local seguro

## 📊 Dados de Exemplo

O arquivo já vem preenchido com **dados de exemplo** para demonstração:

### 👤 Titular
- **Nome:** João Silva Santos
- **CPF:** 123.456.789-00
- **Ocupação:** Engenheiro de Software

### 👨‍👩‍👧‍👦 Dependentes (10)
- Cônjuge, 5 filhos, 3 pais/mães, 1 irmã

### 💰 Rendimentos
- **10 fontes pagadoras**
- **Total Tributável:** R$ 251.000,00
- **IR Retido:** R$ 33.300,00

### 🏥 Despesas
- **Saúde:** R$ 65.500,00
- **Educação:** R$ 135.700,00
- **Outras:** R$ 20.500,00
- **Total:** R$ 221.700,00

### 🏠 Patrimônio
- **10 bens registrados**
- **Total 2025:** R$ 2.308.000,00

> **Nota:** Substitua os dados de exemplo pelos seus dados reais!

## 🎨 Código de Cores

| Cor | Significado |
|-----|-------------|
| 🔵 Azul Escuro | Cabeçalhos principais |
| 🔷 Azul Médio | Seções e subcabeçalhos |
| 🟦 Azul Claro | Campos de entrada de dados |
| 🟨 Amarelo | Campos calculados / Totais |
| 🟧 Laranja | Totalizadores importantes |
| 🟩 Verde | Menu de navegação |
| 🟪 Roxo | Resumo e cálculos finais |

## ⚠️ Avisos Importantes

### ⚖️ Propósito Legal
- ⚠️ **Esta ferramenta é APENAS para organização pessoal**
- ⚠️ **NÃO substitui** a declaração oficial na Receita Federal
- ⚠️ **NÃO dispensa** a consulta a um contador
- ⚠️ Consulte sempre um profissional qualificado

### 🔒 Segurança de Dados
- 🔐 Dados armazenados **localmente** no seu dispositivo
- 🔐 **Não há envio** de informações para servidores externos
- 🔐 Faça **backup regular** do arquivo
- 🔐 Mantenha o arquivo em local **seguro e criptografado**

### 📋 Conformidade
- Use os códigos oficiais da Receita Federal para Bens e Direitos
- Mantenha documentação comprobatória de todos os valores informados
- Guarde informes de rendimento originais
- Mantenha notas fiscais e recibos organizados

## 🔧 Solução de Problemas

### Problema: Fórmulas não calculam
**Solução:** Verifique se o cálculo automático está ativado em Fórmulas > Opções de Cálculo > Automático

### Problema: Validações não funcionam no Google Sheets
**Solução:** Algumas validações podem precisar ser reconfiguradas. Baixe e use no Excel para melhor experiência.

### Problema: Arquivo aparece vazio
**Solução:** Certifique-se de navegar pelas **abas na parte inferior** da planilha. A primeira aba é apenas o menu.

### Problema: Valores não aparecem no Resumo Geral
**Solução:** Verifique se preencheu as outras abas primeiro. O resumo puxa dados automaticamente das outras abas.

## 📚 Referências

- [Receita Federal - IRPF 2026](https://www.gov.br/receitafederal)
- [Tabela de Códigos de Bens e Direitos](https://www.gov.br/receitafederal)
- [Limites de Dedução](https://www.gov.br/receitafederal)
- [Instruções de Preenchimento](https://www.gov.br/receitafederal)

## 💡 Dicas Úteis

### ✅ Organize-se ao Longo do Ano
- Não deixe para organizar tudo em cima da hora
- Vá preenchendo a planilha mensalmente
- Guarde documentos em pastas organizadas

### ✅ Documentação
- Mantenha todos os comprovantes
- Organize por categoria (saúde, educação, etc.)
- Digitalize documentos importantes

### ✅ Revisão
- Revise os dados antes da declaração oficial
- Peça a um familiar para revisar também
- Compare com o ano anterior

### ✅ Contador
- Mesmo com a planilha organizada, consulte um contador
- Leve a planilha preenchida para facilitar o trabalho
- Esclareça todas as dúvidas

## 🤝 Contribuições

Este projeto foi desenvolvido como parte do desafio da **DIO (Digital Innovation One)**.

Sugestões de melhorias são bem-vindas:
- Reporte bugs abrindo uma issue
- Sugira novas funcionalidades
- Compartilhe melhorias de layout
- Ajude na documentação

## 📝 Licença

Este projeto está sob a licença MIT. Isso significa que você pode:
- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Uso privado

**Condições:**
- Mantenha o aviso de copyright
- Mantenha a licença MIT

## 👨‍💻 Autor

**Projeto desenvolvido para DIO**
- Desafio: Organizador de Declaração de Imposto de Renda
- Plataforma: Digital Innovation One
- Ano: 2026

## 📞 Suporte

Para dúvidas sobre o uso da planilha:
1. Consulte este README primeiro
2. Verifique a seção de Solução de Problemas
3. Consulte a documentação da Receita Federal
4. Em caso de dúvidas fiscais, procure um contador

## 🎯 Roadmap

Possíveis melhorias futuras:
- [ ] Exportação para formato da Receita Federal
- [ ] Dashboard com gráficos de análise
- [ ] Calculadora de imposto devido
- [ ] Comparativo com anos anteriores
- [ ] Alertas de prazos importantes
- [ ] Checklist de documentos necessários
- [ ] Versão para MEI e Empresas
- [ ] Integração com sistemas contábeis

## 📊 Estatísticas do Projeto

- **Abas:** 7
- **Campos de entrada:** 100+
- **Fórmulas automáticas:** 18
- **Validações:** 15+
- **Capacidade total:** 50+ registros
- **Formato:** .xlsx (Excel 2016+)
- **Tamanho:** ~21 KB

## 🏆 Reconhecimentos

Agradecimentos especiais:
- **DIO (Digital Innovation One)** pela oportunidade do desafio
- **Receita Federal** pelas diretrizes e documentação
- Comunidade de desenvolvedores que compartilham conhecimento

---

## 📌 Nota Final

**Este organizador é uma ferramenta de apoio para facilitar sua vida na hora de declarar o Imposto de Renda. Sempre consulte um contador profissional para orientações específicas sobre sua situação fiscal.**

**Boa declaração! 📊💰✅**

---

*Última atualização: Fevereiro 2026*
*Versão: 1.0*
*Ano Base: 2025 | Exercício: 2026*
