## Descrição:
 Este projeto tem como finalidade executar um robô de forma assistida utilizando o UiPath Studio. Ele acessa o site do RPA Challenge e realiza o download do arquivo excel para execução. Insere os dados em fila do orquestrador e os consome submetendo os dados nos campos do formulário.

## Instruções:
- Criar um fluxo de trabalho que insira dados de uma planilha nos campos do formulário na tela;
- Os campos mudarão de posição na tela após cada envio ao longo de 10 rodadas, portanto, o fluxo de trabalho deve identificar corretamente onde cada registro da planilha deve ser digitado todas as vezes;

## Requisitos:
 Os requisitos para a execução deste robô são:

- Ter o navegador Google Chrome instalado;
- Ter a extensão UiPath Automation para guias anônimas ativada;
- Ajustar arquivo de configuração 'Data\Config.xlsx' conforme os parâmetros do usuário;
