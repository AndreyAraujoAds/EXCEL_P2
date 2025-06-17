# Projeto de Aplicativo - Informe de Rendimentos

Este projeto representa a estrutura e lógica de um **aplicativo de 3 páginas** voltado para o **Informe de Rendimentos**, com base nas informações organizadas em uma planilha Excel.

## 📂 Estrutura da Planilha

A planilha possui 3 abas principais que representam as etapas do fluxo do aplicativo:

### 1. **APP (Página 1 - Tela Inicial / Entrada de Dados)**
- Objetivo: Entrada de informações básicas do contribuinte.
- Campos:
  - CPF
  - Nome completo
  - Ano-calendário
  - Tipo de rendimento (ex.: salário, aposentadoria, aluguel)
  - Origem do rendimento (ex.: CNPJ da fonte pagadora)
- Observações:
  - Validação básica de CPF.
  - Campos obrigatórios destacados.

### 2. **CALCULO (Página 2 - Processamento de Dados)**
- Objetivo: Realizar os cálculos necessários com base nas entradas fornecidas.
- Processos:
  - Cálculo de total de rendimentos.
  - Dedução de INSS ou outras contribuições (se aplicável).
  - Determinação de rendimento líquido.
- Fórmulas automatizadas presentes nesta aba.
- Células de entrada são referenciadas da aba "APP".

### 3. **INFORME (Página 3 - Geração do Informe de Rendimentos)**
- Objetivo: Apresentação final dos dados calculados em formato de informe oficial.
- Estrutura:
  - Bloco superior com dados do contribuinte e da fonte pagadora.
  - Tabela central com detalhamento de valores:
    - Rendimentos tributáveis
    - Contribuições
    - IR retido
    - Rendimentos isentos
  - Rodapé com espaço para assinatura/responsável.
- Pode ser exportado como PDF para envio ou impressão.

## 🛠️ Objetivo do Projeto

Este projeto visa simular o funcionamento de um app simples e eficiente que permita:
- Inserir os dados do contribuinte.
- Realizar os cálculos de forma automatizada.
- Gerar um informe de rendimentos compatível com exigências legais.

## 💡 Próximos Passos

- Transformar esta lógica em um protótipo de aplicativo (ex: Flutter, React Native).
- Implementar banco de dados para armazenar históricos.
- Adicionar autenticação e segurança de dados.

## 📄 Licença

Uso interno / educacional. Adaptável conforme a necessidade da empresa ou usuário.
