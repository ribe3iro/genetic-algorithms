# genetic-algorithms
Alguns programas em P5.js pra estudar os básicos de algorítmos genéticos

# <a href="https://github.com/ribe3iro/genetic-algorithms/tree/main/cell_game">Cell Game</a>
### Tenta simular uma espécie de seleção natural
Células herbívoras e carnívoras são geradas com características aleatórias (raio de percepção, velocidade, tamanho e força ao manobrar).  
O objetivo é que as células com melhores características sejam naturalmente selecionadas e sobrevivam por mais tempo.

### Regras:

Células herbívoras:
  - Azuis  
  - Vão buscar as células verdes (surgem aleatoriamente) para se alimentar  
  - Ao se alimentar, duplicam em 2 células idênticas à original  
  - Vão fugir de células carnívoras  

Células carnívoras:
  - Vermelhas  
  - Vão perseguir as células herbívoras para se alimentar  
  - Ao se alimentar, duplicam em 2 células idênticas à original  

Obs.:  
- Se não comerem por um certo tempo, as células morrem de fome
- No conflito entre 2 células, vence a que tiver maior tamanho

 # <a href="https://github.com/ribe3iro/genetic-algorithms/tree/main/smart-cars">Smart Cars</a>
### Algoritmo genético que treina populações de carros para alcançar um alvo
Múltiplas populações de carros são geradas com características aleatórias. Ao final do tempo de vida, cada população elege um melhor carro usando parâmetros como menor distância do alvo e maior distância dos obstáculos.  
As características desse melhor carro são copiadas para os demais, que sofrem pequenas mutações.  
Conforme as gerações passam, os carros com melhores características vão sendo selecionados e o desempenho das próximas gerações é aprimorado.
