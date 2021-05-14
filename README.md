# Analise_Dados_Churn

Aplicativo desenvolvido na terceira aula da semana Python do canal "Hashtag Programação"

## Situação:

A empresa relata que há um churn de 26% dos clientes. então foi disponibilizado uma base dados para análise 
com o objetivo de encontrar uma solução para esse problema.

## Análise

### Bibliotecas:
Plotly - Criar gráficos

Pandas - Tratar dados

### Tratando os dados:

Antes de tudo verificamos as colunas da base de dados e algumas informações úteis.

![ColunasInfo](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/colunasInfo.PNG)

Caracteristicas da base de dados:
- coluna unnamed nao tem significado no nosso contexto
- a coluna código está com todos valores nulos
- existe dados nulos nas colunas: Dependentes, churn
- a coluna total de gastos não está com os dados do tipo float.

Resultados:

![ColunasTratadas](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/colunasTratadas.PNG)

Após tratarmos os dados, Geramos um gráfico relacionando cada coluna com a quantidade de Churn.

### Conclusão 

- Clientes nos primeiros meses tendem a cancelar 
  - 1º Palpite : estamos trazendo muitos clientes desqualificados

  - 2º Palpite : dificuldades para reter clientes, o produto nao parece ser bom nos primeiros meses

Solução: bonus depois que o cliente passa de 3 meses

![ColunasTratadas](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-Meses.PNG)

- Problemas de fibra, muitos cancelamentos para quem usa internet de fibra ótica

Solução: Melhorar a qualidade da fibra ótica

![GraficoInternet](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-internet.PNG)

- Cliente com varios serviços tem menos chance de cancelar

Solução: Criar plano plus com muitos serviços e mais barato.

![GraficoSeguranca](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico_seguranca.PNG)

![GraficoBackup](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-backup.PNG)

![GraficoEquipamentos](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-equipamentos.PNG)

![GraficoSuporte](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-suporte.PNG)

- Muitos Clientes com contrato mensal cancela

Solução: Incentivar o contrato anual

![GraficoContrato](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-contrato.PNG)

- muitos cancelamentos com pagamento por Boleto

Solução: Incentivar outros tipos de pagamento (Credito / Debito automatico)
 
![GraficoPagamento](https://github.com/Alisson-tech/Analise_Dados_Churn/blob/master/img/grafico-pagamento.PNG)

