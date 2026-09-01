🫀 Ecossistema de Cardiologia Inteligente --- FASE 1

📌 Sobre o projeto

Este projeto reúne diferentes tipos de dados relacionados à área de
cardiologia com o objetivo de construir uma base para aplicações de
Inteligência Artificial na saúde.

A atividade está organizada em três frentes:

Dados Numéricos (IoT): informações clínicas estruturadas em
formato tabular;

Dados Textuais (NLP): documentos relacionados a doenças
cardíacas, sintomas, tratamentos e saúde;

Dados Visuais (Visão Computacional): imagens de exames
cardiológicos, incluindo ECGs e exames de tórax.

A proposta é demonstrar como diferentes tipos de dados podem ser
utilizadas por técnicas de Inteligência Artificial para identificar
padrões, extrair informações relevantes e apoiar análises na área da
saúde.

Observação: os dados utilizados neste projeto têm finalidade
acadêmica. Eles não devem ser utilizados para diagnóstico médico.

📊 Parte 1 --- Dados Numéricos (IoT)

Objetivo

Nesta etapa foi organizado um dataset contendo informações relacionadas
a fatores clínicos e cardiovasculares.

Os dados foram reunidos e organizados em um arquivo CSV para facilitar
sua utilização em futuras etapas de análise de dados e desenvolvimento
de modelos de Inteligência Artificial.

📁 Estrutura dos dados

Os arquivos relacionados aos dados numéricos estão organizados da
seguinte maneira:

dataset/
├── fontes/
│   ├── font1.csv
│   └── font2.csv
└── dataset_final.csv

O arquivo dataset_final.csv corresponde ao conjunto de dados preparado
para utilização no projeto.

🔗 Acesso aos dados

Os dados completos estão disponíveis publicamente no seguinte endereço:

[https://drive.google.com/drive/folders/1hZTt_Qjj5fyV46M3AU2pdZxb0S-Go9RX?usp=sharing]

O link deve permitir acesso sem necessidade de solicitação de
autorização.

🧬 Origem dos dados

Tipo de dados: SIMULADOS

Fonte: GERADO POR GEMINI

O conjunto de dados foi utilizado com finalidade acadêmica e organizado
para esta atividade.

🩺 Variáveis de maior relevância clínica

Entre as variáveis disponíveis no dataset, algumas apresentam maior
relevância para um projeto de Inteligência Artificial aplicado à
cardiologia.

Idade

A idade é um importante fator associado ao risco cardiovascular. Em um
modelo de IA, pode ser utilizada em conjunto com outras características
para identificar padrões relacionados a diferentes níveis de risco.

Pressão arterial

A pressão arterial é uma informação clínica importante na avaliação
cardiovascular. Valores elevados podem estar associados a condições que
aumentam o risco de doenças cardiovasculares, tornando essa variável
relevante.

Colesterol

Os níveis de colesterol podem contribuir para a avaliação do risco
cardiovascular. Em modelos de IA, essa informação pode ser combinada com
outras variáveis clínicas para identificar padrões associados a
diferentes perfis de risco.

Frequência cardíaca

A frequência cardíaca fornece informações sobre o funcionamento
cardiovascular e pode apresentar diferentes padrões de acordo com o
estado clínico do indivíduo. Por isso, pode ser uma característica
relevante para análises computacionais.

Histórico de doenças cardíacas

O histórico cardiovascular pode fornecer informações importantes sobre
fatores de risco e condições anteriores. Para Inteligência Artificial,
essa variável pode contribuir para a identificação de padrões associados
a maior probabilidade de eventos ou doenças cardiovasculares.

Sintomas

Informações relacionadas aos sintomas podem complementar os dados
clínicos e ajudar algoritmos a encontrar relações entre manifestações
relatadas e diferentes condições cardiovasculares.


📝 Parte 2 --- Dados Textuais (NLP)

Objetivo

Nesta etapa foram reunidos textos relacionados à área cardiovascular e à
saúde, com o objetivo de demonstrar como técnicas de Processamento de
Linguagem Natural (NLP) podem transformar informações textuais em
dados estruturados e úteis para análises.

📁 Arquivos utilizados

Os documentos estão organizados em:

assets/
└── artigos/
│   │   ├── artigo1.pdf
│   │   ├── artigo2.pdf
│   │   ├── artigo3.pdf
│   │   ├── artigo4.pdf
│   │   └── artigo5.pdf
│   │   ├── artigo1.txt
│   │   ├── artigo2.txt
│   │   ├── artigo3.txt
│   │   ├── artigo4.txt
└── └── └── artigo5.txt

Os documentos foram selecionados por apresentarem conteúdo relacionado à
saúde, cardiologia, doenças cardiovasculares, sintomas ou tratamentos. Os documentos de nome igual são os mesmos, apenas diferenciando o tipo de extensão.

🔗 Acesso aos dados

Os arquivos completos estão disponíveis publicamente no seguinte
endereço:

[https://drive.google.com/drive/folders/1ZazLtZHlx2_YWzahpmQ0mvR3vp-rR4Px?usp=sharing]

🧠 Aplicações de NLP

Os textos podem ser utilizados em diferentes tarefas de Processamento de
Linguagem Natural.

Extração de sintomas

Algoritmos podem identificar automaticamente termos relacionados a
sintomas, como dor no peito, falta de ar, palpitações e outros sinais
descritos nos textos.

Essa abordagem pode transformar informações originalmente não
estruturadas em dados que possam ser analisados por modelos de IA.

Classificação de tópicos

Técnicas de NLP podem classificar os textos de acordo com temas como
doenças cardiovasculares, fatores de risco, sintomas, prevenção e
tratamentos.

Isso permite organizar grandes volumes de documentos automaticamente.

Extração de informações clínicas

Modelos de NLP podem identificar informações relevantes
presentes nos textos, como doenças, medicamentos, sintomas, exames e
tratamentos.

Análise de sentimentos

Dependendo do tipo de texto utilizado, algoritmos também podem analisar
sentimentos. Essa aplicação pode ser útil principalmente em relatos de pacientes, questionários e conteúdos
produzidos por usuários.

🩺 Relevância para Inteligência Artificial na saúde

A utilização de NLP na área da saúde pode facilitar a análise de grandes
volumes de informações que normalmente estão armazenadas em formato
textual.

A automatização da extração e classificação dessas informações pode
auxiliar na organização de conhecimento, identificação de padrões e
apoio a sistemas inteligentes voltados à área médica.

🖼️ Parte 3 --- Dados Visuais (Visão Computacional)

Objetivo

Nesta etapa foram reunidas imagens de exames médicos para representar a
utilização de técnicas de Visão Computacional (VC) em aplicações
relacionadas à cardiologia.

Foram utilizados dois tipos de exames:

Eletrocardiogramas (ECG);

Exames de tórax / radiografias de tórax.

📁 Organização das imagens

As imagens estão organizadas da seguinte maneira:

assets/
└── exames/
    ├── ecg/
    └── torax/

A separação por tipo de exame facilita a organização dos dados e permite
que diferentes técnicas de processamento de imagens sejam aplicadas a
cada conjunto.

🔗 Acesso às imagens

O conjunto completo de imagens está disponível publicamente no seguinte
endereço:

[https://drive.google.com/drive/folders/14lubKBxcYNuE8VTZ0dcPERwho4uX0gTr?usp=sharing]

Quantidade total de imagens: 255 no total, sendo 105 exames de tórax e 250 Eletrocardiogramas (ECG).

Formato: .png

👁️ Possíveis aplicações de Visão Computacional

Detecção de padrões

Algoritmos de Visão Computacional podem aprender padrões presentes nas
imagens e utilizar essas características para diferenciar exames ou
identificar regiões de interesse.

No caso dos ECGs, por exemplo, podem ser analisadas características
visuais relacionadas às ondas e ao traçado do exame.

Detecção de bordas e características

Técnicas de processamento de imagens podem identificar linhas, bordas,
formas e outros elementos visuais relevantes.

Essas características podem posteriormente ser utilizadas como entrada
para modelos de aprendizado de máquina.

Identificação de anomalias

Modelos de Visão Computacional podem ser treinados para encontrar
padrões que se diferenciem daqueles considerados normais.

Em exames médicos, essa abordagem pode ser utilizada como parte de
sistemas de apoio à análise de imagens.

Classificação de imagens

As imagens também podem ser utilizadas para treinar modelos capazes de
classificar exames em diferentes categorias, desde que existam rótulos
adequados para treinamento e avaliação.

🩺 Relevância para Inteligência Artificial na saúde

A análise automatizada de exames médicos pode auxiliar profissionais da
saúde na identificação e organização de informações presentes em grandes
volumes de imagens.

Em um sistema real, modelos de Visão Computacional poderiam atuar como
ferramentas de apoio, contribuindo para a detecção de padrões e
priorização de exames que necessitem de uma análise mais detalhada.

Importante: a identificação automática de padrões em imagens não
substitui a avaliação de profissionais da área. Neste projeto, as
imagens são utilizadas exclusivamente para fins acadêmicos.

📂 Estrutura do projeto

ATIVIDADE 1/
│
├── assets/
│   ├── artigos/
│   │   ├── artigo1.pdf
│   │   ├── artigo2.pdf
│   │   ├── artigo3.pdf
│   │   ├── artigo4.pdf
│   │   └── artigo5.pdf
│   │   ├── artigo1.txt
│   │   ├── artigo2.txt
│   │   ├── artigo3.txt
│   │   ├── artigo4.txt
│   │   └── artigo5.txt
│   │
│   └── exames/
│       ├── ecg/
│       └── torax/
│
├── dataset/
│   ├── fontes/
│   │   ├── fonte1.csv
│   │   └── fonte2.csv
│   │
│   └── dataset_final.csv
│
└── README.md

🎯 Objetivos do projeto

Os principais objetivos desta atividade são:

Reunir e organizar diferentes tipos de dados relacionados à
cardiologia;

Demonstrar a aplicação de conceitos de IoT, NLP e Visão
Computacional;

Identificar quais informações podem ser relevantes para sistemas de
Inteligência Artificial na área da saúde;

Criar uma base organizada para futuras etapas de análise e
desenvolvimento de modelos;

Compreender os desafios relacionados ao uso de dados médicos em
soluções de IA.

⚠️ Observações

Os dados deste projeto possuem finalidade exclusivamente acadêmica.

As informações não devem ser utilizadas para diagnóstico, tratamento
ou tomada de decisão médica.

Os dados devem ser utilizados respeitando as condições de uso e as
licenças das fontes originais.

Os links externos devem estar configurados como públicos,
permitindo o acesso pela equipe responsável pela avaliação.

👨‍💻 Projeto acadêmico

Disciplina/Atividade: Inteligência Artificial

Instituição: FIAP

Aluno: Lucas

Data: 08/2026