Projeto replicando o passo a passo de:
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

Abaixo segue um Guia Resumido:

1. **Crie um Espaço de Trabalho no Azure Machine Learning:**
   - Acesse o portal Azure (https://portal.azure.com).
   - Crie um recurso de Machine Learning.
   - Configure: assinatura, grupo de recursos, nome, região, conta de armazenamento, cofre de chaves, insights de aplicativos.
   - Lance o estúdio do Azure Machine Learning.

2. **Use Aprendizado de Máquina Automatizado para Treinar um Modelo:**
   - No estúdio, acesse a página de ML Automatizado.
   - Crie um novo trabalho de ML Automatizado:
     - Tipo de tarefa: Regressão.
     - Conjunto de dados: Crie um novo com dados de aluguel de bicicletas.
     - Defina as colunas e tipos de dados.
     - Escolha modelos (RandomForest e LightGBM).
     - Configure os limites de tentativas, testes e tempo.
   - Submeta o trabalho de treinamento.

3. **Revise o Melhor Modelo:**
   - Após o treinamento, acesse a guia Visão Geral.
   - Veja o resumo do melhor modelo.
   - Analise as métricas e gráficos de desempenho.

4. **Implante e Teste o Modelo:**
   - Na guia Modelo, selecione "Implantar".
   - Configure a implantação com um nome e descrição.
   - Aguarde o status mudar para "Sucesso".

5. **Teste o Serviço Implantado:**
   - Acesse os Endpoints.
   - Abra o endpoint "predict-rentals".
   - Insira os dados de teste e clique em Testar.
   - Analise os resultados de previsão.

6. **Limpeza:**
   - Se não for mais usar, delete o endpoint "predict-rentals".
   - Para evitar cobranças, exclua o grupo de recursos no portal Azure.

Este processo deve levar cerca de 30 minutos.