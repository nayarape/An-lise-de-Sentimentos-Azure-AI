# Análise de Sentimentos com Microsoft Azure

Este repositório contém um exemplo de como realizar a análise de sentimentos e opiniões em textos utilizando os serviços de **Text Analytics** da plataforma **Microsoft Azure**.

## Passo a Passo

### 1. Criar uma Conta no Azure

1. Acesse o portal do [Microsoft Azure](https://portal.azure.com).
2. Caso não tenha uma conta, crie uma gratuitamente.

### 2. Criar um Recurso de Cognitive Services

1. No portal do Azure, clique em **Criar um recurso**.
   
![img1](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/1.png)


3. Pesquise por **IA + machine learning** depois e **Serviços de linguagem** selecione-o.

   ![img2] (https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/2.png)
   
5. Clique em **Criar** e preencha os detalhes:
   - **Nome do recurso**: Dê um nome único para o seu recurso.
   - **Assinatura**: Escolha sua assinatura.
   - **Grupo de recursos**: Crie ou utilize um grupo existente.
   - **Região**: Selecione a região mais próxima.
   - **Preço**: Escolha o nível de preço desejado (o plano gratuito "F0" tem limitações, mas pode ser utilizado).
6. Clique em **Revisar + Criar** e, em seguida, em **Criar**.

   ![img3](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/4.png)
   ![img4](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/5.png)

### 3. Obter Chaves de API e Endpoint

1. Após criar o recurso, vá para o painel do recurso criado.
2. Na seção **Chaves e ponto de extremidade**, copie a **Chave 1** e o **Endpoint**. Você usará essas informações para autenticar na API.

![img5](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/6.png)
### 4. Configuração no Language Studio

1. Após autenticar o id do seu recurso clique em **Classify Text** , depois em **Analyse Sentiments and mine opitions**

![img6](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/7.png)

3. Selecione seu recurso, aplique seu input na linguagem selecionada e receba o feedback

   ![img7](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/8.png)




  ## ANÁLISE 


### Texto utilizado como exemplo para análise 

"Many people enjoy spending their free time in different ways. Some prefer outdoor activities like hiking or biking, while others might choose indoor hobbies such as reading or watching movies. Everyone has their own preferences based on what they find relaxing or enjoyable." 


![analise1](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/1%20analise.png)

![analise2](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/sentenca1.png)

![analise3](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/sentenca2.png)

![analise](https://github.com/nayarape/An-lise-de-Sentimentos-Azure-AI/blob/main/arquivos%20de%20imagens/sentenca3.png)


# Análise de Sentimentos e Opiniões

Este documento apresenta a análise de sentimentos e opiniões de um texto específico. A análise foi realizada para avaliar o tom geral do conteúdo e as emoções expressas em suas sentenças.

## Resultados da Análise de Sentimentos

### Sentimento Geral do Documento:
- **Sentimento**: Positivo
- **Confiança**: 96%

O sentimento geral do documento foi classificado como **positivo**, com uma confiança de 96%. Isso indica que a maior parte do conteúdo tem um tom favorável ou otimista, transmitindo uma impressão agradável de forma significativa.

### Análise das Sentenças:

1. **Sentença 1**:
   - **Sentimento**: Neutro
   - **Confiança**: 11%
   - A primeira sentença foi classificada como **neutra**, com uma probabilidade de 88% de ser vista dessa maneira. Isso sugere que a sentença não apresenta um tom claro de positividade ou negatividade.

2. **Sentença 2**:
   - **Sentimento**: Neutro
   - **Confiança**: 10%
   - A segunda sentença também foi classificada como **neutra**, com 90% de confiança. Isso indica que ela é mais informativa ou objetiva, sem expressar emoções fortes ou julgamentos.

3. **Sentença 3**:
   - **Sentimento**: Positivo
   - **Confiança**: 96%
   - A terceira sentença foi identificada como **positiva**, com uma confiança muito alta. Isso indica que o conteúdo dessa parte é fortemente otimista ou favorável.

## Conclusão:
O texto geral apresenta um **tom positivo**, com a maior parte do conteúdo sendo analisada de forma favorável. No entanto, há algumas sentenças neutras, o que sugere que partes do texto são mais objetivas ou informativas, sem um viés emocional forte. No geral, a análise indica que o texto transmite uma impressão otimista e equilibrada.

---



