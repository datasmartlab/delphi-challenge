<p align="center">
  <img src="https://github.com/datasmartlab/delphi-challenge/blob/master/.github/assets/logo.png" height="150" width="150" alt="Datasmart" />
</p>

<h3 align="center">Datasmart</h3>

<p align="center">Desafio para os candidatos à vaga de desenvolvedor Delphi na Datasmart.</p>

<p align="center">:pushpin: Local de trabalho: Avaré - SP</p>

<br>

<div align="center">
  <a href="#memo-apresentação">Apresentação</a>   |   <a href="#clipboard-instruções">Instruções</a>   |   <a href="#wrench-especificações-técnicas">Especificações técnicas</a>   |   <a href="#gear-especificações-funcionais">Especificações funcionais</a>   |   <a href="#heavy_check_mark-o-que-será-avaliado">O que será avaliado?</a>   |   <a href="#question-dúvidas">Dúvidas</a>
</div>

<br>

## :memo: Apresentação

O desafio é desenvolver uma aplicação com dois cadastros relacionados (marca e produto) e um relatório, seguindo todas as especificações abaixo.

Esse desafio é um teste de nivelamento e para avaliarmos o quão bom você é :)

O desafio é público e todos os interessados que fizerem pull request receberão um feedback da nossa equipe.

Esperamos que todas as pessoas que queiram trabalhar conosco tentem realizá-lo.

A Datasmart trabalha sempre com feedbacks construtivos e, portanto, daremos sempre uma atenção especial para todos que submeterem o teste. Vale a pena tentar! :)

## :clipboard: Instruções

1. Faça um fork desse projeto;

2. Crie uma branch para o seu desafio no padrão: `git checkout -b delphi-challenge/seu-nome-sobrenome`;

3. Realize o desafio seguindo a seção de especificações;

4. Crie um README com uma descrição e instruções para compilar e rodar o projeto;

5. Adicione seu desafio para transferência `git add .`;

6. Faça commit do seu desafio `git commit -m 'Challenge'`;

7. Faça o push da branch: `git push origin delphi-challenge/seu-nome-sobrenome`;

8. Abra um pull request com o nome `Challenge: Seu Nome Sobrenome`;

9. Envie um email para `vagas@datasmart.com.br` com o título: `Desenvolvedor Delphi - Seu Nome Sobrenome`. Adicione seu telefone, LinkedIn, seu perfil do GitHub e em anexo seu currículo.

## :wrench: Especificações técnicas

- Usar Delphi XE5 ou superior

- Utilizar o FastReport para o relatório

- Usar dbExpress ou Firedac para conectar no banco

- Utilizar banco de dados Firebird

## :gear: Especificações funcionais

### Cadastro de Marcas

- A aplicação deve ter uma tela para cadastro de marcas, exibindo uma listagem das marcas existentes com um campo de busca para pesquisar, podendo adicionar novas marcas, editar e excluir.

- O cadastro de marcas deve ter os campos código e nome, sendo obrigatórios seu preenchimento.

### Cadastro de Produtos

- Deve ter também uma tela para cadastro de produtos, exibindo uma listagem de produtos existentes com um campo de busca para pesquisar, podendo adicionar novos produtos, editar e excluir.

- O cadastro de produtos deve ter os campos código, nome, preço e pertencer a uma marca, todos sendo obrigatórios seu preenchimento.

### Relatório

- Deve ter um relatório de listagem de produtos por marca, onde o usuário poderá filtrar por todas as marcas ou uma marca específica.

- O relatório deve ser ordenado ou agrupado por marca contendo todos os produtos.

- O relatório deve ser feito em FastReport.

### Banco de dados

- O banco de dados deve ter poucos exemplos e no final do teste compacte e adicione junto com o projeto.

## :heavy_check_mark: O que será avaliado?

- Conhecimento do Delphi e seus componentes utilizados;

- Boas práticas com o código (lint, indentação, padrões, etc);

- Organização e estrutura do projeto;

- Código Delphi Pascal;

- Uso do Git;

- Design e criatividade;

- Perfomance e segurança;

- Documentação.

## :question: Dúvidas

Em caso de dúvidas, crie uma issue ou envie um e-mail para `vagas@datasmart.com.br`.

Boa sorte!

---

Desenvolvido com 💖 por Datasmart