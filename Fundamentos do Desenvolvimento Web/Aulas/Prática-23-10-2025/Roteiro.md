# Aula básica de HTML

## Construindo Minha Primeira Página Web

### **Objetivo:** Aprender a usar as tags básicas de HTML para estruturar uma página simples.

### 💻 Preparação do Ambiente

1.  **Abra o Editor:** Abra seu editor de código de preferência (VS Code, Sublime Text, Bloco de Notas, etc.).
2.  **Crie o Arquivo:** Crie um novo arquivo e **salve-o** na sua área de trabalho ou em uma pasta de sua escolha com o nome: `meu_site.html`.
3.  **Abra no Navegador:** Dê um clique duplo no arquivo `meu_site.html`. Ele abrirá no seu navegador (Chrome, Firefox, Edge, etc.). Mantenha o editor e o navegador abertos lado a lado.

-----

### 📝 Passo 1: Estrutura Essencial

Digite o código abaixo no seu arquivo `meu_site.html`. Esta é a base de todo documento HTML.

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Meu Primeiro Site</title>
</head>
<body>
    </body>
</html>
```

  * **Ação:** Salve o arquivo no editor (`Ctrl + S` ou `Cmd + S`).
  * **Verificação:** Atualize a página no navegador (`F5` ou botão de recarregar). O título da aba deve mudar para "Meu Primeiro Site".

### ✒️ Passo 2: Conteúdo Principal (Títulos e Parágrafos)

Dentro da tag `<body>`, adicione os seguintes elementos para dar corpo à sua página.

1.  **Título Principal (`<h1>`):** Use o `<h1>` para o título mais importante da página.
2.  **Título Secundário (`<h2>`):** Para subtítulos.
3.  **Parágrafo (`<p>`):** Para blocos de texto.

<!-- end list -->

```html
<body>
    <h1>Bem-vindo à Minha Página Pessoal</h1>
    <h2>Sobre Mim</h2>
    <p>
        Olá! Esta é a minha primeira experiência prática com HTML. 
        Estou aprendendo a usar tags para estruturar o conteúdo de uma página web.
        A linguagem HTML é a base de tudo que vemos online!
    </p>
</body>
```

  * **Ação:** Salve o arquivo.
  * **Verificação:** Atualize o navegador. Observe a diferença na hierarquia e no tamanho dos títulos.

### 🔗 Passo 3: Listas e Links

Adicione mais conteúdo, como uma lista de itens e um link de navegação. Coloque este código logo abaixo do parágrafo que você acabou de criar.

1.  **Lista Não Ordenada (`<ul>` e `<li>`):** Crie uma lista de seus itens favoritos.

    ```html
    <h3>Meus Interesses</h3>
    <ul>
        <li>Tecnologia e Programação</li>
        <li>Livros (adicione um livro de sua preferência)</li>
        <li>Música</li>
    </ul>
    ```

2.  **Link (`<a>`):** O atributo `href` define o endereço de destino.

    ```html
    <p>
        Para saber mais sobre desenvolvimento web,
        <a href="https://developer.mozilla.org/pt-BR/" target="_blank">clique aqui</a>.
    </p>
    ```

<!-- end list -->

  * **Ação:** Salve o arquivo.
  * **Verificação:** Atualize o navegador. Teste o link para garantir que ele abra o site em uma nova aba.

### 🖼️ Passo 4: Desafio Opcional (Imagens)

Se você tiver uma imagem (`.jpg`, `.png`) salva na **mesma pasta** do seu arquivo `meu_site.html`, tente adicioná-la à sua página.

  * **Tag:** Use a tag `<img>`. Ela não precisa de fechamento.
  * **Atributos:**
      * `src`: O caminho para o arquivo de imagem (ex: `"minha_foto.jpg"`).
      * `alt`: Texto alternativo (essencial para acessibilidade, descreve a imagem).

<!-- end list -->

```html
    <img src="nome_da_sua_imagem.jpg" alt="Descrição da imagem para acessibilidade" width="200">
```

### 💡 Revisão Final

1.  Revise seu código e confirme que todas as tags que você abriu foram fechadas (ex: `<ul>` e `</ul>`), exceto as tags `<img>` e `meta`.
2.  Visualize sua página final no navegador.

**Parabéns\! Você estruturou sua primeira página web usando os fundamentos do HTML.**