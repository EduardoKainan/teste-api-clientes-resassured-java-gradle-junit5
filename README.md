# Framework de Teste Automatizado com Java, RestAssured, Junit5 e Gradle

Esse é um exemplo de framework de teste automatizado de estudo tanto de programação quanto testes automatizados, disponibilizado pelo professor Vinicius Pessoni.
[disponível aqui][Comunidade Tester Global](https://viniciuspessoni.com/comunidade-tester-global/)

Nessa framework de teste usei Java, Junit5, RestAssured e Gradle para programar os testes do microserviço (API) que ensinamos nos cursos mencionados acima.


### Requisitos

Baixe e instale o [INTELIJ](https://www.jetbrains.com/idea/)

Baixe e instale a JDK mais recente [JDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)


### Como rodar esse projeto usando o IntelliJ ou Terminal
Clone ou baixe esse projeto em seu computador.

Clone ou baixe a [API de exemplo do curso de teste de APIS](https://github.com/vinnypessoni/exemplo-API) e a execute de acordo com o README da API.


#### Executando pelo IntelliJ

Após importar esse projeto no IntelliJ, navegue até a pasta src/test/java e abra a classe TestaCliente.

Um botão verde (um play) deve aparecer ao lado do nome da classe na linha 11, basta apertar ele.

Os testes serão compilados e os resultados serão exibidos na tela de execução do Intellij.

#### Executando pelo Terminal

Uma outra possibilidade é executá-los por meio do terminal.

Navegue até a pasta em que voceê baixou ou clonou os arquivos e use os comandos:
 
    Linux/Mac
    
        ./gradlew clean test  
    
    Windows
    
        gradlew clean test 

#### Relatórios

Os resultados dos testes são exibidos na tela do Intellij ou terminal.
 
Além disso, geramos um relatório .html a cada execução. 

Esse relatório está na pasta 

    build -> reports -> tests -> test -> index.html


#  Canais do Professor =}

😍 [YouTube]( https://www.youtube.com/c/pessonizando) 

💗 [Instagram](https://www.instagram.com/pessonizando)

⭐ [Telegram](https://t.me/pessonizando)
