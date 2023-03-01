# **links-page**

Uma página de Links Criada com HTML e CSS (Semelhante ao Linktree)

## **Objetivo do Portifólio**

Colocar em prática em um projeto simples a estrutura do Pré-Processador Sass.

## **O que é o Sass?**

O Sass é um pré-processador CSS feito em Ruby. Sua função é mais como uma ferramenta para o desenvolvedor do que um Framework com alterações visuais no projeto. Ele adciona funcionalidades para o CSS como:

- Variáveis
- Mixins
- Imports
- Nesting
- Operações Matemática
- Entre outros...

Essas funcionalidades trazem beneficios como: Estilizações de fácil leitura e entendimento, Estruturação do Código CSS, Diminuição de Estilizações repetitivas, etc...

O Compilador do SASS converte arquivos ".scss" e ".sass" para css puro. Os dois tipos de arquivos são utilizados pelo SASS e possuem as mesmas finalidades, a diferença está em seus estilos, enquanto no ".sass" o código é identado e sem chaves (com estrutura semelhante ao python), os arquivos ".scss" não nescessitam obrigatoriamente de identação e utilizam chaves para organizar o Nesting.

> Arquivo ".sass"

```scss
.myinfos
  height: 45%
  display: flex
  gap: 10px 20px
  padding-right: 10px
  flex-direction: column

  .headsection
    font-family: "Chakra Petch", sans-serif
    display: flex
    height: 70%
    align-items: center
```

> Arquivo ".scss"

```scss
.myinfos {
  height: 45%;
  display: flex;
  gap: 10px 20px;
  padding-right: 10px;
  flex-direction: column;

  .headsection {
    font-family: "Chakra Petch", sans-serif;
    display: flex;
    height: 70%;
    align-items: center;
  }
}
```

## **Diferença entre .SASS e .SCSS**

Ambas as extensões são processadas pelo compilador Sass e possuem a mesma função. O ".sass" era originalmente a utilizada pelo pré-processador, porém o Sass se inspirou na linguagem de estilo "Less" (que por sua vez, teve sua criação inspirada no próprio SASS) e adotou a syntax do ".scss". A escolha de qual tipo vai de cada desenvolvedor, particularmente é sempre recomendável utilizar o ".scss" já que sua syntax é muito parecida com a do CSS, se você colar um código "CSS" em um arquivo ".sass", você terá erros de compilação, diferente do ".scss"

### Saiba mais em https://sass-lang.com/
