
# Arquivos Dotenv em aplicações Springboot
Arquivos Dotenv em aplicacoes Springboot .env- Repositorio criado para documentar o processo de aprendizagem da utilização de arquivos .env com o framework springboot

## Aula 1
Na aula 1 o professor apresentou a estrutura do projeto base e o link da realese para que download.

- Clique [aqui](https://github.com/treinaweb/treinaweb-spring-dotenv/releases/tag/v1.0) para acessar a realease.

## Aula 2
Na aula 2 o professor adicionou a dependencia do spring-dotenv

```xml
<dependency>
<groupId>me.paulschwarz</groupId>
<artifactId>spring-dotenv</artifactId>
<version> 2.3.0</version>
</dependency>
```
No arquivo .env você deve usar a seguinte estrutura

```.env
NOME_DA_VARIAVEL = valor_da_variavel

```
