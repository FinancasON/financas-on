# FINANÇAS ON — Site Oficial

Site institucional do **FINANÇAS ON**, pronto para GitHub Pages.

## Como publicar no GitHub Pages

1. Envie todos os arquivos deste pacote para a raiz do repositório.
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)`.
5. Clique em **Save**.
6. Aguarde alguns minutos e abra o link publicado pelo GitHub Pages.

## Como colocar os links de download

No arquivo `index.html`, procure pelo bloco abaixo, logo depois da abertura do `<body>`:

```html
<!-- LINKS DE DOWNLOAD -->
<script>
  window.DOWNLOAD_LINKS = {
    windows: "#",
    android: "#"
  };
</script>
```

Troque apenas o `#` pelo link real:

```html
window.DOWNLOAD_LINKS = {
  windows: "https://seu-link-do-instalador-windows.exe",
  android: "https://seu-link-do-aplicativo-android.apk"
};
```

- `windows`: link do instalador `.exe`, `.msi` ou página de download do Windows.
- `android`: link do APK ou da página na Play Store.

Enquanto o link estiver como `#`, o botão fica sem ação e aparece como link em breve.

## Conteúdo do site

- Hero com logo e botões de download.
- Seção “Como funciona”.
- Privacidade e segurança.
- Funcionalidades do app.
- Screenshots.
- Área de download separada para Windows e Android.
- FAQ.
- Suporte.
- Footer com links principais.

**Versão:** 2.0.3  
**Criador:** Alexsandro N. de Santana
