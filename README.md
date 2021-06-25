# TG1 - 5º semestre de BD

 
teste

Professor da Disciplina: Giuliano Bertoti 

 

# TG

 

Aluno: Thiago Dias Penha dos Santos - ra
Orientador: Emanuel Mineda

 

Título do TG: (título)

 


 
# 1.	INTRODUÇÃO


É recorrente os anúncios e alertar a respeito das famosas “Fake News” e diante um gigantes mar de informações relevantes que somos expostos em nosso cotidiano através da internet, é difícil distinguir o que é real e o que pode ser falso. [1]

Estar informações falsas são circuladas em grande quantidade através de redes sociais e muitas vezes até serem identificadas como falsas, já fizeram grande estrago.
Entretanto, informação é nosso principal pilar ao realizarmos nossos direitos civil de voto e com a presença das Fake News podemos ser levados a realizar erros em nossas decisões a respeito de quem colocar no poder.

Diante tal adversidade é preciso que o eleitor pesquise as fontes de cada artigo, após esta validação seria preciso que o mesmo buscasse as emendas propostas e votadas por seu candidato para ver se suas ações estão de acordo com o proposto em seus discursos e por final tentar alinhar e encontrar possíveis ligações ou motivos que levaram o seu candidato a tomar tais decisões.

Como partida que pertence, ligações com empresas, votos e emendas efetuadas anteriormente, tudo isto gerando um grande desgaste para o eleitor.

Estas ideias, buscam em captar o voto do eleitor e são baseadas nas três leis Vans Parijs.

A primeira sendo a força educativa da caça aos votos, faz com que a classe política tenha uma necessidade de correr atrás de eleitores e de votos, isso forçando os líderes políticos a ter contato e ouvir sua população caso queiram ser reeleitos fazendo com que eles tomassem decisões melhores. 

A segunda razão é baseada na deliberação que a democracia trás, que é a formulação e discussão de argumentos, o processo de diálogo e embate de ideias. Então a força da hipocrisia vai atuar nas discussões que a democracia tem, tanto nas pré eleições, na campanha eleitoral, em debates, como depois das eleições em camarás. Essa necessidade de diálogo faz com que os candidatos tentem a desenvolver discursos que apelem para o interesse geral da população, ou ao menos dos interesses do eleitorado dele ou representados na assembleia. 

"Sincero ou não, esse discurso acaba tendo algum impacto sobre os atos dos aspirantes a líderes. A necessidade de soar bem no fórum deliberativo civiliza não somente suas palavras, mas também suas políticas" - Vans Parijs.

E a terceira força, a força disciplinadora da autoimposição, é a força que dá poder ao povo de tirar do poder quem está lá, isso é um mecanismo para tentar garantir as duas primeiras forças. [2]

## 1.1. Objetivos do Trabalho 
O objetivo geral deste trabalho é encontrar possíveis padrões e analisar o posicionamento político dos candidatos encontrados nos bancos de dados do governo, através de plataformas que disponibilizam estes dados ao publico geral.
Para a consecução deste objetivo foram estabelecidos os objetivos específicos:

•	Realizar uma investigação sobre os atuais candidatos encontrados nos bancos de dados público disponibilizados na internet.

•	Propor possíveis padrões de votos realizados pelos candidatos.

•	Procurar possíveis variáveis que influenciem nos votos.

•	Expor possível falso posicionamento politico.


## 1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:
No Capítulo 2 é feita a fundamentação das tecnologias que serão utilizadas durante o desenvolvimento da aplicação
O Capítulo 3 apresenta o desenvolvimento da solução, onde será utilizado data-marts, data mining e diversas ferramentas para facilitar o processo.
No Capítulo 4 são apresentados os resultados do processamentos dos dados, onde deve ser encontrado padrões;
O Capítulo 5 apresenta as considerações finais  deste trabalho a partir da análise dos resultados obtidos.

# 2. FUNDAMENTAÇÃO TÉCNICA
Durante o desenvolvimento deste projeto será utilizado data-marts públicos, a linguagem de programação python e frameworks como NumPy, Pandas e Matplotlib para a transformar o dados catalogados em gráficos de fácil visualização.

## 2.1. Data Mart
O conceito de data mart é o sub-conjunto de dados que são aplicados em um data warehouse, sendo assim é necessário para este projeto encontrar diversos bancos de dados e unir os mesmos para encontrar padrões e catalogar de forma eficiente os mesmos.

## 2.2. Python
Python é uma linguagem de programação orientada a objeto de alto nível e de eficiente performance para leitura e análise de dados. Teve seu lançamento em 20 de fevereiro de 1991 e houve diversas novas versões desde então. [3]

## 2.3. NumPy
NumPy é uma biblioteca usada para cálculo de arrays multidimensionais, oferecendo uma vasta quantia de funções. [4]

## 2.4. Panda
Panda é uma biblioteca para a manipulação e analise da dados, otimizado para filtrar e limpar dados, inserir e deletar colunas em conjunto de dados e juntar dados.

## 2.5. Matplotlib
Matplotlib é uma biblioteca python focada na geração de gráficos, com objetivo em facilitar a leitura e entendimento dos dados.


# 3. DESENVOLVIMENTO
O objetivo deste capítulo é apresentar o desenvolvimento da ferramenta que será responsável por analisar os dados fornecidos.

## 3.1. Arquitetura do Sistema
Quando se trata de analise de dados é preciso que sua arquitetura seja elástica e capaz de suportar uma grande quantia de processamentos, para isto será utilizado um banco NoSQL.
Para o processamento em lote das informações será utilizado Python.

## 3.2. Dados
Para a aquisição de dados validos a serem processados durante o projeto será utilizado a plataforma http://dados.gov.br/ e http://www.portaldatransparencia.gov.br/

# Bibliografia
[1] http://www.scielo.mec.pt/scielo.php?script=sci_arttext&pid=S2183-54622018000100012 - Acessado 01/07/2020
[2] Van Parijs, Philippe. Demos-cracia para a União Europeia: por que e como?. In: A. Lavalle, A. de Vita & C. Araujo eds., O papel da teoria política contemporânea. Justiça, constituição,democracia e representação, Alameda Editorial  : São Paulo 2015, p. 19-41 Vans
[3] https://www.python.org/doc/essays/blurb/ - Acessado 01/07/20
[4] https://numpy.org/doc/stable/user/whatisnumpy.html - Acessado 01/07/20

