
# Desafio Programador Protheus Unoesc
Esse é o nosso desafio para a vaga de programador Protheus na [Unoesc](https://www.unoesc.edu.br/). Serão testadas as habilidades e qualidade de código ao transformar requisitos limitados em uma aplicação.

- [Desafio Programador Protheus Unoesc](#desafio-programador-protheus-unoesc)
- [Projeto](#projeto)
  - [Escopo do Projeto](#escopo-do-projeto)
    - [Requisitos](#requisitos)
    - [Atenção!](#atenção)
  - [Tecnologias a serem utilizadas](#tecnologias-a-serem-utilizadas)
- [Avaliação](#avaliação)

# Projeto
Você terá que desenvolver uma aplicação responsável por consumir a API [brapi](https://brapi.dev) e persistir os dados de **ações** em um banco de dados relacional.

Documentação da API disponível aqui: https://brapi.dev/docs
## Escopo do Projeto
### Requisitos
* A aplicação deve persistir em uma tabela do banco de dados todos as ações (***tickers***) disponíveis na API.
* Neste cadastro de ações (***tickers***) devem conter as informações de símbolo (*symbol*) e nome (*shortname*).
* A aplicação deve cadastrar em outra tabela no banco de dados as informações de Cotação (*regularMarketPrice*), Valor de Mercado (*marketCap*), Volume de Transações (*regularMarketVolume*), Moeda (*currency*) e Data (*regularMarketTime*) destas ações.
* A aplicação deve apresentar esses valores ao usuário em formato à escolha do desenvolvedor (terminal, arquivo de texto, csv, pdf, xlsx...) com a seguinte estrutura:
  * Símbolo;
  * Nome;
  * Cotação;
  * Valor de Mercado;
  * Volume de Transações;
  * Moeda;
  * Data.
### Atenção!
* Não há requisitos quanto a escolha da linguagem de programação, framework ou banco de dados a serem utilizados na implementação.
* Versionar o projeto realizando commits com comentários do que está sendo implementado.
* Soluções parciais serão aceitas, porém o que for submetido deve estar funcionando.

Para auxiliar o entendimento do desafio, elaboramos um diagrama de classes contendo a estrutura do banco de dados:

![ER Desafio Protheus](https://user-images.githubusercontent.com/32557284/225391963-edf56be7-a835-4bc4-8017-c7dff6f055ec.png)

## Tecnologias a serem utilizadas
* Linguagem de programação à escolha;
* Banco de Dados relacional à escolha;
* Git.
# Avaliação
**O código será avaliado de acordo com os critérios:**
* Build e execução da aplicação;
* Completude das funcionalidades;
* Qualidade de código (design pattern, manutenibilidade, clareza);
* Histórico do GIT;
* Sentido e coerência nas respostas aos questionamentos na entrevista de apresentação do desafio realizada pelo candidato.

**Não esqueça de documentar o processo necessário para rodar a aplicação.**
