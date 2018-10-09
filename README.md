# Desafio Ionic

## Instruções
Faça um `fork` desse projeto e desenvolva em cima dele. Quando tudo estiver pronto faça um pull request. Não esqueça de alterar esse *README*, colocando aqui instruções de como rodar seu projeto e comentando qualquer coisa nele que você gostaria de nos contar, como a abordagem que você utilizou na solução do desafio, se você usou alguma arquitetura de CSS, se você pensou em alguma preocupação de performance e etc.


## O desafio
Você deverá criar um aplicativo, usando **Ionic 4** + Firebase, que será um clone do aplicativo do Netflix. 

Esse app deverá ter uma página de login e uma de cadastro (Usando Firebase Authentication). 

Na parte de login, deverá ser implementado a funcionalidade de [Fingerprint](https://ionicframework.com/docs/native/fingerprint-aio/)/[Touch ID](https://ionicframework.com/docs/native/touch-id/) para permitir que o usuário se logue com mais facilidade em nosso app.

Após logado, o usuário irá para a Home, onde serão exibidas diversas listas horizontais de filmes (use a API do [MovieDB](https://developers.themoviedb.org/3/getting-started/introduction)), que você poderá organizar como quiser. Exemplo: Exibir listas de acordo com genêro, exibir listas de acordo com popularidade, etc. Consulte as opções de query disponiveis no MovieDB e use a criatividade. :)

A unica coisa obrigatória aqui é que no topo de todas as listas deverá ter uma de "Favoritos", onde será exibido uma relação com todos os filmes que o usuário favoritar dentro do aplicativo. 

Ah, e não se esqueça que cada lista de filmes deve ser um componente isolado.

[Exemplo de lista horizontal e componente.](https://www.imageupload.co.uk/images/2018/10/09/F28459C8-3212-472D-86D4-1616734C84AE.png)

Ao clicar no filme, a pessoa deve ser levada para uma nova página que irá conter mais informações sobre o filme selecionado como sinopse, ano de lançamento e etc. Além de um icone para que a pessoa favorite aquele filme (Lembra da lista obrigatória que teremos na Home? Isso será usado para popular a mesma. Faça uma relação com os filmes favoritados do usuário no Firebase utilizando o Firestore :wink:).

Algumas coisas adicionais que seu projeto precisa ter, obrigatóriamente:

- Sass;
- Teste unitários (Aqui você é aberto pra usar o que quiser. Quer ir de Karma + Jasmine? Quer se aventurar no Jest? Quer sair da curva com Chai + Mocha? Não importa, só queremos que você teste. :heart:);
- Splashscreen + Icones;
- Tem que usar a paleta de cores e fonte que são especificada nesse repositório;
- Tem que funcionar no Android **e** no iOS.

## Estilos

### Paleta de cores

$red: #E50914 (Para detalhes, colorir botões e etc);

$black: #221F1F (Backgrounds);

$white: #f5f5f1 (Texto)

### Fonte

https://fonts.google.com/specimen/K2D
