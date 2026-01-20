# cursophp

# Introdução Geral

* Diferença entre pensamento de perto vs de longe.
* O poder do interrogatório elaborado.
* Repetição é rei, prática é deus.
* Não se testa na mente, se testa na prática.
* Pra aprender, precisamos dormir.

## Como funciona um site

#### Domínio e Subdomínio
* Registro br
* Hostgator
* Hostinger
* Locaweb
* Umbler
* UOL Host
* GoDaddy
* Cloudflare

## Como um Servidor Funciona

### Tipos de servidores web

* Apache - php
* * O Apache é o principal candidato dos servidores atuais
* ISS (Internet Information Servicer)
* Tomcat - javaweb
* JBoss - javaweb

## Como o PHP funciona

* O PHP é um software instalado no servidor.
* Interpretado pelo Apache
<img width="280" height="229" alt="image" src="https://github.com/user-attachments/assets/8faa8a2d-248c-44ea-a09e-5dea350aceba" />

## Página Estática vs Dinâmica

<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/c339689b-3da6-4486-9a05-58de9e34f793" />
<br>
<img width="262" height="190" alt="image" src="https://github.com/user-attachments/assets/b5e57bd4-b188-4bfa-a4ce-c20b7d3a5518" />

## Editores de Código

* MyCompiler - web
* SublimeText 2
* Visual Studio Code
* Atom
* Notepad2
* Notepad++
* Brackets
* Bluefish
* Vim
* NetBeans
* GNU Emacs
* UltraEdit
* CoffeeCup HTML Editor
* TextMate
* Codeshare.io
* Spacemacs
* BBBEdit
* WebStorm
* Espresso
* Nova
* Dreamweaver

# HTML e CSS

## O que é html?

O HTML (HyperText Markup Language) é uma linguagem de marcação utilizada para estruturar e organizar o conteúdo de páginas web. Diferente de linguagens de programação, o HTML não cria algoritmos ou manipula dados, mas define a estrutura de elementos como textos, imagens, links, tabelas e formulários que compõem uma página.

Ele funciona através de tags, que são interpretadas pelos navegadores para exibir os elementos na tela. Por exemplo, a tag <p> é usada para criar parágrafos, enquanto <img> insere imagens. Um arquivo HTML é salvo com a extensão .html e pode ser aberto diretamente em navegadores.

## Onde salvar e como abrir arquivos?

🔹 “Onde salvar”: refere-se ao local em que os arquivos do código devem ser armazenados. Em cursos de programação, isso geralmente envolve explicar a estrutura de pastas, como salvar scripts PHP em diretórios corretos (por exemplo, dentro da pasta do servidor local como htdocs no XAMPP ou www no WAMP).

🔹 “Como abrir”: trata da forma de executar ou visualizar esses arquivos. No caso do PHP, não basta abrir o arquivo diretamente no navegador; é preciso rodar em um servidor local (como Apache) e acessar via http://localhost/nomedoarquivo.php.

## Estrutura de uma Página Web
### O que o conteúdo da página aborda
🔹 <b>HTML</b> como base: a aula mostra que toda página web começa com um documento HTML, que define a estrutura e os elementos principais.

🔹 <b>Cabeçalho (head):</b> parte onde ficam informações que não aparecem diretamente para o usuário, como título da aba, metadados, links para arquivos CSS e scripts.

🔹 <b>Corpo (body):</b> área visível da página, onde são colocados textos, imagens, links, botões e outros elementos que o usuário interage.

🔹 Tags fundamentais: explicação sobre <html>, <head>, <title>, <body> e como elas se relacionam para formar a base de qualquer página.

🔹 Organização lógica: a aula enfatiza que entender essa estrutura é essencial para evoluir no desenvolvimento web, pois é a partir dela que se adicionam estilos (CSS) e comportamentos (JavaScript).

# Cabeçalho
<pre>
    <head>
        <title>Titulo da sua página</title>
        <link rel="stylesheet" href="">
        <script></script>
        <style></style>
        <meta>
        <base href="" />
    </head>
</pre>

<img width="309" height="163" alt="download" src="https://github.com/user-attachments/assets/c7380f8c-1baf-4de7-87f9-00b7a4e08cc8" />

# Formatações de texto

<pre>
    <html>
    <header><script type="text/javascript" src="/___vscode_livepreview_injected_script"></script>
        <title>Titulo da sua página</title>
    </header>
    <body>
        Esté é um <b>negrito</b><br>
        Esé um <strong>negrito</strong>
        que assim vai soar <br><br>
        <sub></sub>
        <u></u>
        <sup></sup>
        <strike></strike>
    </body>
    <div>
        Este é um <strong>peema</strong><br><br>
        que <i>assim</i> vai soar. <br><br>

        Se <u>eu</u> <sup>2</sup> <strike>queser</strike>
        fazer <br>
        ele vai <small>ficar</small>
    </div>
</html>
</pre>

# Listas não ordenadas
<pre>
    <html>
        <head>
            <title>Titulo da sua página</title>
        </head>
        <body>
            Ingredientes do nosso bolo:
            <ul style="list-style-type:circle, square, none">
                <li>Trigo</li>
                <li>Água</li>
                <li>Sal</li>
                <li>Fermento</li>
                <li>Corante</li>
                <li>Massa</li>
            </ul>
        </body>
    </html>
</pre>

# listas ordenadas

<pre>
    <html>
        <head>
            <title>Página de teste</title>
        </head>
        <body>
            <ol type="1, A, a, I, i">
                <li>Jogar a massa</li>
                <li>Mexer</li>
                <li>Esperar</li>
                <li>Comer</li>
            </ol>
        </body>
    </html>
</pre>

# Imagens

<pre>
    <html>
        <head>
            <title>Página de teste</title>
        </head>
        <body>
            <img src="../" alt="">
            <img src="http://www.google.com.br/google.jpg" width="200" height="" alt="Google" title="Este é um titulo" />
        </body>
    </html>
</pre>

# Links

<pre>
    <html>
        <head>
            <title>Página de Teste</title>
        </head>
        <body>
            <a href="www.google.com" target="_blank">Abrir Google</a>
            <a href="pagina.html">Clique aqui para abrir essa página</a>
            <a href="documento.pdf" download>Baixar Documento</a>
        </body>
    </html>
</pre>
