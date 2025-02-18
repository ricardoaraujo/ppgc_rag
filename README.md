# Grandes Modelos de Linguagem aplicados a Geração Aumentada via Recuperação 

## Notícias

- Disponibilizado a descrição completa do [Projeto Final da disciplina](descricao_projeto.md)
- Disponibilizado [formulário para submissão do projeto final](https://docs.google.com/forms/d/e/1FAIpQLSf_BLAFotM6x6JDW_3GMiIsv-C0R-j_dLKxVl4FY98g7pHaFA/viewform?usp=sf_link)
- A partir do dia 13/11, as aulas ocorrerão na sala **254**
- **Não teremos aula no dia 18/12, faremos as apresentações online**

# Apresentações

- [Marque sua apresentação aqui](https://appt.link/meet-with-ricardo/30-min/)
- Apresentações marcadas até 07:00 do 18/12:

| Start Date | Start Time | Conference URL | First Name | Last Name | Additional Info |
|------------|------------|----------------|------------|------------|----------------|
| 2024-12-18 | 10:00:00 | https://meet.google.com/mzr-qmhg-mof | Marcelo | Ribeiro | Grupo composto por: Lui Gill, Marcelo Ribeiro e Marcelo Dias |
| 2024-12-18 | 14:30:00 | https://meet.google.com/vop-axet-mri | Guilherme | Lima | Apresentação do trabalho, AgroRAG. Participantes: Guilherme e Marilia |
| 2024-12-18 | 15:00:00 | https://meet.google.com/rsu-tprz-uuu | Tobias | Francisco | Grupo: Eduardo Moller, Tobias Francisco |
| 2024-12-18 | 15:30:00 | https://meet.google.com/roh-fuof-awz | Aline | Timm | Apresentação de Aline  e  Lucas Seidy |
| 2024-12-19 | 08:30:00 | https://meet.google.com/yen-mfwu-qdu | Thiago | Reis Porto | |
| 2024-12-19 | 14:00:00 | https://meet.google.com/bgn-vajq-czt | Fabrício | Scaglioni | |
| 2024-12-19 | 16:30:00 | https://meet.google.com/emj-fkdb-udm | Emerson | Lopes | |
| 2024-12-19 | 17:00:00 | https://meet.google.com/ine-fkej-mdr | Bruno | Braga | Dupla: Bruno da Cruz Braga, Gustavo Lameirão de Lima |
| 2024-12-20 | 08:00:00 | https://meet.google.com/ctx-sdqn-nou | Arthur | Cerveira | Grupo: Arthur Cerveira e Carlos Calage |
| 2024-12-20 | 09:00:00 | https://meet.google.com/amv-rwrc-nrd | João Pedro | Tomaszewski |
| 2024-12-20 | 13:30:00 | https://meet.google.com/fuf-rrgb-bdh | Alexandre | Thurow Bender | Alexandre Thurow Bender, Gabriel Almeida Gomes |
| 2024-12-20 | 17:30:00 | https://meet.google.com/bfv-qunx-qry | Vagner | Seibert | 


## Sobre a disciplina

A Geração Aumentada via Recuperação (RAG - Retrieval-Augmented Generation) é um método que expande as capacidades dos Grandes Modelos de Linguagem (LLMs - Large Language Models) ao conectá-los a fontes externas, como bancos de dados ou documentos. Isso possibilita que os modelos acessem informações que não fizeram parte de seu treinamento, viabilizando sua aplicação em cenários que envolvem o uso de dados privados ou que requerem informações constantemente atualizadas, entre outras aplicações. Esta disciplina tem como objetivo introduzir os principais conceitos e boas práticas da Geração Aumentada via Recuperação.

A disciplina tem duração de 16 semanas e é dividida em duas partes. Na primeira parte, que ocupa cerca de 2/3 do período, serão apresentados e discutidos os principais conceitos, práticas e desafios no desenvolvimento de sistemas baseados em RAG. Na segunda parte, os estudantes irão desenvolver, documentar e apresentar projetos que utilizem RAG. Esses projetos comporão a avaliação da disciplina. Será incentivado o trabalho em equipe e a aplicação criativa dos conceitos aprendidos, com foco na solução de problemas reais. Ao final, espera-se que os estudantes adquiram uma compreensão sólida das possibilidades e limitações do RAG, bem como habilidades técnicas para implementar sistemas que utilizem essa abordagem de forma eficiente.

### Projetos e ferramentas

Cada estudante irá desenvolver um sistema baseado em RAG, aplicado a algum problema de seu interesse, a ser definido ao longo da disciplina. Embora a escolha da linguagem de programação seja livre, o uso de Python é incentivado e recomendado devido à ampla disponibilidade de ferramentas e bibliotecas que podem facilitar o desenvolvimento. Os projetos serão estruturados de forma a permitir o uso de ferramentas livres e/ou gratuitas. Esses projetos deverão demonstrar o uso de técnicas de recuperação de informações em conjunto com a geração de texto, abordando desafios como a integração de dados externos, otimização de desempenho e avaliação da relevância das respostas geradas. A documentação detalhada do processo de desenvolvimento será uma parte crucial da avaliação, garantindo que os conceitos teóricos discutidos em aula sejam aplicados de maneira prática e estruturada.

- Tarefa 1: [envio de proposta de RAG](https://forms.gle/MM33KehYQC5pUx5BA)
- Tarefa 2: [envio do projeto final](https://docs.google.com/forms/d/e/1FAIpQLSf_BLAFotM6x6JDW_3GMiIsv-C0R-j_dLKxVl4FY98g7pHaFA/viewform?usp=sf_link)

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
- [Colab notebook com exemplo de uso de embeddings](https://colab.research.google.com/drive/1USpU7aV-B9urycIqBthTQtDX5T55nBlU?usp=sharing)

## Bancos de dados para embeddings
- [Vector DB Comparison](https://superlinked.com/vector-db-comparison)
- [pgvector](https://github.com/pgvector/pgvector)

## Grandes Modelos de Linguagem

- [Thinking like an AI](https://www.oneusefulthing.org/p/thinking-like-an-ai)

## Pipeline RAG

![Pipleine básico de um RAG](rag_basico.png)

- [Código para um RAG básico](https://github.com/ricardoaraujo/ppgc_rag/blob/main/rag_basico.zip)

