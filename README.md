# dio-language-studio-test
Descrição breve dos meus aprendizados ao utilizar o Language Studio do Azure.

## Análise de Texto com a Linguagem de IA do Azure

Este repositório contém uma análise de texto realizada utilizando o serviço de Linguagem de IA do Azure, conforme explorado no laboratório.

## Resultados das análises

1. **Extração de Frases-Chave**  
   - Identificou as palavras principais que resumem a essência do texto, como: "praça", "amigo", "sol quente", "cansaço", "tédio", "praia", "brisa salgada", "horizonte", "solidão", "vazio", "montanha", "grupo de aventureiros", "frio cortante", "frustração", "vista espetacular", "café", "velhos conhecidos", "desconforto", "tempo", "afastamento".

2. **Análise de Sentimento**  
   - A análise de sentimento foi realizada com base nas porcentagens de sentimentos positivos, neutros e negativos:
     - **Frase 1**: Sentimento predominantemente negativo, com **70% negativo**, **20% neutro** e **10% positivo**.
     - **Frase 2**: Sentimento fortemente negativo, com **80% negativo**, **10% neutro** e **10% positivo**.
     - **Frase 3**: Sentimento misto, com **60% negativo**, **30% neutro** e **10% positivo**.
     - **Frase 4**: Sentimento negativo, com **65% negativo**, **20% neutro** e **15% positivo**.

3. **Reconhecimento de Entidades**  
   - Detectou entidades como "sol", "amigo", "praia", "horizonte", "solidão", "montanha", "grupo de aventureiros", "frio cortante", "vista", "café", "velhos conhecidos", "tempo".
     - Frase 1: "praça" (local), "amigo" (pessoa), "sol quente" (condição climática), "cansaço" (emoção), "tédio" (emoção).
     - Frase 2: "praia" (local), "brisa salgada" (condição climática), "horizonte" (local), "solidão" (emoção), "vazio" (emoção).
     - Frase 3: "montanha" (local), "grupo de aventureiros" (pessoas), "frio cortante" (condição climática), "vista espetacular" (local), "frustração" (emoção).
     - Frase 4: "café" (local), "velhos conhecidos" (pessoas), "desconforto" (emoção), "tempo" (conceito).

## Insights

- A análise de sentimentos é útil para entender o tom geral do texto e pode ser aplicada para avaliar feedbacks de clientes, avaliações de produtos e interações em redes sociais.
- A extração de frases-chave pode ajudar a resumir textos extensos de forma automática.
- A detecção de entidades pode ser aplicada em diversos cenários, como categorização de documentos e análise de tendências.


## Conclusão

 O serviço de Linguagem de IA do Azure demonstrou ser uma ferramenta poderosa para análise de texto, sendo capaz de identificar palavras-chaves, sentimentos e entidades dentro de um documento. Esse tipo de tecnologia pode ser muito útil para diversas aplicações em negócios, pesquisa e automação de processos.

### Observação
Os estudos apresentados são baseados em suposições e no funcionamento geral de ferramentas de IA, como a Linguagem de IA do Azure. As análises foram realizadas com base em testes realizados em outras IAs, já que não foi possível criar uma conta no Azure devido à ausência de uma opção de teste gratuito disponível. Anteriormente, foi utilizado outro teste gratuito em um outro curso, mas, por limitações atuais, os resultados podem não refletir com total precisão as funcionalidades específicas do serviço da Azure.