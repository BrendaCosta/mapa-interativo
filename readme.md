## Mapa interativo do Brasil

### Zonas interativas com HTML, CSS e SVG
- 1° baixar a imagem em SVG: 
* Dica de local para baixar o mapa: https://mapsvg.com/maps/brazil

> - Path são as divisões dos vetores
> - Embaixo da divisão tem o "title" que é a identificação da area

> Se a imagem tiver colorida ou marcada, excluimos os atributos do SVG, que ficam logo no inicio da tag, o mapa/ imagem deve ficar totalmente preta

- 2° No CSS vamos estilizar o nosso mapa

~~~
// a classe pode ter qualquer nome, a obrigatoriedade é do path
.mapa path{ 
    fill: "coloque a cor"; // cor de fundo
    stroke: "coloque outra cor"; // cor da linha
    stroke-width: 2px; // espessura da linha
}
 ~~~

- 3° No HTML antes do path no SVG colocamos a tag de link para quando o mouse passar aparecer o title

~~~
<a><title>Bahia</title></a>
~~~

- 4° Para abrir um link
~~~
<a  xlink:href="#" target="_blank">
~~~

- [Projeto no Codepen](https://codepen.io/brendacosta/pen/OJgPwOG)

![Print](/mapa_print.png)