# Especialista em SQL - Digital Inovation One
Projeto proposto pela plataforma Digital Inovation One para
praticar técnicas e conceitos aprendidos nas aulas.

## Contato

- Nome: Paulo Braga
- E-mail: paulobraga@pauloads.com.br
- Linkedin: https://www.linkedin.com/in/paulo-b-neto/

## Autores

- [@ppbn890](https://github.com/ppbn890)

## Versões

### Modelagem de Dados E-commerce

#### Conhecimentos utilizados

- Foram colocados em prática toda a teoria relacionada ao projeto conceitual de um Banco de dados, ao planejamento da estrutura lógica, modelagem e refinamento.

#### Informações adicionais
- Postarei a evolução desse projeto de acordo com os novos módulos do curso.

#### Tudo gira em torno do pedido nesse projeto:

- Um pedido possui busca as informações de um ID de cliente, que por sua vez busca informações de dados desse cliente, endereço e formas de pagamento.
- Esse mesmo pedido pode ter N produtos. Esses produtos, por sua vez, estão sujeitos à relações de estoque disponível, fornecedores e possivelmente vendedores terceiros que se afiliaram à plataforma.
- Por fim, um pedido possui informações de entrega, e toda a entrega está relacionada a uma empresa parceira que realiza o serviço.

### Projeto Conceitual e Modelagem de Dados - Oficina Mecânica

#### Conhecimentos utilizados

- Foram colocados em prática toda a teoria relacionada ao projeto conceitual de um Banco de dados, ao planejamento da estrutura lógica, modelagem e refinamento.

#### Informações adicionais
- Postarei a evolução desse projeto de acordo com os novos módulos do curso.

#### Objetivo:
- Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida

#### Narrativa:
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
