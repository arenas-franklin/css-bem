# Modulo 2 Acereladev React
----


## Atomic Design 
metodo de componização mais profunda, utiliza modelo atomico como se foosse um atomo

**Átomos:** São os elementos mais simples: button, input, slider, text etc..

**Molécula:** A molécula é a junção de **dois ou mais atómos,** e tem uma interação entre eles, gerando uma **interdependência,** onde  um influencia no outro.

**Organismos:** O organismo é um **conjunto de atómos e moléculas** que giram em torno de um **obketivo,** nem todos estão diretamente interligados, mas estão unidos por um **contexto.**

**Templates:** O templates é uma esboço para a página, ele define o local onde os componentes serão inseridos.

**Páginas:** A páginas é o **produto final,** todos os componentes serão incluídas nela, respeitando o objetivo final da página.

----

## CSS Modular com BEM

Organizar CSS é trabalhoso e gera muitos problemas no futuro

BEM é a sigla de Block Element Modifier que, em português, significa Bloco Elemeno Modificado.

Forma estrturada de nomear classes, baseado-se nas propriedades do elemento em questão.

**BLOCO:** O bloco é o recipiente ou **conexto  em que o elemento se encotra.** Imagine isso sendo as grandes partes estrturais do seu códigos.

**ELEMENT:** O element é **parte do bloco.** Cada elemento é escrito após o nome do bloco, **conectado por dois traços sublinhados.**

*.block__element { }*
*.header__logo { }*
*.header__tagline { }*
*.header__searchbar { }*
*.header__navigation { }*

**MODIFIER:** Não precisar escrever novas classes em outras áreas do site se os estilos dos elementos são os mesmos. Quandos precisar modificar o estilode um elemento especifico, você pode usar um modificador. Adicionar um hífen duplo -- após o elemento (ou bloco)

*.block--modifier { }*
*.block__element--modifier { }*

*header__navigation { }*
*header__navigation--secondary { }*
