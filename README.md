# ProjetoUnity
<h1>Criando as Bases</h1>
  <p>
    Primeiramente após criarmos o projeto iremos aparecer numa tela vazia, sem nenhum objeto ainda.
  </p>

![Screenshot_20240601_184605_YouTube.jpg](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/099d91e0-3ad5-4f70-9fc2-d54590206381)

<p>
  devemos adicionar um objeto 3d para isso iremos clicar em “GameObject” depois vamos clicar em “3dObject” isso irá abrir uma     aba com diversos objetos 3d, devemos escolher o  objeto “cube”. Você também pode escolher o objeto “plane” e aumentar o         tamanho dele.
  Observe na imagem abaixo o objeto na cena.
</p>

![Screenshot_20240601_184646_YouTube.jpg](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/5a81a8dc-c20b-4d99-97d6-f6df0d5681cc)

<p>
  Depois vamos às proporções do objeto para fazer ele parecer mais um chão. Indo na aba “Transform”, localizada no canto          superior direito, e mudando o X, Y e Z na Scale mudamos o tamanho do objeto.
</p>

![20240601_185038.jpg](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/664dfa5c-e6bd-4c39-9608-bf93510d51c5)


<p>
  Esse deve ser o seu resultado após mudar as propriedades do cubo ou escolher o objeto “plane” e aumentar seu tamanho.
</p>

![Screenshot_20240601_185503_YouTube.jpg](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/95f0351d-4bce-4aff-a3d8-c987e76ca990)

<p>
  Agora já com um chão devemos colocar as paredes do labirinto, para isso iremos no “GameObject” novamente, depois vamos clicar em “3dObject” e escolher o “cube” novamente.
</p>

![Screenshot_20240601_185513_YouTube.jpg](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/0804e102-0525-4c98-a2f7-8f7d22bd3458)

<p>
  Vamos mudar as propriedades desse cubo para que ele se torne as paredes finais do nosso labirinto, ou seja, paredes mais longas que cubram todo comprimento do labirinto, em formato de cubo no nosso caso. Em seguida crie outro cubo e mudando as propriedades faça uma parede de proporções normais para o labirinto.
Posicione essa parede criada e depois duplique ela e posicione a cópia em outro local, às vezes para maior variedade será necessário mudar o tamanho de alguma parede. Fazendo esse processo várias vezes devemos obter um resultado parecido com o das imagens abaixo:
</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/c3cfeb8a-4c7b-412e-9b58-060a8ae38f3f)
<p>Labirinto criado com game objects cubo, mudando as dimensões para parecer uma parede</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/0af27706-b14c-4214-9ebf-a027add8c9c9)
<p>Visão de cima do Labirinto</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/2be435ad-8dce-4f0f-b693-82bf8c21d28e)
<p>Câmera ajustada pra visão total do labirinto e para facilitar prints.</p>

<hr>

<h1>Adicionando Texturas</h1>
<p>
Agora precisamos adicionar um pouco de vida aos objetos, para isso vamos colocar textura nos objetos e no chão.

Para criar uma textura primeiramente precisamos de uma imagem de uma textura.
Exemplo:
</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/83835f32-5d11-49ba-9496-86094245c12b)
<p>Textura para as paredes.</p>

<p>
  Agora vamos baixar a imagem e depois precisamos arrastar a imagem já selecionada até os assets no unity.
Em seguida, devemos clicar em “assets” e depois em “create” e escolher “material”. Deve aparecer um “material” vazio nos assets do seu projeto, clique no “material” e dê um nome a ele.
</p>

![criando_material.png](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/6927094d-f18a-4b84-91f4-3459f06d2216)

<p>
  Já no “material” devemos clicar no pontinho ao lado do nome “albedo”.
Imagem Exemplo:
</p>

![hOqgJ.png](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/9add446e-5151-4355-885a-c262520b817f)

<p>
  Clicando na bolinha ao lado de Albedo irá abrir uma janela com todas as imagens do seu projeto, clique na imagem escolhida e pronto. O material já estará pronto para uso nos objetos da cena.
Adendo importante que no material você pode mudar algumas propriedades, assim podendo mudar no “metalic” o quão metálico o seu material parecera, ou seja, o quanto irá refletir de luz. também é possível mudar no “smoothness” o quão “suave” a textura irá parecer no material.

Também se pode mudar o tiling e o offset eles no geral mudam quantas vezes a sua imagem vai se repetir no eixo X e Y.
</p>

![808f0eb9ca99725c1ceab02d1b31c09a.png](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/d43527ac-dbce-4d7f-b427-9152c1283d27)

<p>
  Em seguida é só clicar no “material” e arrastar até o objeto no nosso caso as paredes. Faça o mesmo processo para o chão
Textura pro chão:
</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/1573d36e-9d1d-41ae-86bc-bf1d6f040844)
Textura para o chão.

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/d3e32b10-f29c-4e6a-8864-5906d08a66c2)
Importando as texturas para o projeto

<p>
  Esse foi o resultado até agora:
</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/c6ac8d31-2da5-4952-a0aa-3f304a00150f)
<p>Texturas aplicadas no projeto.</p>

<hr>
<h1>Colocando Física nos Objetos</h1>

<p>Iremos colocar alguns objetos com física, eles serão 3 bolas, 2 dummys e por fim várias pedrinhas.
</p>

<h2>
Adicionando Física as bolinhas
</h2>

<p>
Começando pelo mais fácil iremos fazer primeiro as bolinhas. Para elas será necessário adicionar o objeto “sphere”, pelo método ensinado anteriormente “GameObject” -> “3d Object” -> “sphere”. após criar as bolinhas as posicione na cena, se possivel de uma forma que as bolinhas fiquem voando acima do labirinto assim fica mais fácil de ver a física funcionando.
</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/8caff50b-a183-47c7-a933-c1e013d20cfe)

<p>
  Para adicionar a física às bolinhas devemos clicar em uma delas depois ir em “add new component” e adicionar o “RigidBody” esse componente que fará a bolinha sofrer os efeitos da gravidade.
No RigidBody vai ter uma aba com as configurações do corpo, é muito importante que a opção “Use Gravity” esteja marcada para a bolinha, isso define que a gravidade atue na bolinha, e também é bem importante mudar a “mass” de 1 para 50.000, assim a bolinha terá mais peso na hora de cair e quicar. Também é necessário mudar o “Drag” para 0 e o “Angular drag” para 0.05
</p>

![1_6wFuElMJqG0bR4nYHM2D9Q.png](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/d273d1ca-3a74-42a4-9893-81a509a3523a)

<p>
  Após isso precisaremos criar um material físico para aplicar na bolinha, para isso devemos ir na aba “create” no canto superior esquerdo e depois ir em “Physic Material” , depois podemos dar um nome ao objeto e também devemos configurar esse material.


Você pode fazer assim “Dynamic Friction” no 0.5, “Static friction” no 0.5 e o “bounciness” em 1, esse último é o mais importante pois vai dar a elasticidade a bolinha assim fazendo ela quicar. De resto o “Friction Combine” você pode deixar o padrão “Average“ ou mudar para “Minumium”. Já o “Bounce Combine” é preciso mudar para “Multiply” assim a bolinha vai quicar mais.
<br>
Após isso é só pegar o material criado e arrastar até o objeto. Faça o mesmo processo nas duas bolinhas.
</p>

![1_85Gj9FJ7LHdfNQhW9QsAGg.png](https://github.com/GabrielGaudi/ProjetoUnity/assets/105759351/79cca730-3502-4f2d-b7b8-c7a0d8b1fb51)

<hr>

<h2>Adicionando Física as pedras</h2>

<p>
  Primeiro precisamos ir para a asset store, para isso podemos ir pelo navegador e pesquisar ou ir na aba “Window” e depois indo em “Asset Store”
Já na Asset Store podemos procurar um asset de pedras, de preferência gratuito, após achar clique nele e depois clique no botão azul escrito “open in Unity”.
Em seguida deve aparecer uma janela perguntando se você quer ir para o unity clique em “abrir Unity Editor”.
Já no unity ele deve abrir o “Package manager” já no seu pacote de assets clique em “Download” após o pacote ser baixado ele já pode ser importado clicando em “Import”, que deve abrir uma janela perguntando o'que se deve importar do pacote, deixe o padrão e clique novamente em “Import”. Após isso já se pode fechar o “Package manager”.
</p>


<p>
  Agora já com as pedrinhas baixadas e importadas para o projeto se deve escolher algumas delas e arrastar até a cena, colocando diversas pedrinhas em diferentes locais do chão da cena. Também é necessário colocar física nas pedrinhas, colocando o “RigidBody” e dessa vez não marcando a opção “Use Gravity”, também colocando um “Psychic Material” onde tudo pode ser padrão mais o “Bounciness” tem que ser 1 pra bolinha poder quicar nas pedras.
</p>

<hr>

<h2>Adicionando Física as paredes e chão</h2>

<p>
  Para isso devemos criar um “Psychic Material” e podemos deixar tudo no padrão menos menos o “Bounciness” afinal queremos que a bolinha pule em tudo, incluindo as paredes.
Podemos fazer o mesmo processo para o chão também criando um material para ele, porém dessa vez vamos deixar tudo no padrão porque o chão não irá fazer a bolinha pular. Ambos devem ter "RigidBody" ele pode ser padrão porém é vital que a opção "Use Gravity" esteja desmarcada
</p>

<p>Física dos muros e do chão (sem gravidade para não caírem)</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/234b2669-a665-4490-a336-0b6c8c170a42)

<hr>

<h2>Adicionando Física aos Dummys</h2>

<p>
  Para isso precisamos baixar e importar o pacote com os dummys e arrastar eles até a cena. Depois devemos criar um “Psychic Material” onde vamos deixar tudo padrão, depois precisamos colocar o “Rigid Body” com “mass” de 5000, drag 0, angular drag de 0,05 e com o “Use Gravity” marcado.
</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/d01b68c9-96bd-4c99-98ee-f9dd7146fcaa)
<p>Textura para a bola</p>

<p>Adicionando assets de pedras com física própria</p>

![image](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/a6c871c7-4c89-4501-8ae5-3ebf051061fd)

<p>No Unity:</p>

![fisicapedras](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/908757eb-7ded-4f9c-9dba-d667f9033531)

<p>Personagem da store com física e colisões diferentes das bolas</p>

![fisicaL](https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/9fdc6c16-71bf-45ae-88d2-5a37abe0f166)


<h4>Esse deve ser o resultado final:</h4>

https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/118dc756-46bb-401a-b916-ed6c90c12884



https://github.com/GabrielGaudi/ProjetoUnity/assets/162371856/304b44c7-7cf1-4aa5-8430-2d0f0369043a


