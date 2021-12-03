# Desenvolvimento de um conjunto de dados com comentários extraídos da plataforma _Twitch_ sobre o jogo _League of Legends_

[![DOI](https://img.shields.io/badge/DOI-10.5753%2Fbrasnam.2021.16128-blue.svg)](https://doi.org/10.5753/brasnam.2021.16128)
[![DOI](https://img.shields.io/badge/Zenodo-10.5281%2Fzenodo.3735090-green.svg)](https://doi.org/10.5281/zenodo.3735090)
![GitHub](https://img.shields.io/github/license/fabiolobato/hate_speech_twitch)
![GitHub last commit](https://img.shields.io/github/last-commit/fabiolobato/hate_speech_twitch)

#### **Dados sobre o artigo**
> Artigo publicado no **X Brazilian Workshop on Social Network Analysis and Mining**, no ano de 2021. A base de dados utilizada para os testes foi construída com comentários dos 10 _streamers_ mais populares no jogo _League of Legends_ e está disponível na plataforma de _Open Science **Zenodo**_.

#### **Autores**
<table>
  <tr>
    <td align="center"><a href="http://lattes.cnpq.br/0426846510205467"><img style="width: 100px; height:auto;" src="https://bit.ly/3Ej189W" width="100px;" alt=""/><br /><sub><b>Lucas D. F. Rodrigues</b></sub></a><br /><sub><b>UFOPA</b></sub></a></td>
    <td align="center"><a href="http://lattes.cnpq.br/4856853219520680"><img style="width: 138px; height:auto;" src="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K8382971J4" width="100px;" alt=""/><br /><sub><b>Luiz C. C. L. Junior</b></sub></a><br /><sub><b>UEMA</b></sub></a></td>
    <td align="center"><a href="http://lattes.cnpq.br/4510520291728075"><img style="width: 80px; height:auto;" src="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K4125840Z1" width="100px;" alt=""/><br /><sub><b>Antonio F. L. Jacob Junior</b></sub></a><br /><sub><b>UEMA</b></sub></a></td>
    <td align="center"><a href="http://lattes.cnpq.br/8320014491229434"><img style="width: 108px; height:auto;" src="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K4450672H1" width="100px;" alt=""/><br /><sub><b>Fábio M. F. Lobato</b></sub></a><br /><sub><b>UFOPA | UEMA</b></sub></a></td>
  </tr>
<table>

### :blue_book: ***Leia o artigo completo publicado no X Brazilian Workshop on Social Network and Mining (2021) clicando <a href="https://doi.org/10.5753/brasnam.2021.16128">aqui</a>.***
<br>

#### :open_file_folder: ***Para visualizar as informações e baixar a base de dados no Zenodo, clique <a>aqui</a>.***

<br>

# Resumo

O crescimento das plataformas de transmissão ao vivo como a Twitch, impulsionado pelo aumento no volume de criadores de conteúdo, impactou positivamente em uma indústria economicamente importante, os jogos eletrônicos (e-Sports). O destaque da categoria dentro do tipo Multiplayer Online Battle Arena (MOBA) vai para o League of Legends, que foi um dos responsáveis pela legitimação e profissionalização dos e-Sports. O jogo possui uma vasta gama de criadores e que trazem consigo uma grande quantidade de interações dos internautas que os assistem. Um fenômeno deletério percebido neste cenário é a proliferação de discursos ofensivos, com comentários atacando ou denegrindo pessoas ou grupos, criando uma rede de ódio. Neste ensejo, neste trabalho apresentamos um conjunto de dados construído com comentários extraídos das transmissões dos criadores com maior engajamento na plataforma, visualizando os aspectos característicos e verificando de forma experimental, como o ódio está distribuído. Esta base de dados tem o potencial de auxiliar pesquisas envolvendo a detecção e também na análise desta indústria/domínio de aplicação da temática abordada. 

***AVISO: Este repositório contém elementos que apresentam linguagem ofensiva e/ou pejorativa, e que podem causar gatilhos mentais.***

---

**Por favor, cite o nosso <a href="https://doi.org/10.5753/brasnam.2021.16128">artigo</a> e <a href="https://doi.org/10.5281/zenodo.3735090">base de dados</a> caso você utilize qualquer um dos recursos aqui disponibilizados.**

~~~bibtex
@inproceedings{brasnam,
    author = {Lucas Rodrigues and Luiz L. Junior and Antonio Jacob Junior and Fábio Lobato},
    title = {Desenvolvimento de um conjunto de dados com comentários extraídos da plataforma Twitch sobre o jogo League of Legends},
    booktitle = {Anais do X Brazilian Workshop on Social Network Analysis and Mining},
    location = {Evento Online},
    year = {2021},
    keywords = {},
    issn = {2595-6094},
    pages = {91--102},
    publisher = {SBC},
    address = {Porto Alegre, RS, Brasil},
    doi = {10.5753/brasnam.2021.16128},
    url = {https://sol.sbc.org.br/index.php/brasnam/article/view/16128}
}

~~~

~~~bibtex
@dataset{luiz_c_c_lima_junior_2020_3735091,
  author       = {Luiz C. C. Lima Junior and
                  Lucas D. F. Rodrigues and
                  Antonio F. L. Jacob Junior and
                  Fábio M. F. Lobato},
  title        = {{League of Legends and hate speech: a corpus for 
                   comments in Twitch.tv}},
  month        = mar,
  year         = 2020,
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.3735091},
  url          = {https://doi.org/10.5281/zenodo.3735091}
}

~~~

------------------------------------------
***Descrição dos arquivos***
------------------------------------------
~~~

- CNN_HS.ipynb        --> Jupyter Notebook contendo a implementação das Redes Neurais Convolucionais.
- LSTM_HS.ipynb       --> Jupyter Notebook contendo a implementação da Memória de Curto e Longo Prazo.
- RNN_HS.ipynb	      --> Jupyter Notebook contendo a implementação das Redes Neurais Recorrentes.	
- toxic_test.csv      --> Base CSV para teste dos algoritmos treinados com o toxic_train.csv.
- toxic_train.csv     --> Base CSV para treino dos algoritmos.

~~~
------------------------------------------

***Dependências***
------------------------------------------

| Pacotes      | URL    |
| ------       | ------ |
| Python       | https://www.python.org/ |
| Tensorflow   | https://www.tensorflow.org/ |
| Keras        | https://keras.io/ |
| PyTorch      | https://pytorch.org/ |
| Scikit-Learn | https://scikit-learn.org/ |
| NLTK         | https://www.nltk.org/ |

------------------------------------------