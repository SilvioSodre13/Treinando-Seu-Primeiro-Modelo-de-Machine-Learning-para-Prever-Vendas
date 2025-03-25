# Treinando-Seu-Primeiro-Modelo-de-Machine-Learning-para-Prever-Vendas

O objetivo é criar um modelo de Machine Learning para prever vendas futuras com base em dados históricos.
 
O processo inclui a coleta e preparação dos dados, a seleção de algoritmos de Machine Learning adequados (como regressão ou métodos de aprendizado supervisionado) e o treinamento do modelo. 

Após o treinamento, o modelo é avaliado usando métricas de desempenho e, em seguida, implantado para gerar previsões em tempo real. Ferramentas de análise de dados, frameworks de Machine Learning e serviços de implantação em nuvem são utilizadas para garantir que a solução seja escalável e eficiente.


## Contexto

Imagine que você é o dono de uma sorveteria chamada “Gelato Mágico”, localizada em uma cidade litorânea .

Durante o verão, as vendas de sorvetes disparam, mas você percebe que há uma forte correlação entre a temperatura do dia e a quantidade de sorvetes vendidos.

## Objetivo

Para otimizar a produção, evitar desperdícios e garantir que você sempre tenha estoque suficiente, você decide criar um modelo de Machine Learning para prever a quantidade de sorvetes que serão vendidos com base na temperatura. 


## Base dos Dados


Conforme orientado em aula foi criada uma base de dados fictícia usando o Microsoft Copilot.


Input no Copilot para geração da base de dados: 

![image](https://github.com/user-attachments/assets/ee0aede0-759e-4090-8113-1feae05859eb)


Output

![image](https://github.com/user-attachments/assets/6e4cafae-1a38-4378-bc90-542b18383ecc)


A base de dados foi originalmente gerada de forma fracionada a resposta apresenta em torno de 40 registros. Para unificá-la, consolidei os arquivos em um editor de texto e os salvei em um único arquivo CSV. Em seguida, abri o arquivo no Excel e removi a coluna de data, pois ela é irrelevante para o treinamento do modelo. Nosso objetivo é analisar a relação entre a temperatura e a quantidade de vendas.


Arquivo consolidado visualizado no Excel :

![image](https://github.com/user-attachments/assets/03163b9d-5498-42d6-8932-cecf398379a6)


## Preparando o Ambiente no Azure Machine Learning

Criando um Grupo de Recursos

![image](https://github.com/user-attachments/assets/98abacef-fb85-45aa-9b04-5e82860cf902)

![image](https://github.com/user-attachments/assets/17274753-d851-4b4f-badb-97cea3913101)

![image](https://github.com/user-attachments/assets/f761e5b0-712b-4200-9763-4efb368ab144)

![image](https://github.com/user-attachments/assets/cff4a158-aef7-4e3a-830c-c9374dcbc29d)
![image](https://github.com/user-attachments/assets/7ce78d71-0aa4-44ab-9f88-f8b8a354ee07)

![image](https://github.com/user-attachments/assets/c56c01d5-0f55-4bc4-904a-e3eb84ef69ae)

Criando o Azure Machine Learning Dentro do Grupo de Recursos

![image](https://github.com/user-attachments/assets/f3bd568d-1a95-4ff4-8676-e12d0dc708b8)
![image](https://github.com/user-attachments/assets/405be363-b120-4546-9f39-f2dee1627ab2)
![image](https://github.com/user-attachments/assets/f1c524e4-a41b-4c55-a52a-39935c5baeac)
![image](https://github.com/user-attachments/assets/95867d7a-d086-43a3-ad24-f2420546f2d4)
![image](https://github.com/user-attachments/assets/0d55e96b-1bf2-4bbe-bde8-a2cda7caaabe)

![image](https://github.com/user-attachments/assets/9fcd25a1-8e83-4b40-9fe3-44af6ce9e8c6)


 Estudio Machine Learning Criado

 ![image](https://github.com/user-attachments/assets/f8bf7234-d7e8-4d9c-a202-6a1d398c1cdb)

Notebook carregando a pasta com os arquivos 

![image](https://github.com/user-attachments/assets/78e2e661-5a33-4487-b2d3-9a1578deee1c)

![image](https://github.com/user-attachments/assets/912dabb7-ee3e-4d52-8182-774df5ff0544)

![image](https://github.com/user-attachments/assets/7a85c09f-3fc0-41ae-a1f0-c3e10d2193c3)

Provisionando um ambiente de Computação

![image](https://github.com/user-attachments/assets/3fe7d744-f4ff-41e4-bbb6-fc52fc459193)

Criando uma instancia de Computação

![image](https://github.com/user-attachments/assets/166a8268-4408-4252-816e-e9ba0f60072f)
![image](https://github.com/user-attachments/assets/9a01c191-28b9-48c9-9f58-8fc2c4906240)

Criando um cluster 

![image](https://github.com/user-attachments/assets/72122877-47b5-44de-8da6-85e322043983)
![image](https://github.com/user-attachments/assets/e3969433-66e6-4cc4-82f0-aa5929aa3d9c)


Criando um ativo de dados

![image](https://github.com/user-attachments/assets/ecf4292a-c32f-423d-a052-a5393f508424)

![image](https://github.com/user-attachments/assets/8f0195a6-4a76-499f-bfb8-c28d0fc3f45c)

![image](https://github.com/user-attachments/assets/1dac50d8-2a6f-4432-8968-5cc24a48e0c6)
![image](https://github.com/user-attachments/assets/58fb1b69-7fe0-428f-b4ec-8c3bb04881cf)


Treinando o Modelo atraves do ML Automatizado

![image](https://github.com/user-attachments/assets/e1f1554d-2296-407f-b8ce-d29b379e46aa)

![image](https://github.com/user-attachments/assets/21e1c936-9ab7-4391-8fa0-ce51dc8ee839)

![image](https://github.com/user-attachments/assets/1d1c22c9-1a40-4b0f-860e-fd53d50c0a01)

![image](https://github.com/user-attachments/assets/a51f3f93-fae7-4910-8e89-58af50325b84)

Modelo Criado

![image](https://github.com/user-attachments/assets/d3222bd5-38dc-4c68-8b01-d12e2cb98274)


Criando um modelo atraves do Designer (Pipeline)

![image](https://github.com/user-attachments/assets/acd1cd22-6e7e-48a1-b686-14a39c4910ff)
![image](https://github.com/user-attachments/assets/5102b61b-a728-426f-a4ee-9b11187a58ba)
![image](https://github.com/user-attachments/assets/0776a559-438a-4217-9eee-c126dfe5d68d)

Visualizando os modelos criados (Jobs)

![image](https://github.com/user-attachments/assets/40f408ff-5d83-4bf6-bf15-d100a256d5ff)

Verificando o resultado do treinamento

![image](https://github.com/user-attachments/assets/a6f105a1-5282-488e-8ae2-f672f4956745)

Verificando outras metricas do melhor modelo criado do AutoML

![image](https://github.com/user-attachments/assets/a3b7d4d4-6e31-4f90-95c1-07e1c5307e92)

Implantando o modelo

![image](https://github.com/user-attachments/assets/ba5bb574-d33a-4294-b241-a439f989781d)

![image](https://github.com/user-attachments/assets/64393b54-e0a4-487f-9ff3-85c0fcf707e3)

![image](https://github.com/user-attachments/assets/5372c77b-fd82-4efb-8321-b2b5acfa02fd)
































































 
































