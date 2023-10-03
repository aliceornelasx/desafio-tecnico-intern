# Questionário para estágio de desenvolvedor web (PHP/JavaScript)

Para responder a este questionário, crie um fork do repositório e responda às perguntas no arquivo README.md. Em seguida, envie o link do seu fork para análise.

## Questionário

- Explique o que é um framework web e qual a sua importância.
  Framework web são softwares feitos para a internet, é importante pois além de acessível no aprendizado também tem infinitas possibilidades e soluções.
  
- Quais são os principais frameworks web PHP?
- Laravel, Symfony e CodeIgniter.
  
- Quais são os principais frameworks web JavaScript?
- ReactJS, Vue, Angular e Node.
  
- Explique o que é um banco de dados relacional e quais são os seus componentes.
- Um banco de dados relacional é composto de tabelas e cada tabela possui campos. Relacional consiste em um campo que faz a ligação entre as outras tabelas (chave primária, id). Seus componentes principais são, select, insert, delete e update.

- Quais são os principais tipos de dados em SQL?
Seus principais tipos de dados são: int, string, booleano, datetime, entre outros.

- Crie uma função em PHP que receba um nome e uma idade como parâmetros e retorne uma mensagem de boas-vindas.
- <?php
public function index($name, $age) {
  echo 'Bem vindo: '.$name.' '.$age;
}

- Crie uma função em JavaScript que receba um número como parâmetro e retorne o seu fatorial.
- function fat(value){
  if(value === 0){
    return 1
  }

  return value * fat(value - 1)
}


- Crie uma query em SQL que retorne todos os registros de uma tabela.
- SELECT * FROM <table_name>

- Explique o que é uma API e quais são os seus benefícios.
 Uma API são estrutura de dados no servidor voltadas para a web, baseada em alguns tipos HTTP sendo os mais comuns: GET, POST, PUT, DELETE e além disso tem um benefício para controlar o retorno das chamadas. Os benefícios são que com uma API bem estruturada, o desenvolvimento fica fácil e também de fácil interação com outros sistemas.
  
- Descreva um projeto de desenvolvimento web que você já realizou.
- Realizei meu portfólio ano passado com HTML, CSS e um pouco de JavaScript. Nele também tem uma calculadora que fiz após uma vídeo aula no youtube.

## Entrega

Ao finalizar o desafio, envie o link do seu fork para nós. Avaliaremos a estrutura, clareza, boas práticas e funcionamento correto.
Boa sorte!
