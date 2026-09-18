---
layout: default
---
### 🌸 Atividade 4: O que fazer com sua melhor foto? O segredo do zoom

Oiê! Sabe quando você tira *A* foto e quer usá-la para tudo? foto de perfil no WPP, instagram, linkedin, twitter, crachá da empresa, etc...

E pra usar em todos os lugares, sempre temos que cortar um pouquinho aqui... esticar alí... para caber no formato necessário!

E quando você tenta esticar a imagem ela fica toda estourada e cheia de quadrados? Não dá pra usar assim né? Na nossa aula de Computação Visual, eu aprendi que a matemática usada para tentar salvar essas imagens se chama Interpolação.


Basicamente, a interpolação é um processo em que o computador usa uma função para estimar valores que não foram medidos ou amostrados na imagem original. Ou seja, quando queremos redimensionar e ampliar uma foto, o computador precisa "adivinhar" e criar pixels novos para preencher os espaços em branco. 
Olha só as duas formas mais babadeiras dele fazer isso:

*A técnica do Vizinho Mais Próximo (O modo preguiçoso):* Para preencher o novo espaço, o computador simplesmente olha para o pixel original e faz uma cópia da cor do pixel mais próximo. É uma técnica super rápida e simples, mas é exatamente ela que deixa a imagem com aquela aparência "pixelada" ou de baixa qualidade quando damos um zoom muito grande

*A técnica da Interpolação Bilinear (A it girl da matemática):* Em vez de só copiar de qualquer jeito, essa técnica é super refinada. O computador olha para os quatro vizinhos mais próximos daquele espaço vazio. A partir daí, ele calcula uma média ponderada das cores com base na distância que o nosso novo pixel está desses vizinhos. O resultado é uma transição muito mais suave!

![Numquidito](images/nu-qui-dito-nuquidito.gif)

Então, da próxima vez que você der zoom na sua foto para ver um detalhe ou pra encaixar ela em algum canto e ela continuar perfeita, agradeça aos divos cálculos de interpolação rodando nos bastidores! 💅💻