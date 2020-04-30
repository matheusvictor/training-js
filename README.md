# js-iniciante

Nesta atividade, poderão ser colocados em prática alguns recursos de JS, como vetores (e funções como map e filter), objetos, eventos, DOM, entre outros.

Tendo [estes dados](https://pastebin.com/uV6j9EQY), vocês irão fazer um "sistema" com os seguintes recursos:

**Obs:** Entendam como banco de dados o vetor de cidadãos que deixei no link acima.

* adicionarCidadao() - Adicionar uma pessoa ao banco de dados (não permitindo ter CPFs já cadastrados);
* selecionarAdultos() - Ver apenas os que são maiores de idade;
* filtrarPorUF() - Ver quais pessoas do banco de dados são de uma determinada UF;
* pesquisarPorCPF() - Pesquisar pessoas no banco de dados pelo CPF;
* removerCidadao() - Remover um cidadão do banco de dados pelo CPF;
* consultarCriancasVivas() - Ver quais pessoas que estão vivos e são crianças (considerem as que têm até 12 anos)

**Requisitos:**
* Vocês **devem usar o Git** nesta atividade.
* Prevenção e tratamento de erros (não obrigatoriamente usando recursos como try/catch), pois é muito importante em um programa como este.
* Boas práticas de código, tais como a indentação, a nomenclatura de variáveis, estrutura das pastas, etc.

EXTRA:
* Criar cidadãos apenas com CPFs válidos (isso fica pra pesquisa hehe);
* Usando a API [ViaCEP](https://viacep.com.br/ws/01001000/json/), cadastre a cidade e uf de uma pessoa apenas com o CEP;  
**Obs:** Para isso, veja os conceitos de API, REST, JSON, Ajax, XHR, Promises e funções assíncronas, disponíveis pela web e na MDN.

**Orientações:**
* Você poderá utilizar o Mozilla Developer Network (MDN), por exemplo, para procurar por funções e recursos.
* No caso do CPF, procure pelo **algoritmo**, mas evite utilizar códigos prontos.
