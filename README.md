# Jogo_Dino
Desenvolvimento do jogo Dinossauro
 ## A lógica desenvolvida basicamente foi esta:

 1. Verifica se a tecla espaço foi pressionada (event.keyCode === 32).
 2. A função "jump" realiza as condições para o dino pular:
    A função setInterval() é a temporizadora de intervalos (executa infinitamente até encontrar o clearInterval() );     
    Esses intervalos são os testes para o Dino realizar a ação de subida e descida;
 3. Os cactos surgem com a funçao random (número aleatório) da biblioteca Math multiplicado cada 6000 milésimos.
 4. A verificação de contato é conforme a posição (dimensão) do dino e o cacto caso ocorra o resultado é GAME OVER!
 5. O deserto é animado com o próprio CSS utilizando a propriedade de repetição infinita.
