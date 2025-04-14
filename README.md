# README: Relatório de Diárias e Motoboys

## Descrição

Este script Python foi desenvolvido para gerar um relatório detalhado com base em uma planilha Excel contendo informações sobre diárias, motoboys e valores cobrados. Ele organiza os dados de forma estruturada, proporcionando uma análise eficiente por semana, dia da semana, loja e valores totais.

Ao executar o script, ele cria uma nova planilha com três abas principais:

1. **Resumo Geral**: Contém a contagem de diárias por dia da semana e o valor total cobrado para cada dia.
2. **Resumo por Loja e Semana**: Detalha as diárias e a média de motoboys por loja e por semana.
3. **Resumo Semanal**: Apresenta o total de diárias e valores cobrados por semana.

Além disso, o script calcula a média geral de motoboys por mês, com base nas informações de data.

## Pré-requisitos

Certifique-se de ter os seguintes pacotes instalados antes de executar o script:

- **pandas**: para manipulação dos dados.
- **tkinter**: para a interface de seleção de arquivos.
- **openpyxl**: para salvar planilhas Excel.
  
Você pode instalar os pacotes necessários com o seguinte comando:

```bash
pip install pandas openpyxl
