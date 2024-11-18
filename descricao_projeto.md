# Projeto final RAG

Este projeto compõe a avaliação da disciplina “Grandes Modelos de Linguagem aplicados à Geração Aumentada via Recuperação” no PPGC/UFPel em 2024/2. 

O objetivo do projeto é colocar em prática os diversos conceitos discutidos ao longo da disciplina, resultando em uma implementação de um sistema RAG completo sobre algum domínio específico. 

## Sobre o domínio
Não há restrições temáticas sobre o domínio a ser utilizado. Deve ser observado, porém, a relevância do domínio para a aplicação dos conceitos de RAG. Em particular, espera-se que os documentos de origem sejam numerosos e/ou grandes o suficiente para não ser razoável simplesmente alimentar uma LLM com a totalidade das informações disponíveis. Via de regra, o total de tokens deve superar 8000 tokens significativamente.

## Sobre o pipeline
Deve-se implementar um pipeline RAG mínimo, contendo o armazenamento dos documentos, chunking e criação de embeddings, recuperação orientada a query e geração de resposta. Espera-se, porém, que se vá além em algum aspecto que seja relevante ao domínio. Espera-se a aplicação de uma metodologia mínima de avaliação do pipeline.

## Sobre a implementação
Recomenda-se o uso de Python, mas as tecnologias específicas são de livre escolha, desde que adequadas ao problema. Pode-se usar modelos de embeddings e LLMs relativamente pequenos se for necessário o uso local. Observa-se que é possível utilizar o modelo Gemini-1.5-Flash de forma gratuita dentro de certos limites, sendo uma boa opção de LLM. 

## Sobre a apresentação
É esperado que ao final seja possível testar o pipeline completo, fornecendo queries e recebendo respostas. Uma interface mínima é necessária, ainda que não precise ser gráfica. Uma sugestão é a utilização do framework streamlit que permite a prototipação rápida de interfaces, incluindo sistemas de chat. 

O código deve estar amplamente documentado, servindo também como relatório do projeto.

Uma breve apresentação (cerca de 6 slides) deve ser preparada, demonstrando as decisões, resultados,  deficiências observadas e planos de como melhorar estas deficiências. 

## Sobre a avaliação
O projeto será avaliado de acordo com a correta implementação do pipeline de acordo com as boas práticas observadas na disciplina, a adequação das decisões, evidências de tentativas de otimização do pipeline e a presença de documentação e apresentação.

## Sobre os grupos
O projeto deve ser executado em duplas. Na impossibilidade de formação de dupla, comuniquem.

## Datas
- A entrega do código, documentação e apresentação deve ser feita até 9 de dezembro.
- As apresentações ocorrerão nos dias 11 e 18 de dezembro.
- Horários adicionais para discussão do andamento do trabalho (ONLINE): todas quintas, 18h30, no link https://meet.google.com/roj-rzms-dqy
