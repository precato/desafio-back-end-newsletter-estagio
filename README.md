<h1 align="center">Desafio: Desenvolvedor Back-end Estágio</h1>

<p align="center">

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;
</p>

# :rocket: Sobre o desafio
Para você já ir se aquecendo para o que está por vir, queremos propor um desafio para você.

Queremos que você implemente um servidor que recebrá consulta a uma base de inscrições de um formulário. A partir das regas de negócio definidas, você precisará construir uma API REST que realize uma consulta em um banco de dados utilizando filtro de datas fornecidas na requisição e retorne as informações encontradas.

- **Consulta por data:** No sistema de captação de leads, temos um formulário de inscrição em um fluxo de mensagens com notícias e informações sobre os precatórios de nossos clientes. As informações coletadas no formulário ficam armazenadas em uma tabela de um banco de dados relacional e queremos extrair relatórios de volume de inscrições de acordo com uma data inicial e uma data final. Para isso, precisamos de uma API capaz de receber a data inicial e a data final, realizar a consulta filtrada no banco de dados e retornar as informações encontradas.

- **Observações:** O desafio deve ser desenvolvido utilizando Javascript ou Typescript, sendo obrigatória a utilização de NodeJS.

## Regras de negócio
1. A consulta só deve ser feita com datas válidas (a data recebida deve ser realmente uma data e a data final não deve ser menor que a data inicial).

2. A propriedade "created_at" da tabela forms_answers deve ser preenchida com a data de inscrição do formulário.

## Dados
Para te ajudar a entender um pouco melhor, essa é a entidade da tabela forms_answers, necessária para você resolver o seu desafio.

<p align="center">
  <img  src="./assets/forms_answers.png">
</p>

# :calendar: Entrega
Para entregar esse desafio, você deve criar um repositório no **GitHub** contendo a sua implementação junto com as informações necessárias para rodar o seu projeto.

Em seguida, basta enviar o link do repositório para o email **dev.gi@precato.com.br** com o assunto **"Desafio desenvolvedor back-end estágio"**.

- **Observações:** Não esqueça de deixar o repositório público para que possamos visualizar sua resolução. 😉