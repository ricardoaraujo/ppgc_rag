# Grandes Modelos de Linguagem aplicados a Geração Aumentada via Recuperação 

## Sobre a disciplina

A Geração Aumentada via Recuperação (RAG - Retrieval-Augmented Generation) é um método que expande as capacidades dos Grandes Modelos de Linguagem (LLMs - Large Language Models) ao conectá-los a fontes externas, como bancos de dados ou documentos. Isso possibilita que os modelos acessem informações que não fizeram parte de seu treinamento, viabilizando sua aplicação em cenários que envolvem o uso de dados privados ou que requerem informações constantemente atualizadas, entre outras aplicações. Esta disciplina tem como objetivo introduzir os principais conceitos e boas práticas da Geração Aumentada via Recuperação.

A disciplina tem duração de 16 semanas e é dividida em duas partes. Na primeira parte, que ocupa cerca de 2/3 do período, serão apresentados e discutidos os principais conceitos, práticas e desafios no desenvolvimento de sistemas baseados em RAG. Na segunda parte, os estudantes irão desenvolver, documentar e apresentar projetos que utilizem RAG. Esses projetos comporão a avaliação da disciplina. Será incentivado o trabalho em equipe e a aplicação criativa dos conceitos aprendidos, com foco na solução de problemas reais. Ao final, espera-se que os estudantes adquiram uma compreensão sólida das possibilidades e limitações do RAG, bem como habilidades técnicas para implementar sistemas que utilizem essa abordagem de forma eficiente.

### Projetos e ferramentas

Cada estudante irá desenvolver um sistema baseado em RAG, aplicado a algum problema de seu interesse, a ser definido ao longo da disciplina. Embora a escolha da linguagem de programação seja livre, o uso de Python é incentivado e recomendado devido à ampla disponibilidade de ferramentas e bibliotecas que podem facilitar o desenvolvimento. Os projetos serão estruturados de forma a permitir o uso de ferramentas livres e/ou gratuitas. Esses projetos deverão demonstrar o uso de técnicas de recuperação de informações em conjunto com a geração de texto, abordando desafios como a integração de dados externos, otimização de desempenho e avaliação da relevância das respostas geradas. A documentação detalhada do processo de desenvolvimento será uma parte crucial da avaliação, garantindo que os conceitos teóricos discutidos em aula sejam aplicados de maneira prática e estruturada.

### Cronograma (sujeito a alterações)

| Semana | Tópico                      | Conteúdo                                                                            |
| ------ | --------------------------- | ----------------------------------------------------------------------------------- |
| 4/Set  | Introdução                  | Introdução à disciplina e IA                                                        |
| 11/Set | \-                          | \-                                                                                  |
| 18/Set | Aprendizado de Máquina      | Introdução ao Aprendizado de Máquina. Conceitos fundamentais de Redes Neurais.      |
| 25/Set | Embeddings                  | Aprendizado de representações e representação de textos                             |
| 2/Out  | LLMs                        | O que são, como funcionam, limitações                                               |
| 9/Out  | RAG básico                  | Arquitetura básica do RAG, pipelines de recuperação, integração com LLMs            |
| 16/Out | Avaliação                   | Métricas de avaliação, precisão, recall, F1, avaliação humana                       |
| 23/Out | Splitting                   | Técnicas de splitting, trade-offs entre granularidade e performance, impacto no RAG |
| 30/Out | Recuperação híbrida         | Combinação de métodos de recuperação densa e esparsa, benefícios e desafios         |
| 6/Nov  | Reranking                   | Re-ranqueamento de resultados, modelos de rankeamento                               |
| 13/Nov | RAG multi-estágio           | Expansão de query, avaliação de resultados                                          |
| 20/Nov | Fine-tuning                 | Fine-tuning de LLMs, adaptação a domínios específicos                               |
| 27/Nov | Desenvolvimento de projetos |                                                                                     |
| 4/Dez  | Desenvolvimento de projetos |                                                                                     |
| 11/Dez | Apresentações               |                                                                                     |
| 18/Dez | Apresentações               |


## Conceitos básicos: IA e ML

Grandes Modelos de Linguagem são um tipo de modelo de Aprendizado de Máquina, que por sua vez é uma área da Inteligência Artificial. Os textos abaixo introduzem alguns conceitos importantes para compreendermos estes modelos.

- [Introdução ao Aprendizado de Máquina](https://ricardomatsumura.medium.com/introdu%C3%A7%C3%A3o-ao-aprendizado-de-m%C3%A1quina-d3a8777db112)
- [Introdução ao Aprendizado de Máquina Supervisionado](https://ricardomatsumura.medium.com/aprendizado-supervisionado-5bfacca7566e)
- [Perceptrons](https://ricardomatsumura.medium.com/perceptrons-f18935009a61)
- [Introdução às Redes Neurais](https://ricardomatsumura.medium.com/uma-vis%C3%A3o-conceitual-de-redes-neurais-d053242944c9)
- [Introdução às Redes Neurais Profundas](https://ricardomatsumura.medium.com/uma-introdu%C3%A7%C3%A3o-conceitual-a-redes-neurais-parte-2-redes-neurais-profundas-c80329b11f6c)

## Embeddings

Embeddings são representações vetoriais de dados, como palavras ou itens, em um espaço de alta dimensionalidade, permitindo capturar similaridades e relações entre eles de forma numérica. Essas representações compactas são usadas para facilitar o processamento de dados complexos e melhorar o desempenho em tarefas como processamento de linguagem natural.

- [Embeddings - Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/embeddings)
- [Embeddings - Data Geek](https://www.datageeks.com.br/embeddings/)
