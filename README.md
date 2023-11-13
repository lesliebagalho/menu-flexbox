# menu-flexbox
Menu flexbox definitivo <br>
[x] Criar estrutura do HTML <br>
'<nav>
    <a href="#" class="logo">leslieb<span>-dev</span></a>

    <ul>
        <li>sobre</li>
        <li>serviços</li>
        <li>depoimentos</li>
    </ul>
    <!-- ul -->

    <a href="#" class="button">contato</a>
'</nav>
<!-- nav -->

<br><br>
[x] Criar a estrura do CSS <br>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root{
    font-size: 62.5%;
    --nav-bg-color: blue;
    --nav-text-color: white;
    --button-bg-color: yellow;
    --button-text-color: black;
}

body{
    font-size: 1.6rem;
    font-family: 'Roboto', sans-serif;
}

a{
    text-decoration: none;
}

nav{
    background: var(--nav-bg-color);
    color: var(--nav-text-color);
    height: 6rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.5rem;
}

.logo{
    color: var(--nav-text-color);
    font-weight: 600;
}

.logo span{
    font-size: 2rem;
    font-weight: 600;
    color: var(--button-text-color);
}

ul{
    display: flex;
    list-style: none;
    gap: 3rem;
}

.button{
    display: inline-flex;
    justify-content: center;
    align-items: center;
    padding: 1rem 1.6rem;
    background: var(--button-bg-color);
    color: var(--button-text-color);
    border-radius: 5em;
}