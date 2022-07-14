# Alura - Solução do Projeto Mobile First AluraBooks

Codificação de um projeto disponibilizado durante o curso de Front-end da [Alura](https://www.alura.com.br/formacao-front-end).

## Indíce

**Visão Geral**
>[Desafio](#desafio) |
>[Screenshot](#screenshot) |
>[Links](#links)

**Meu Processo**
>[Construído com](#construído-com) | 
>[O que eu aprendi](#o-que-eu-aprendi) | 
>[Recursos úteis](#recursos-úteis)

**Considerações Finais** 
>[Autor](#autor) |
>[Agradecimentos](#agradecimentos)

## Visão Geral

### Desafio

O desafio foi construir este projeto criando um menu hamburguer com HTML e CSS, integrar um carrossel com SwiperJS e fazê-lo parecer o mais próximo possível do design. Os usuários devem ser capazes de:

- Vizualizar o layout ideal tanto para dispositivos mobiles quanto para desktops;
- Vizualizar os estados de foco para elementos interativos. 

### Screenshot

![Captura de Tela (199)](https://user-images.githubusercontent.com/105252003/178901722-db44a01e-3066-4d7a-9580-d2ee3e9ef287.png)

### Links

- URL da solução: [Index](https://github.com/beatrizslan/Projeto-Mobile-First-Alura-Books/blob/main/docs/index.html)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-Mobile-First-Alura-Books/)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- Propriedades personalizadas de CSS;
- Integração do carrossel com SwiperJS;
- Flexbox;
- Mobile-first.

### O que eu aprendi

- Fazer um menu hamburguer através do HTML e CSS;
- Linkar fontes externas;
- Integrar um carrossel com SwiperJS;
- Utilizar variáveis no CSS;
- Trabalhar com o flexbox;
- Desenvolver uma página responsiva, começando pelo mobile-first.

```HTML
<div class="container">
  <input type="checkbox" name="menu" id="menu" class="container__botao">
  <label for="menu" class="container__rotulo">
      <span class="cabecalho__menu-hamburguer container__imagem"></span>
  </label>
  <ul class="lista-menu">
      <li class="lista-menu__titulo">Categorias</li>
      <li class="lista-menu__item">
          <a href="#" class="lista-menu__link">Programação</a>
      </li>
      ...   
   </ul>
</div>     
```

```CSS
:root {
    --cor-de-fundo: #EBECEE;
    }
    
body {
    background: var(--cor-de-fundo);
}
```

```JS
<script>
        const swiper = new Swiper('.swiper', {
            spaceBetween: 10,
            slidesPerView: 3,
            pagination: {
                el: '.swiper-pagination',
                type: 'bullets',
            },
        });
    </script>
```

### Recursos úteis

- [Guia Completo do Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Flexbox e quais são suas propriedades. 
- [SwiperJS](https://swiperjs.com/) - Esta é uma biblioteca que faz parte do Framework7 e me ajudou a importar o carrossel do site.
  

## Considerações Finais

### Autor

- Website - [Beatriz Slan | Alura](https://beatrizslan.github.io/Projeto-Mobile-First-Alura-Books/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)


### Agradecimentos

Gostaria de agradecer a toda equipe envolvida da Instituição Alura, pela excelente didática, plataforma de ensino e por disponibilizar projetos reais e profissionais que me ajudam muito a praticar e aprimorar todo meu conhecimento deste mundo incrível do Front-end.  
