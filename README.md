# lab-pw-2017-1

Este projeto é uma atividade prática da disciplina de programação para web do curso de<br/>
Sistemas de Informação UFG-INF. Consiste em usar bootstrap para melhorar a aparência da autobiografia produzida como prática 01<br/>
Orientação: Profº: Walison Moreira<br/>

## Autobiografia.
 
## Para rodar o projeto siga os passos abaixo

### primeiramente faça o clone do projeto usando o comando abaixo no gitbashe.

`git clone https://github.com/JonesQuito/autobiografia-com-bootstrap`

### Rodar com o Tomcat.

`mvnw org.apache.tomcat.maven:tomcat7-maven-plugin:run`  --> caso apresente erro, use o comando abaixo<br>
`mvn tomcat7:run`<br>

### Acesso via navegador

`http://localhost:9090/autobiografia-com-bootstrap`

No Linux, use `./mvnw` ao invés de apenas `mvnw`, como no Windows. Além disso, pelo menos uma vez, é preciso dar permissão de execução ao arquivo de script **mvnw** com o comando `chmod +x mvnw`.

## Opções para empacotar a aplicação:

### Para "empacotar" a aplicação sem adicionar o maven.

`mvnw package`

### Empacotar a aplicação incluindo o maven no projeto

`mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9` 

