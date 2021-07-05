# Material do Tutorial Introdução aos Módulos de Análise de Dados

Autoras: @jtemporal @leportella

Esse material foi originalmente apresentado na Python Brasil 13, essa versão atualizada para ser apresentado na [Python Nordeste 2021] (edição online).

[OS SLIDES ESTÃO AQUI 😉](https://slides.com/jtemporal/intro-cdd-pyne-2021)

## Descrição

Numpy, Pandas, Matplotlib... os módulos de análise de dados são inúmeros! E suas potencialidades também! Vamos ver como ler planilhas, separar dados, criar gráficos e fazer uma série de análises usando um pouquinho de cada método. O objetivo deste tutorial é ter uma ideia de por onde começar a analisar dados!

### Configurações de ambiente

Você vai precisar de uma coleção de bibliotecas. Você pode instalá-las da sua forma favorita, mas o mais importante é usar as seguintes versões:

- Python >= `3.6` (eu tô usando a versão `3.8.2`), caso você queira instalar uma dessas versões eu recomendo o uso do pyenv e eu [ensino nesse artigo](https://jtemporal.com/pyenv-inicio/) como instalar versões do python com pyenve
- Todas as bibliotecas listadas no arquivo `requirements.txt` nas versões apontadas lá.

Caso você precise de ajuda como usar o arquivo `requirements.txt` dê uma olhada nessa [colinha que eu escrevi que explica como esse arquivo funciona](https://jtemporal.com/requirements-txt/).

Abaixo tem uma colinha de todos os passos para criar um ambiente virtual em python e  instalar os requisitos 😉

Para conferir a versão do Python na sua máquina:

```console
python --version
```

ou 

```console
python3 --version
```

Para criar um ambiente virtual:

```console
python3 -m venv .env
```

Para ativar um ambiente virtual:

```console
source .env/bin/activate
```

Para instalar os requisitos do arquivo `requirements.txt`:

```console
pip install -r requirements.txt
```

### Pré-requisitos

Conhecimento mínimo da linguagem (loops, condicionais, variáveis, etc)
 
## Tópicos abordados:

* Noções básicas do Jupyter Notebook
* Ler e trabalhar com planilhas csv
* Separação de dados
* Análises estatísticas básicas (média, moda, mediana, desvio padrão...)
* Trabalhando com dados inexistentes (substituição de dados, NaN, interpolação linear)
* Desenvolvimento de gráficos (histograma, análise no tempo, gráficos com dois eixos...)

## Outras informações

Dentro da pasta web temos páginas HTML para cada um dos notebooks. Então para fácil visualização não interativa você pode usar apenas o seu navegador favorito e ler o conteúdo dos notebooks sem precisar do Jupyter.

## Outros links úteis

- [Cheatsheet de Pandas](https://leportella.com/cheatsheet/pandas/) da [Leticia Portella](https://leportella.com/) com comandos de pandas.

## Execute os notebooks no Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jtemporal/tutorial-modulos-data-science/main)

Caso você não queira/possa instalar nada no seu computador você deve fazer um fork deste repositório, copiar o link para ele e iniciar um [Binder neste site](http://mybinder.org).

Assim você vai conseguir começar sem precisar instalar nada no seu computador.