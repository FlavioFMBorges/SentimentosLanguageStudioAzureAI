# Análise de Sentimentos com Language Studio no Azure AI

Foi coletado 3 opiniões de clientes de um bar/petiscaria e foram colocados no arquivo sentimentos.txt.
Após análise pelo Azure language mostrou os seguintes sentimentos sobre a empresa.
![Sentimento sobre a empresa](https://github.com/FlavioFMBorges/SentimentosLanguageStudioAzureAI/blob/main/Inputs/resultado_sentimentos.jpg) 
![](https://github.com/FlavioFMBorges/SentimentosLanguageStudioAzureAI/blob/main/Inputs/resultado_sentimentos2_3.jpg)

Apesar de poucas opiniões, estas mostraram que o sentimento dos clientes em sua grande maioria é positiva mas que precisa melhorar em alguns pontos.
O interessante é ver o reconhecimento das palavras chaves encontradas pelo Azure que mostram os sentimentos do clientes.

## O processo para esta análise no Azure foi o seguinte:  
  
### Primeira parte:  
0 - Entrar no site https://portal.azure.com/  
1 - Criar um recurso;  
2 - Opção Ai + Machine Learning;  
3 - Language service - create;  
4 - Clicar no botão continue to create your resource;  
5 - Botão create, aguardar o deployit.  
  
### Segunda parte:  
0 - Entrar no site https://language.cognitive.azure.com/?azure-portal=true;  
1 - Na janela que abrir selecionar a subscrição e nome de recurso que vc acabou de criar;  
2 - Clicar no botão Done;  
3 - Ir na Aba Classify text;  
4 - Ir no Box Analyze sentiment and opinions;  
5 - Inserir um texto para language studio, como o exemplo que segue abaixo.  
  
"Tired hotel with poor service  
The Royal hotel, London, United Kingdom  
5/6/2018  
This is an old hotel (has been around since 1950's) and the room furnishings are average -  becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk."  

6 - Botão run.  
