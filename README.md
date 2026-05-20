# FINANÇAS ON — Site Oficial

Site institucional do **FINANÇAS ON**, pronto para publicação no GitHub Pages.

## Arquivos incluídos

- `index.html` — página principal completa, em arquivo único, com imagens embutidas.
- `README.md` — instruções de publicação.
- `.nojekyll` — evita processamento do GitHub Pages/Jekyll.
- `404.html` — página simples de erro com link para voltar ao início.
- `robots.txt` e `sitemap.xml` — arquivos básicos para indexação.

## Como publicar no GitHub Pages

1. Crie ou abra o repositório `FinancasON/financas-on`.
2. Garanta que o repositório tenha uma branch `main`. Se o GitHub não deixar enviar arquivos, recrie o repositório marcando **Add a README file**.
3. Envie todos os arquivos deste pacote para a raiz do repositório.
4. Acesse **Settings → Pages**.
5. Em **Source**, selecione **Deploy from a branch**.
6. Em **Branch**, selecione `main` e pasta `/ (root)`.
7. Clique em **Save**.
8. Aguarde alguns minutos e acesse:

```text
https://financason.github.io/financas-on/
```

## Atualizar botão de download

No `index.html`, procure pelos botões com `href="#"`, principalmente na área `id="download"`, e troque pelo link real do instalador do FINANÇAS ON.

Exemplo:

```html
<a href="https://seu-link-do-instalador.exe" class="dl-btn dl-btn-win">
```

## Segurança

Não coloque neste repositório público:

- tokens;
- senhas;
- client secret Google;
- chaves Mercado Pago;
- dados do Supabase;
- JSONs administrativos;
- links privados do Google Drive.

**Versão do site:** complementada para GitHub Pages  
**App:** FINANÇAS ON v2.0.3  
**Criador:** Alexsandro N. de Santana
