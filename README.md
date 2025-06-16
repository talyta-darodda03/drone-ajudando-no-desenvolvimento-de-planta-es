O projeto do jogo começou com a ideia de criar uma animação interativa em p5.js, onde um drone sobrevoa uma plantação e combate pragas que ameaçam o crescimento das plantas. O objetivo principal era unir conceitos simples de programação visual e interação para representar o uso da tecnologia no campo.

No início, defini a estrutura básica do cenário: uma área verde representando a plantação com diversas plantas espalhadas na parte inferior da tela. Cada planta cresce gradualmente ao longo do tempo e pode ser afetada pela presença das pragas. Para isso, criei a classe Plant, responsável por controlar o tamanho da planta e o efeito das pragas sobre seu crescimento.

Em seguida, implementei o drone como uma entidade móvel que o jogador pode controlar usando as setas do teclado para se deslocar horizontalmente. Para atacar as pragas, o drone possui a capacidade de lançar veneno — representado por pequenas bolinhas que caem para baixo. Isso foi feito criando uma classe Bullet que controla o movimento descendente do veneno e detecta colisões com as pragas.

As pragas, por sua vez, são representadas como pequenos círculos marrons que ficam posicionados próximos às plantas. Para tornar o jogo mais dinâmico, implementei um comportamento em que as pragas tentam fugir do drone quando ele se aproxima, simulando uma reação natural de fuga. Esse movimento tornou a interação mais interessante e desafiadora para o jogador.

Durante o desenvolvimento, também cuidei para que a colisão entre o veneno e as pragas fosse detectada, removendo as pragas acertadas e permitindo que o jogador tenha feedback claro sobre suas ações. Além disso, foi incluído um sistema simples para o crescimento das plantas, que é desacelerado pela presença das pragas, mas pode ser acelerado pela proximidade do drone, incentivando a proteção da plantação.

Por fim, o jogo foi estruturado para ser simples, didático e interativo, com controles intuitivos (setas para mover o drone e espaço para lançar o veneno), proporcionando uma experiência que une aprendizado sobre agricultura e tecnologia de forma lúdica.

Assim, o código integra elementos visuais, controle de usuário, física básica e lógica de colisão para criar um jogo funcional e educativo sobre o combate às pragas na agricultura usando drones.

