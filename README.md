# Cod3r Cursos
Repositório com os conteúdos da Cod3r Curso. 

## Tecnologias a serem utilizadas
1. <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> 
2. <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
3. <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
4. <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
5. <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
6. <img src="https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
7. <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
8. <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
8. <img src="https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
10. <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>

## HTML 
**Descrição**: Hyper Text Markup Language 
O HTML (HyperText Markup Language) é a base da web e permite estruturar o conteúdo das páginas. Aqui estão os pontos principais que explorei hoje:

### 1. Estruturação com Títulos

Uma das primeiras coisas que aprendi foi sobre o uso das tags de título. O HTML possui seis níveis de títulos, que vão de h1 a h6. Cada nível indica uma importância hierárquica no conteúdo:

- <b> h1 </b> é o título principal, geralmente utilizado uma única vez em uma página;
- <b>h2</b> e <b>h3</b> e os demais são subsequentes, usados para seções e subseções.
Isso não só ajuda na organização visual, mas também melhora a acessibilidade e SEO das páginas.

Isso não só ajuda na organização visual, mas também melhora a acessibilidade e SEO das páginas.

### 2. Entendendo as Tags
As tags são os blocos construtivos do HTML, que definem os elementos da página. Cada tag tem uma função específica, como:

- <b> p </b> para parágrafos ,
- <b> a </b> para links,
- <b> img </b> para imagens.

Entender a função de cada uma dessas tags foi essencial para criar a estrutura básica de uma página.

### 3. Listas: Ordenadas e Não Ordenadas
Aprendi a usar as tags <b> ul </b> e <b> ol </b> para criar listas.

- <b>ul</b> cria listas não ordenadas, exibidas com marcadores como bolinhas;
- <b>ol</b> cria listas ordenadas, numeradas automaticamente.
Essas listas são ótimas para organizar informações de maneira clara e direta.

### 4. Semântica: HTML Além da Estética
Um dos conceitos mais importantes foi a semântica no HTML. Usar tags semânticas como <b>article</b>, <b>section</b>, <b>header</b> e <b>footer</b> ajuda a descrever o propósito dos elementos de maneira clara. Isso torna o código mais legível e fácil de manter, além de melhorar a acessibilidade, já que leitores de tela entendem melhor o conteúdo.

![Tags não semânticas e semânticas](.//assets/imgs/tags_html.png)


### 5. Estrutura Básica de um Documento HTML
Toda página HTML começa com uma estrutura básica:
![Estrutura básica de um arquivo HTML](.//assets/imgs/estrutura_basica.png)

O cabeçalho <b>head</b> contém informações como o título da página e meta dados, enquanto o corpo <b>body</b> define o conteúdo visível, incluindo seções como o <b>header</b> e o <b>footer</b>.

<!-- <h4>DOM: Document Object Model</h4> -->

### 6. Formulários
```js
  <form action="#">
    <input 
      id="nome-usuario"
      type="text"
      name="nome-usuario"
      placeholder="Informe o nome do usuário"
      value=""
      size="50"
      required
      >
      <button>Enviar</button>
  </form>
```

Saída: 
http://127.0.0.1:5500/html/formularios/1_campo_de_texto.html?nome-usuario=Grazielle+Amanda+do+Carmo+Caf%C3%A9#

### 7. Campo de Seleção 
```js
<html>
<form action="#">
  <label for="dia-da-semana">Dia da Semana</label>
  <select name="dia-semana" id="dia-semana">
    <option value="1">Domingo</option>
    <option value="2">Segunda-Feira</option>
    <option value="3">Terça-Feira</option>
    <option value="4">Quarta-Feira</option>
    <option value="5">Quinta-Feira</option>
    <option value="6">Sexta-Feira</option>
    <option value="7">Sábado</option>
  </select>
  <button>Enviar</button>
</form>
</html>
```

## CSS 
### 1. Seletores CSS
![Estrutura HTML](./assets/imgs/seletores_css.png)

O HTML é estrutura, enquanto o CSS é estilização para dentro da sua aplicação. 

**CSS**: Folha de Estilo em Cascada

Iremos utilizar as tags para aplicar estilos em suas tags. Como utilizaremos os seletores para realizar a estilização. 

### Modelo Caixa 
![Modelo Caixa](./assets/imgs/modelo-caixa.png)

### Tipos de Display
#### 1. Display Inline
Os elementos não consideram a altura e a largura, mantendo os elementos lado a lado.

![Display Inline](./assets/imgs/display-inline.png)

#### 2. Display Block
Somente o trecho é utilizado. Altura e Larguras são consideradas. 

![Display Block](./assets/imgs/display-block.png)

#### 3. Display inline-block
Usa apenas o tamanho necessário a ser ocupado. 

![Display inline-block](./assets/imgs/display-inline-block.png)

#### 4. Flexbox 
A partir do momento que você define a sua **div** com **display: flex** a caixa que está inserida nessa div será um **flex container**. 

O **Flexbox** (Flexible Box Layout) é um modelo de layout no CSS que permite a distribuição eficiente do espaço entre os itens de um contêiner, mesmo quando suas dimensões são desconhecidas ou dinâmicas. É especialmente útil para criar layouts responsivos e adaptáveis.

![](./assets/imgs/flexbox-container.png)

#### Eixos no Flexbox
No Flexbox, há dois eixos principais:

**Main Axis (Eixo Principal)**: É o eixo ao longo do qual os itens flexíveis são dispostos. Por padrão, o eixo principal é horizontal (da esquerda para a direita), mas pode ser alterado para vertical se o flex-direction for definido como column.

**Cross Axis (Eixo Transversal)**: É o eixo que é perpendicular ao eixo principal. Se o eixo principal é horizontal, o eixo transversal será vertical, e vice-versa.

#### Modos do Flexbox 
```js
justify-content: start;
```

![justify-content: start](./assets/imgs/justify-content-start.png)

```js
justify-content: end;
```

![justify-content: end](./assets/imgs/justify-content-end.png)

```js
justify-content: center;
```

![justify-content: end](./assets/imgs/justify-content-center.png)

```js
justify-content: space-between;
```

![justify-content: end](./assets/imgs/justify-content-space-between.png)

```js
justify-content: space-around;
```

![justify-content: end](./assets/imgs/justify-content-space-around.png)

```js
flex-direction: column; 
justify-content: start;
```

![justify-content: end](./assets/imgs/flex-direction-column.png)

```js
flex-direction: column; 
justify-content: space-around;
```

![justify-content: end](./assets/imgs/flex-direction-column-2.png)

```js
align-items: start; 
```

![justify-content: end](./assets/imgs/flexbox-align-items.png)

```js
align-items: end; 
```

![justify-content: end](./assets/imgs/flexbox-align-items-end.png)

```js
align-items: stretch; 
```

![justify-content: end](./assets/imgs/flexbox-align-items-stretch.png)

**Exemplo 1**
![exemplo flexbox](./assets/imgs/flexbox-exemplo.png)

```js
align-items: center; 
justify-content: space-between; 
```

**Exemplo 2**
![exemplo flexbox](./assets/imgs/flexbox-exemplo-2.png)

```js
display: flex;
align-items: center; 
justify-content: center; 
gap: 10px; 
```
<!-- gap: espaço entre os elementos >