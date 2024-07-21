# Frontend Mentor - QR code component

Olá a todos, este é mais um desafio feito pelo frontend mentor e estou muito feliz de compartilha-lo com o mundo!

## Ideias, Planejamento e Execução

Com Simplicidade e Objetividade sendo a base, novamente optei por formas mais simples de estlizações usando css, pensei em usar as variaveis com a criação de cores unicas para cada fonte que o projeto solicita, porém percebi que seriam descessarias, já que o numero de arquivos no projeto acabaria aumentando por uma coisa que poderia ser resolvida com uma ou duas linhas a mais de codigo, então decidi por usar o color do css normalmente. fora isto, optei por usar uma extensão de navegador para auxiliar-me melhor no enquadramento de design da receita, o perfectPixel. usei também, pela primeira vez, tabelas em HTML, a tag table, o que foi um pouco desafiador, porem mais uma aprendizado que deve ser dominado.

### O que eu aprendi

O uso de extensão no navegador torna tudo mais eficiente e também o uso de tabelas em codigo HTML, algo que nunca havia testado antes.

Pontos de destaque das classes CSS:

```html
<div class="nutrition">
          <h2>Nutrition</h2>
          The table below shows nutritional values per serving without the
          additional fillings.
          <table >
            <tr>
              <th>Calories</th>
              <td>277kcal</td>
            </tr>
            <tr>
              <th>Carbs</th>
              <td>0g</td>
            </tr>
            <tr>
                <th>Protein</th>
                <td>20g</td>
              </tr>
              <tr>
                <th>Fat</th>
                <td>22g</td>
              </tr>
            </tr>
          </table>
        </div>
```

```css
.nutrition table {
  display: flex;
  text-align: left;
}

.nutrition tr th {
  padding-top: 10px;
  border-bottom: 1px solid black;
  width: 250px;
}

.nutrition tr td {
  border-bottom: 1px solid black;
  color: hsl(31, 77%, 45%);
  width: 250px;
}

.menu {
  display: grid;
  grid-template-columns: minmax(230px, 380px);
  margin-right: 35px;
  grid-gap: 15px;
  justify-content: center;
}
```

### Desenvolvimentos futuros

prosseguirei com os desafios do fontend mentor

### sites com recursos Úteis

- [site W3schools](https://www.w3schools.com/css/css_rwd_intro.asp)
- [site chromewebstore/perfectPixel](https://chromewebstore.google.com/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi)
## Autor

- Frontend Mentor - [@MAIAN-HUNTER](https://www.frontendmentor.io/profile/MAIAN-HUNTER)
- Linkedin - [Maian-Lucas](https://www.linkedin.com/in/maian-lucas-1a796026a/)

## Conhecimentos

92% de meu conhecimento foi adquirido pelo curso de programação Dev Quest, oa outros 8% foram de documentações de sites da internet como o proprio Frontend Mentor, W3schools e de videos da plataforma youtube.