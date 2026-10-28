# Etiqueta

Formação de preço de venda para MEI, ME e EPP. Projeto da disciplina Extensão II.

O site tem dois arquivos, que precisam ficar juntos na mesma pasta:

| Arquivo | O que é |
| --- | --- |
| `index.html` | Página de apresentação do projeto (início, como funciona, funcionalidades, benefícios e botão de acesso) |
| `sistema.html` | O sistema de precificação Etiqueta |
| `.nojekyll` | Arquivo vazio que diz ao GitHub Pages para publicar os arquivos como estão |

Não há servidor, banco de dados nem instalação. Cada arquivo é HTML puro, com o CSS e o JavaScript dentro dele. Os dados que cada pessoa digita no sistema ficam guardados só no navegador dela.

## Publicar no GitHub Pages (gratuito, com HTTPS)

1. Entre em github.com e crie uma conta, se ainda não tiver.
2. Clique em **New repository**. Nome: `etiqueta`. Marque **Public**. Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file**, arraste `index.html`, `sistema.html` e `.nojekyll`, e clique em **Commit changes**.
4. Vá em **Settings** e depois em **Pages**. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
5. Espere de 1 a 2 minutos e recarregue a página de Settings > Pages. O endereço aparece no topo:
   `https://SEU-USUARIO.github.io/etiqueta/`

O sistema fica em `https://SEU-USUARIO.github.io/etiqueta/sistema.html`, e o botão da apresentação já aponta para ele.

O HTTPS vem ligado por padrão em endereços `github.io` (opção **Enforce HTTPS** em Settings > Pages).

## Conferir se qualquer pessoa consegue abrir

Abra o link numa janela anônima (Chrome: Ctrl+Shift+N; Safari: Arquivo > Nova janela privada) ou no celular de alguém que não tem a sua conta. A página precisa abrir sem pedir login. Se pedir, o repositório não está público: Settings > General > Danger Zone > Change visibility > Public.

## Atualizar o site depois

Pelo navegador, sem instalar nada:

1. Abra o repositório no GitHub.
2. Clique em **Add file** > **Upload files** e arraste o arquivo novo **com o mesmo nome** (`index.html` ou `sistema.html`). Ele substitui o antigo.
3. Escreva uma frase dizendo o que mudou e clique em **Commit changes**.
4. Em 1 a 2 minutos o site publicado já mostra a versão nova. Se o navegador mostrar a antiga, recarregue a página (no celular, feche e abra a aba).

Para uma correção pequena de texto, dá para editar direto: clique no arquivo, no ícone de lápis (**Edit this file**), altere e clique em **Commit changes**.

O histórico fica guardado: em **Commits** dá para ver e recuperar qualquer versão anterior.

## Cuidados

- Mantenha os nomes `index.html` e `sistema.html`. Os botões dependem deles.
- Atualizar o site não apaga os dados de quem já usa o sistema, porque eles ficam no navegador de cada pessoa. Mudar o endereço do site (por exemplo, renomear o repositório) faz cada pessoa começar do zero naquele navegador; para levar os dados, use Ajustes > Baixar backup no endereço antigo e Restaurar no novo.
- Repositório público significa que o código e o rodapé (com nomes e matrículas da equipe) ficam visíveis para qualquer pessoa.
