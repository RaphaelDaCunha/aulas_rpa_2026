Cenário:

1. Nome do Processo
R:Conciliação bancária diária
2. É viável para RPA? (Sim / Não)
R:Sim
3. Justificativa baseada nos 4 critérios essenciais (Repetitividade, Regras de Negócio, Tipo de Dados, Volume).
R:Repetitividade:
O processo de conciliação bancária é realizado diariamente e segue uma sequência de atividades que se repete. O robô poderá executar as mesmas tarefas todos os dias, como baixar o extrato, consultar os registros no ERP e realizar a comparação das informações.

Regras de Negócio:
O processo possui regras de negócio claras e objetivas. A conciliação pode ser realizada por meio da comparação do CNPJ e do valor das transações do extrato bancário com as baixas registradas no ERP. Dessa forma, o robô consegue tomar decisões seguindo regras previamente definidas, sem depender de julgamento subjetivo.

Tipo de Dados:
Os dados utilizados no processo são estruturados. O extrato bancário é disponibilizado em formato .csv, contendo informações que podem ser lidas e processadas automaticamente. Os dados das baixas também podem ser consultados no ERP, permitindo que o robô faça a comparação entre as informações.

Volume:
O processo pode envolver uma grande quantidade de transações diariamente. A realização manual dessas comparações pode consumir bastante tempo, principalmente quando existem muitos registros. Por isso, o uso de RPA pode agilizar a execução do processo e permitir que várias transações sejam analisadas de forma automática.
4. Mapeamento Passo a Passo das Ações do Robô
R:
- 1 Iniciar a execução do processo

O robô inicia a rotina de conciliação bancária diária em horário previamente definido.

Verifica se os sistemas e arquivos necessários estão disponíveis para iniciar o processamento.

- 2 Acessar o sistema bancário

O robô acessa o sistema bancário utilizando as credenciais previamente configuradas.

Localiza o extrato bancário referente ao período que deverá ser conciliado.

- 3 Baixar o extrato bancário

O robô realiza o download do extrato bancário no formato .csv.

Salva o arquivo em uma pasta previamente definida para o processo.

Verifica se o arquivo foi baixado corretamente e se contém os dados necessários para a conciliação.

- 4 Ler e organizar os dados do extrato

O robô abre o arquivo .csv e realiza a leitura das transações.

Identifica as informações necessárias para a comparação, principalmente o CNPJ e o valor da transação.

Organiza os registros para que possam ser comparados com as informações existentes no ERP.

- 5 Acessar o sistema ERP

O robô acessa o sistema ERP utilizando as credenciais previamente configuradas.

Consulta as baixas financeiras registradas no mesmo período do extrato bancário.

Obtém os dados necessários para realizar a comparação com as transações do banco.

- 6 Comparar as transações

O robô percorre cada registro presente no extrato bancário.

Para cada transação, procura no ERP uma baixa correspondente.

A comparação é realizada seguindo as regras de negócio definidas, utilizando o CNPJ e o valor da transação como principais critérios.

- 7 Identificar as transações conciliadas

Caso o CNPJ e o valor da transação do extrato sejam correspondentes aos dados encontrados no ERP, o robô considera o registro conciliado.

O resultado da conciliação é registrado no controle do processo.

- 8 Identificar as transações não conciliadas

Caso o robô não encontre uma baixa correspondente no ERP ou os dados não sejam compatíveis, a transação é classificada como não conciliada.

O robô registra essas ocorrências para que possam ser analisadas posteriormente por um responsável.

- 9 Gerar o resultado da conciliação

Após analisar todas as transações, o robô consolida os resultados do processamento.

O relatório ou arquivo de controle deve apresentar, no mínimo, as transações conciliadas e não conciliadas.

As informações podem ser organizadas de forma que facilite a identificação de divergências.

- 10 Salvar os arquivos e registros

O robô salva o resultado final em uma pasta ou local definido pela empresa.

Mantém o extrato utilizado e o relatório gerado para fins de controle e rastreabilidade do processo.

- 11 Finalizar a execução

Após processar todas as transações, o robô encerra o acesso aos sistemas.

Finaliza a rotina de conciliação bancária diária.

Caso existam transações não conciliadas, o resultado fica disponível para análise e tratamento manual pelo responsável.