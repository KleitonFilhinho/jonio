# Site do Jonio

Site estático oficial do aplicativo Jonio, pronto para publicação no GitHub Pages em `https://jonio.com.br`.

## Adicionar o logotipo

Crie a pasta `assets` na raiz do projeto e coloque nela o arquivo `logo.png`. O caminho final deve ser:

```text
assets/logo.png
```

Enquanto o arquivo não existir, o site mostra um monograma “J” como alternativa visual.

## Publicar no GitHub Pages

1. Envie estes arquivos para a branch `main` do repositório no GitHub.
2. No repositório, acesse **Settings → Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch `main`, a pasta `/ (root)` e clique em **Save**.
5. Em **Custom domain**, informe `jonio.com.br` e salve.
6. Depois que o certificado estiver disponível, ative **Enforce HTTPS**.

O arquivo `CNAME` já contém o domínio personalizado e o arquivo `.nojekyll` garante a publicação direta dos arquivos estáticos.

## Configurar o DNS

No provedor do domínio, configure os registros DNS recomendados pelo GitHub para um domínio raiz (`jonio.com.br`). Consulte a documentação atual do GitHub Pages antes de alterar os registros. A propagação pode levar algum tempo.

## Páginas

- Página inicial: `https://jonio.com.br`
- Política de Privacidade: `https://jonio.com.br/privacy.html`
- Suporte: `https://jonio.com.br/support.html`

Não há processo de compilação nem dependências: basta publicar os arquivos.

