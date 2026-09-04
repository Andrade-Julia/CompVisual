---
layout: default
---
### 🌸 Atividade 3: Oi, Itália! O Domínio Espacial por Trás do Clarão

Oii meninas! Hoje na aula etendi como funciona o lightroom!

Sabe quando tiramos aquela foto tumblr, mas ficou escura demais ou com o flash estourado, e corremos para o Lightroom para salvar? 
Pois é, os sliders que arrastamos são pura matemática!

![Kylie Gui estourada](images/Kylie%20Gui.jpg)
Diva tumblr no instagram: @KylieGui

Na aula de hoje (03/09) aprendemos que esses ajustes ocorrem no "domínio espacial". Isso é um nome chique para dizer que o computador pega a nossa foto e altera os valores de intensidade diretamente pixel por pixel!

Sabe quando você precisa clarear as sombras da foto? Por trás disso existe a Transformação de Potência (Gama). Quando o programa usa um valor de $\gamma < 1$, ele magicamente mapeia os tons escuros e os expande, clareando a imagem seletivamente para revelar os detalhes. É a salvação das nossas fotos no cinema querendo ou naun! 

E pra escurecer uma foto estourada

![Oi Italia! - meme Anitta](images/oiitalia1.jpg)
https://www.tiktok.com/@x.memes13/video/7236838379088792838?is_from_webapp=1&sender_device=pc

A mesma transformação é aplicada, mas com o $\gamma > 1$, que faz exatamente o inverso: realça os detalhes nas partes mais claras e devolve a cor da nossa foto! 

Os nossos dispositivos fazem a mesma coisa, só que automáticamente e em um tempo diferente, toda vez que utilizamos nossas câmeras! E em casos como no meme  "Oi Itália" da Anitta, o pipeline de processamento do samsung dela teve que perceber o clarão e fazer esses cálculos matemáticos ao vivo e em tempo real em cada frame do vídeo... por isso ele "travou" e demorou aquele segundinho para dar oi pra Itália!

Todas as transformações que fazemos nas imagens são na verdade um monte de coisa matemática.

O O Alargamento de contraste por exemplo:

![Kylie Gui](images/kyliegui1.jpg)
Diva tumblr no instagram: @KylieGui

 Expande as intensidades da imagem para que ela ocupe todo o intervalo disponível do seu celular, deixando a foto super vibrante e com vida! E mais contraste querendo ou naum!

E se você queria ter uma estética MySpace ou Scene nos anos 2000, com certeza já inverteu as cores de uma foto! Eu fazia muito isso com meu Samsung pocket para me fingir de fantasma ou mudar as cores das coisas na casa! Na computação visual, isso é uma Transformação Linear de Negativo, calculada por uma fórmula super simples ($s = (L - 1) - r$), que inverte todas as luzes e sombras.

Então, da próxima vez que você estiver editando sua foto para deixar o feed perfeito, lembre-se: você não é apenas uma it girl, você está literalmente aplicando cálculos de processamento de imagens no domínio espacial querendo ou nawn!! 💅💻