# Apache Airflow - Criando uma DAG 

Nessa DAG que usei de teste para aprender como funciona o Apache Airflow, com o objetivo de consumir uma API de previsão de tempo dos EUA, no qual eu peguei a cidade de Boston como exemplo e criar uma DAG que executa toda segunda-feira para demonstrar a semana que irá ter de previsão do tempo.

Aqui eu fiz da seguinte maneira:
    • Criei um DAG; 
    • Utilizei as CRON Expressions para definir um intervalo de agendamento;
    • Criei tarefas utilizando o PythonOperator;
    • Desenvolvi um DAG que extrai dados da previsão do tempo, de uma API. 
