<p align="center">
  <a href="" rel="noopener">
 <img style="width: 256px"src="img/tableLudo.png" alt="Project logo"></a>
</p>
<h1 align="center">Ludo 2.0</h1>

## 📝 Sumário

- [Objetivo do jogo](#objetivo)
- [Regras](#regras)
- [Outras Funcionalidades](#funcionalidades)
- [Como executar ?](#usage)
    - [Haskel](#haskell)
    - [Prolog](#prolog)
- [Tecnologias](#tech_stack)
- [Autores](#authors)

## 🎯 Objetivo do jogo <a name = "objetivo"></a>

Percorrer todo o trajeto do tabuleiro no sentido horario com todas as peças e ser o primeiro jogador a levar seus quatro peões ao ponto de chegada da sua cor.
<br>

## 📌 Regras <a name = "regras"></a><br>

<ol>
    <li> 
        Pode ser jogado por um player e um bot baseado em heurística e aleatoriedade. 
    </li> <br>
    <li>
        O tabuleiro quadrado tem um percurso em forma de cruz e cada jogador tem quatro peões.
    </li><br>
    <li>
        Os peões de cada jogador começam na base de mesma cor.
    </li><br>
    <li>
        Para se iniciar a partida, joga-se o dado e o participante que fizer o maior número de pontos (6) inicia o jogo retirando uma peça da base.
    </li> <br>
    <li>
       Quando o jogador já tem pelo menos um peão no percurso, joga-se um dado e os avanços são feitos de acordo com os pontos obtidos com o lançamento do dado. Se tirar 6, além de usar esse resultado ele pode jogar novamente o dado.
    </li><br>
    <li>
        Para transportar um peão de sua base para seu ponto de partida é necessário tirar (6). 
    </li><br>
    <li>
       Se um jogador chegar a uma casa já ocupada por um peão adversário, o peão adversário deve voltar para sua base.
    </li><br>
    <li>
       Mas se 2 peões da mesma cor ocuparem uma mesma casa, eles não podem ser capturados e nenhum adversário pode passar por essa casa, tendo seus peões bloqueados.
    </li><br>
    <li>
       Após dar a volta no tabuleiro o peão avança pela reta final, de sua própria cor. A chegada ao ponto final só pode ser obtida por um número exato nos dados. Se o jogador tirar mais do que o necessário, ele vai até o fim e volta, tendo que aguardar sua próxima jogada.
    </li><br>
    </ol>

## ✅ Outras Funcionalidades: <a name="funcionalidades"></a>

<ul>
    <li>O jogo terá um sistema de salvamento; </li>
    <li>Terá obstáculos pelo caminho como uma casa que retrocede duas casas;</li>
</ul>

## 🎈 Como executar ? <a name="usage"></a>

### ◾ Haskell <a name="haskell"></a>

``` bash
    # Primeiramente, faça o clone do nosso projeto digitando no terminal:
    $ git clone https://github.com/viniciuslins256/Projetos-PLP.git

    # Em seguida, no terminal digite:
    $ cd Projetos-PLP/Haskell

    # Com o stack instalado digite:
    $ stack build

    # Depois de instalar as dependencias digite:
    $ stack exec ludo
```

### ◾ Prolog <a name="prolog"></a>

``` bash
    # Primeiramente, faça o clone do nosso projeto digitando no terminal:
    $ git clone https://github.com/viniciuslins256/Projetos-PLP.git

    # Em seguida, no terminal digite:
    $ cd Projetos-PLP/Prolog/app

    # Com o swi-prolog instalado digite:
    $ swipl main.pl
```

## ⛏️ Construido com: <a name = "tech_stack"></a>

- [Haskell](https://www.haskell.org) - Functional Programming Language
- [Prolog](https://www.swi-prolog.org/) - logic Programming Language

## ✍️ Autores: <a name = "authors"></a>

- [@lucasarlim](https://github.com/lucasarlim)
- [@viniciuslins256](https://github.com/viniciuslins256)
- [@Pedro-Manoel](https://github.com/Pedro-Manoel)
- [@Felipe1496](https://github.com/Felipe1496)
