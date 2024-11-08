# ANALISE-E-WASTE

Trabalho da disciplina de Inteligência Artificial - Bacharelado Ciência da Computação UNIFG

O avanço tecnológico e o aumento no consumo de eletrônicos resultam em um volume crescente de resíduos, como celulares e baterias, que contêm substâncias tóxicas prejudiciais ao meio ambiente e à saúde humana. Estudos indicam uma urgente necessidade de iniciativas para o descarte correto desses materiais. Em resposta a essa demanda, o projeto propõe um sistema de coleta inteligente que incentiva o descarte consciente e recompensa consumidores por práticas sustentáveis. Dessa forma, visa-se promover um ciclo de benefícios ambientais e sociais, contribuindo para uma economia circular e um futuro mais sustentável.

[Categorização para Discussão de Colunas]()

[Planilha de Artigos e Literatura]()

[Dados]()

[DATASET]()

[Apresentação]()

Os Scripts etão ordenados na ordem sugerida, no entanto eles foram apenas utilizados para construir a planilha de [dados](https://docs.google.com/spreadsheets/d/1priwDe7UXDmy9nzbXKZTDhQG9_NOB6FZafhcmQLOTfU/edit#gid=587864036) que já está disponibilizada no [link](https://docs.google.com/spreadsheets/d/1priwDe7UXDmy9nzbXKZTDhQG9_NOB6FZafhcmQLOTfU/edit#gid=587864036).

# Análise e previsões de resíduos eletrônicos no Brasil

## Introdução
O aumento no consumo de dispositivos eletrônicos gera um crescente volume de resíduos perigosos ao meio ambiente e à saúde. Diante da urgência de soluções sustentáveis, este trabalho propõe um sistema de coleta inteligente que incentiva o descarte consciente e recompensa práticas sustentáveis. O objetivo é criar um ciclo que reduza os impactos ambientais e promova uma economia circular, engajando a sociedade em uma cultura de responsabilidade socioambiental.

## Objetivo
O objetivo principal é desenvolver um sistema de coleta inteligente para dispositivos eletrônicos, visando incentivar o descarte consciente e sustentável desses materiais. A proposta busca recompensar os consumidores por práticas ecológicas, promovendo a redução do impacto ambiental dos resíduos eletrônicos e contribuindo para uma economia circular e socialmente responsável.

## Materiais e Métodos
### Base de Dados
- Utilizamos o E-Waste Image Dataset do Kaggle, contendo imagens categorizadas de resíduos eletrônicos, como placas de circuito, baterias, televisores, entre outros. Esse conjunto de dados oferece uma base para tarefas de visão computacional, como classificação e detecção de objetos, auxiliando no desenvolvimento de soluções para a gestão e reciclagem de resíduos eletrônicos.

### Organização dos Dados
- Treino: Conjunto de dados para que o modelo "aprenda" os padrões visuais de cada classe;
- Teste: Avaliar o desempenho do modelo em dados que ele nunca viu, medindo sua precisão e habilidade de generalização;
- Validação: Auxilia no ajuste fino dos parâmetros  do modelo, garantindo que ele não fique "viciado" nos dados de treino e seja capaz de lidar bem com novos dados.


### Coleta e pré-processamento de dados
1. Importação de Dados: As imagens são carregadas e categorizadas conforme o tipo de resíduo eletrônico.
2. Limpeza e Organização: Filtragem e organização dos dados para assegurar representatividade e qualidade dos itens.
3. Processamento Inicial: Redimensionamento e padronização das imagens para uniformidade no treinamento do modelo.
4. Extração de Atributos: Uso de técnicas de Image Embedding para transformar as imagens em vetores de características para análise em IA.
5. Classificação de Tipos de Incentivos: Identificação de preferências de incentivo para promover a reciclagem, como incentivos fiscais ou vouchers.

### Variáveis do Dataset
- Os dados são organizados para identificar diferentes classes de resíduos, variando em tamanho, cor e tipo, incluindo:

Imagens de diversos resíduos categorizados (placas, baterias, etc.).
Atributos visuais como tamanho, altura, largura, entre outros, para melhor entendimento das características dos resíduos.

### Modelos Utilizados
- Foram implementados e testados diferentes algoritmos de Machine Learning para classificar resíduos eletrônicos:

Random Forest: Para lidar com variáveis complexas e melhorar a precisão na classificação.
kNN (K-Nearest Neighbors): Para categorização com base em similaridade.
Redes Neurais: Para reconhecimento de padrões complexos em imagens.

## Ferramentas Utilizadas
- Orange: Foi usado para o pré-processamento e treinamento dos modelos de IA, oferecendo uma interface amigável para manipulação de dados e construção de workflows. O uso dessa ferramenta facilitou a construção de um pipeline visual para Image Embedding, análise de dados e avaliação de resultados sem necessidade de codificação extensiva.

## Resultados
- Os modelos foram avaliados utilizando métricas como:

Precisão (Accuracy): Mede a proporção de resíduos corretamente classificados.
Recall: Mede a capacidade do modelo em identificar resíduos de interesse (evitando falsos negativos).
F1-Score: Combinação de precisão e recall, importante para avaliar a eficácia geral.
Após o treinamento, o modelo obteve bons resultados na identificação e classificação dos diferentes tipos de resíduos eletrônicos, o que indica potencial para ser utilizado em cenários reais.

## Conclusão
Este projeto demonstrou a viabilidade de um sistema de coleta inteligente para resíduos eletrônicos, integrando tecnologias de visão computacional e aprendizado de máquina para promover o descarte consciente. O sistema, além de classificar resíduos, pode servir como base para políticas de incentivo, promovendo a sustentabilidade e incentivando práticas de reciclagem na sociedade. Como futuros desenvolvimentos, planeja-se a integração com bases de dados públicas e o uso de técnicas avançadas para melhorar a precisão e a eficiência do sistema.
