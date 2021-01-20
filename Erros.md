# Erros Conhecidos

## Instalação

**ERRO**
~~~shell
Classpath is empty. Please build the ptoject first e.g by running '.gradlew jar -PscalaVersio=<versionScala>'
~~~

    CAUSA: Possivelmente o diretório destino de descompactação em seu noem possui espaço

    SOLUÇÃO: Remova o espaço do nome do diretório