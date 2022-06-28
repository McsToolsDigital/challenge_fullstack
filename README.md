      ------------------------------------------------------------
      ------------------------------------------------------------
      |||              |||      ||||||||||||||    |||||||||||||||
      |||||          |||||   |||                 |||
      |||  ||      ||  |||   |||                 |||
      |||    ||  ||    |||   |||                 ||||||||||||||
      |||      ||      |||   |||                               |||
      |||              |||   |||                               |||
      |||              |||   |||                               |||
      |||              |||      ||||||||||||||   ||||||||||||||
      ------------------------------------------------------------
      ------------------------------------------------------------
      -----------> BEM VINDO(A) AO DESAFIO MCS MARKUP <-----------
      ------------------------------------------------------------
      ------------------------------------------------------------

Bora começar uma jornada com a gente? Esse é o ponto de partida!

O que será avaliado?
 - Soluções apresentadas para os problemas propostos;
 - Qualidade e organização do código;
 - Conhecimento nas ferramentas utilizadas;

O que devo fazer?

BACKEND: Desenvolver uma aplicação em Python, utilizando frameworks e bibliotecas à sua escolha, que:
 - Busque dados da API de IPCA (Índice Nacional de Preços ao Consumidor-Amplo), do Banco Central do Brasil, por meio do método GET;
 - Extraia datas e valores e da API e armazene em um banco de dados à sua escolha;
- Leia o banco de dados e retorne os valores somados em formato JSON;
 - Disponibilize um endpoint (pelo método POST), que deverá receber como parâmetros data inicial e data final do período a ser consultado e que não permita períodos maiores que um ano e tenha a possibilidade de duas saídas, à escolha do usuário (JSON ou Excel);
 - Disponibilizar um endpoint que retorne os dados no formato escolhido pelo usuário.

FRONTEND: Desenvolver uma aplicação em React que:
 - Faça a requisição dos dados para a API construída anteriormente e disponibilize o período pesquisado e o valor da soma;
 - Permita que o usuário altere o valor da pesquisa, barrando requisições cujo período seja maior que 1 ano;
 - Permita que o usuário escolha se quer receber os dados em JSON ou Excel;
 - Permite que o usuário faça o download dos dados retornados.

Por fim, publique seu projeto na Heroku ou na AWS e atualize este arquivo com o link do projeto publicado.
Envie o link do Github para nós por e-mail.
Fique à vontade para separar backend e frontend, caso sinta necessidade. Apenas envie os links para que possamos avaliar.

Contam como diferenciais no processo:
 - Desenvolver um layout no Figma e aplicar no frontend;
 - Desenvolver uma aplicação frontend responsiva;
 - Estrutura de diretórios e organização do(s) projeto(s);
 - Qualquer implementação de melhoria ou funcionalidade que agregue valor ao sistema.

A API do Banco Central está disponível no link: https://api.bcb.gov.br/dados/serie/bcdata.sgs.433/dados?formato=json&dataInicial=01/01/2000&dataFinal=31/12/2100


Esperamos que você se divirta com o desafio.


