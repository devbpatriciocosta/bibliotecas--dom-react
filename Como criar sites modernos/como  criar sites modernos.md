# Como criar sites modernos! 

O site moderno precisa:
- Ser rápido;
- Ser flexível; 
- Ser dinâmico; 

Imagina que você está desenvolvendo um chat, e você recebe uma mensagem nova a cada segundo! 

Pra atualizar a mensagem na tela do usuário, sem atualizar a página, você precisa atualizar o DOM! 

Na nossa simulação, suponhamos que o navegador demore 0.1 S para criar divs novas para cada mensagem do DOM

Ok, ainda funciona perfeitamente; 

Mas e se você recebe 10 mensagens a cada 1 segundo? 

Ok, ainda funciona, porém, se eu começar a receeber cada vez mais mensagens? 

Vai demorar cada vez mais tempos para atualizar a mensagens para o usuário; 

O NAVEGADOR NÃO VAI CONSEGUIR ATUALIZAR A TEMPO E AGORA????

É possível criar um DOM VIRTUAL!

Ou seja, nós virtualizamos o acesso ao DOM e conseguimos deixar a troca de dados e mensagens mais dinâmica e otimizada; 

O DOM VIRTUAL vai receber pacotes de dados e mandar tudo de uma vez para o navegador em LOTES, atualizando assim, tudo mais rápido; 

O VIRTUAL não é mostrado para o usuário, ele é como se fosse uma parte da memória que retém os dados e depois joga para o DOM real, que aí sim, fica visível par ao usuário;



Eu vou precisar criar um DOM VIRTUAL???? 

Não, não é necessário! 

