<h1>Projeto Apeperia</h1>
<h4>Layouts Responsivo: Trabalhando com layouts mobile</h4>
Este projeto faz parte de um módulo do curso Alura Online
Módulo sobre design responsivo.

<h3>Aula 1: Aprendendo sobre Emmet</h3>

O Emmet consiste em escrever os códigos html de forma mais ágil.

exemplo:

digitando estes cógigos
>header>img+nav>ul>li*6>a

o resultado será este
```
 <header>
        <img src="" alt="">
        <nav>
            <ul>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
                <li><a href=""></a></li>
            </ul>
        </nav>
    </header>
```

**O sinal de ">"** (maior que) demonstra a hierarquia da tag, por exemplo:
>header>div3

significa que a div estará dentro da tag header

**O sinal "+"** (adição) siginifica que a tag fará parte do mesmo nível hierárquico que a tag anterior, por exemplo:
>div>h1+p

significa que dentro da tag DIV teremos um título e um parágrafo.

**O sinal de "*"** (multiplição === asterisco) significa o as tags serão multiplicadas.
>ul>li*2
```
<ul>
    <li></li>
    <li></li>
</ul>

```
**ctrl + space** = caso não o emmet não funcione após você escrever o código.