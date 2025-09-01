# Animação Screensaver DVD Clássico 📀

Uma recriação da clássica animação de "screensaver" do logo da DVD, que quica nas bordas da tela e muda de cor a cada colisão. Este projeto foi desenvolvido puramente com HTML, CSS e JavaScript, sem a necessidade de bibliotecas ou frameworks externos.

## 🎬 Demonstração

<img src="./.github/Loop Bounce GIF by Meg Lewis.gif" alt="Animação do DVD em ação">

## 🚀 Funcionalidades

- **Movimento Diagonal:** O logo se move pela tela em um ângulo de 45 graus.
- **Detecção de Colisão:** Detecta quando o logo atinge qualquer uma das quatro bordas da tela.
- **Mudança de Direção:** Inverte a direção do movimento no eixo correspondente (horizontal ou vertical) após uma colisão.
- **Mudança de Cor Aleatória:** A cor do logo é alterada para uma cor aleatória a cada colisão.
- **Responsivo:** A animação funciona em qualquer tamanho de tela, se adaptando à janela do navegador.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura base da página.
- **CSS3:** Estilização do cenário e do logo.
- **JavaScript (ES6):** Lógica da animação, detecção de colisão e manipulação do DOM.
- **SVG:** O logo do DVD é um gráfico vetorial escalável, permitindo a mudança de cor e mantendo a qualidade.

## ⚙️ Como Executar

Este projeto não requer nenhuma instalação ou build. Basta seguir os passos abaixo:

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd SEU-REPOSITORIO
    ```
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).

E pronto! A animação começará imediatamente.

## 🎨 Customização

Você pode facilmente alterar alguns parâmetros no código para customizar a animação:

### Velocidade

No arquivo `index.html` (ou `script.js` se estiver separado), altere os valores das variáveis `xSpeed` e `ySpeed`:

```javascript
// Velocidade e direção iniciais
let xSpeed = 4; // Altere para aumentar/diminuir a velocidade horizontal
let ySpeed = 4; // Altere para aumentar/diminuir a velocidade vertical
```

### Tamanho do Logo

No CSS (dentro da tag `<style>` no `index.html`), modifique as propriedades `width` e `height` do seletor `#dvd-logo`:

```css
#dvd-logo {
  width: 150px; /* Altere a largura */
  height: 75px; /* Altere a altura */
  /* ... outras propriedades */
}
```

---

Feito com ❤️ por Duda Bauer.
