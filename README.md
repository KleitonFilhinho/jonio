# Site do Jonio

Site estÃ¡tico oficial do aplicativo Jonio, pronto para publicaÃ§Ã£o no GitHub Pages em `https://jonio.com.br`.

## Adicionar o logotipo

Crie a pasta `assets` na raiz do projeto e coloque nela o arquivo `logo.png`. O caminho final deve ser:

```text
assets/logo.png
```

Enquanto o arquivo nÃ£o existir, o site mostra um monograma â€œJâ€ como alternativa visual.

## Publicar no GitHub Pages

1. Envie estes arquivos para a branch `main` do repositÃ³rio no GitHub.
2. No repositÃ³rio, acesse **Settings â†’ Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch `main`, a pasta `/ (root)` e clique em **Save**.
5. Em **Custom domain**, informe `jonio.com.br` e salve.
6. Depois que o certificado estiver disponÃ­vel, ative **Enforce HTTPS**.

O arquivo `CNAME` jÃ¡ contÃ©m o domÃ­nio personalizado e o arquivo `.nojekyll` garante a publicaÃ§Ã£o direta dos arquivos estÃ¡ticos.

## Configurar o DNS

No provedor do domÃ­nio, configure os registros DNS recomendados pelo GitHub para um domÃ­nio raiz (`jonio.com.br`). Consulte a documentaÃ§Ã£o atual do GitHub Pages antes de alterar os registros. A propagaÃ§Ã£o pode levar algum tempo.

## PÃ¡ginas

- PÃ¡gina inicial: `https://jonio.com.br`
- PolÃ­tica de Privacidade: `https://jonio.com.br/privacy.html`
- Suporte: `https://jonio.com.br/support.html`

NÃ£o hÃ¡ processo de compilaÃ§Ã£o nem dependÃªncias: basta publicar os arquivos.

