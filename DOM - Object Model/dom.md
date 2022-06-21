# DOM - Document object MODEL

DOM é uma interface que o navegador cria para estruturar e ler aquele o código de HTML que nós criamos;

O DOM permite atualizar uma página sem precisar carregar um site, ou seja, se nós manipulamos bem o DOM, o site fica muito mais fluído aos olhos do usuário; 

Ele serve para atualizar e recarregar menos a página; 

É possível atualizar a página do usuário sem a necessidade de recarregar a página inteira, apenas manipulando o DOM; 

Um exemplo diisso é o instagram; Ele atualiza, colocando mais fotos, sem a necessidade de atualizar a página toda; 

Outro exemplo são os filtros de produtos de um e-commerce; Quando selecionamos produtos expecíficos com detalhes específicos; Isso, com o DOM, permite que não seja necessário atualizar a página inteira; 


## COM O DOM PODEMOS: 

- EDITAR O HTML;
- MOVER O HTML;
- EXCLUIR PARTES DO HTML;
- CRIAR NOVOS HTMLS
- BUSCAR HTMLS;

PODEMOS FAZER ISSO TAMBÉM COM CSS buscando classes específicas; 


## Como funciona o DOM por baixo dos panos?
- Ele atua transformando o site em uma árvore; 

Temos uma WINDOW que se abre para 3 possibilidades - a LOCATION, DOCUMENTO e o HISTORY; 

O Location - É o endereço atual do site que estamos; 

O history - É a parte que fica no canto esquerdo do navegador e com ele nós conseguimos voltar ou ver o histórico de navegação; 

O Document - É a maior parte do DOM - É onde colocamos o site inteiro; 
Ele começa a separar os elementos do site de acordo com as tags HTML que nós usamos, como: 
Element <html> 
Element <body> - Element <h1>... e por aí vai; 
Element <head>
Element <Title>
Text "Portifólio"


## Como acessar o DOM?

O navegador transforma o código HTML em um objeto JS e com isso você consegue usar funções dentro desse objeto para acessar o DOM! 

- A maneira demonstrada na aula é difícil... então no REACT existe uma maneira mais fácil. 

Diante de tudo isso o DOM tem um sério problema, ele é muito lento! 

Uma vez que todos os sites precisam de uma atualização mais rápida, o uso do DOM pode gerar problemas com a sua velocidade!