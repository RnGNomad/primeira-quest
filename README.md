# Solucao para : Frontend Mentor - Huddle landing page with single introductory section

Essa e a minha solucao para o [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).

## Sumario de conteudos

- [Visao geral](#visao-geral)
  - [Sobre o desafio](#sobre-o-desafio)
  - [Links](#links)
- [Meu-processo](#meu-processo)
  - [Feito com](#feito-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Dificuldades enfrentadas](#dificuldades-enfrentadas)
  - [Continuo desenvolvimento](#continuo-desenvolvimento)
  - [Recursos usados](#recursos-usado)
- [Contato do autor](#contato-do-autor)
- [Agradecimentos?](#agradecimentos)

## Visao geral

### Sobre o desafio

 Esse dessafio e sobre uma "landing-page"
 o preview dele seria esse:

![foto](./src/images/desktop-preview.jpg)

Feito para testar as capacidades de Html e Css




### Links

- Link para a solucao do desafio : [Clique aqui para ver](https://your-solution-url.com)

## Meu processo

### Feito com

- HTML5 de marcação
- CSS Propriedades customizadas
- Flexbox
- CSS Grid
For styles

### O que eu aprendi

Vi que apesar de intimidador ao primeiro olhar, nao e muito dificil de se pegar o jeito de fazer uma pagina com flex e grid

Aprendi que usar Position absolute em uma imagem que esta em uma secao de 1fr no grid nao funciona muito bem hehe

### Partes do codigo que eu mudei no decorrer do projeto

Na div de "socials" antes estava dentro da div de informacoes, deixando meio errado o como a grid funcionaria
```html
 <div class="informacao">
            <h2 class="introducao">Build The Community Your Fans Will Love</h2>
            <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. 
            Create connections with your users as you engage in genuine discussion.</p>
            <a href="./work-in-progress.html">Register</a>
        </div>
        <div class="socials">
            <a href="https://www.facebook.com"   target="_blank">
                <i class="fab fa-facebook-f"></i>
            </a>
            <a href="https://www.twitter.com" target="_blank">
                <i class="fab fa-twitter"></i>
            </a>
            <a href="https://www.instagram.com" target="_blank">
                <i class="fab fa-instagram"></i>
            </a>
        </div>
```

Ah sim, lembra da imagem com Position absolute?

Eh isso ai, ela ficava nessa parte do css
```css
.container .conteudo-titulo .ilustracoes {
    height: 290px;
    align-self: center;
    margin: 15px 0 0 40px;
}
```

### Dificuldades enfrentadas

Nao enfrentei muitas dificuldades nesse desafio, nao sei se e porque estava bem facil ou eu que sou bom mesmo

felismente achei meio facil, com o prazo de apenas 2 dias de programacao, isso no tempo que eu uso para fazer o curso, que seria umas 4h/5h no total

### Continuo desenvolvimento

Gostei muito de ter trabalhado com esse Exercicio, vou continuar me esforcando cada vez mais para ser bom nessa area

mas futuramente quero ser full stack talvez, alem de programar jogos tembem...

### Recursos usados

- [Font Awesome](https://fontawesome.com) - Usado para colocacao dos emojis das redes sociais

## Contato do autor

- Website - [Alex](https://www.your-site.com)
- Frontend Mentor - [Alexandre Miguel](https://www.frontendmentor.io/profile/RnGNomad)
- Instagram - [Alex](https://www.instagram.com/alexandremf3/)

## Agradecimentos?

Teria agradecimentos aos individuos que me ajudaram mas...

fiz o projeto sozinho, sim todo ele sem pedir ajuda porque era isso que eu queria tentar ne

Olha so como eu consegui. Nao acho que tenha ficado o mais optimo, mas ja e o suficiente para mim, que sou apenas um iniciante na area da programacao frontend

Mesmo assim agradeco a comunidade incrivel que é a :

### Guilda DevEmDobro / Guilda DevQuest