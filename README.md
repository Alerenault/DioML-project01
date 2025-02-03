# DioML-project01
Modelo de previsão de aluguel de bicicletas.

# Tipo de Aprendizado utilizado
# Regressão
É um tipo de aprendizado supervisionado no qual os modelos aprendem a usar dados de treinamento aplicam esse aprendizado a dados novos. A principal meta dos modelos de regressão é obter valores de saída numéricos com base em preditores independentes, diferentemente classificação  em que o objetivo é prever em quais categorias novos dados se encaixam com base em aprendizados de dados de treinamento. Na regressão, o objetivo é ajudar a estabelecer a relação entre essas variáveis de preditores independentes estimando como uma variável afeta as outras. Por exemplo, o modelo pode prever o preço de um automóvel com base em recursos como quilômetros por litro e classificação de segurança.

# Criando um aprendizado de maquina automatizao( Automated ML)
Para criar um aprendizado de máquina automatizao na Azure é necessário acessar o Machine Learning Studio, e dentro das opções do menu selecionar o item Automated ML. Detntro desta tela tem a opção de Criar um novo ML Automatizado, a criação é feita em etapas, a primeira é para adicionar informações básicas, como nome do job, nome da experiência e outros. A próxima etapa serve para informar qual o tipo de aprendizado será utilizado, neste caso, o escolhido foi a regressão, tmabém é necessário informar quais serão os dados utilizados no aprendizado de máquina, os dados podem ter diversas origens, como API e tabelas existentes na azure. 


# Dados utilizados para o aprendizado
Foram utilizados uma planilha de dados fornecidas para este laboratório com as seguintes informações:
dia, mês, ano, estação, feriado, dia da semana, dia útil, previsão do tempo, temperatura, atemperatura, hum , velocidade do vento 


