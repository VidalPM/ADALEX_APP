# ADALEX Digital — v2.0

Aplicativo web (PWA) da **Igreja Evangélica Assembleia de Deus - Alexandra**, pronto para publicação no **GitHub Pages**.

## Arquivos incluídos

| Arquivo | Finalidade | 
| ----- | ----- | 
| `index.html` | Página principal do aplicativo, já configurada com `./logo.png` como logo padrão. | 
| `logo.png` | Logotipo oficial exibido no cabeçalho do aplicativo e salvo em cache offline. | 
| `sw.js` | Service Worker extraído do aplicativo para habilitar cache offline e instalação como PWA em HTTPS. | 
| `.nojekyll` | Desativa o processamento Jekyll no GitHub Pages para garantir entrega direta dos arquivos estáticos. | 
| `README.md` | Documentação e passo a passo de publicação. | 

## Como publicar no GitHub Pages

1. **Crie um repositório no GitHub** (ex.: `adalex-digital`), marcado como **Public**.

2. **Envie todos os arquivos** (`index.html`, `logo.png`, `sw.js`, `.nojekyll` e `README.md`) para a raiz do repositório (`main`).

3. No repositório, acesse **Settings → Pages**.

4. Em **Build and deployment → Source**, selecione **Deploy from a branch**.

5. Em **Branch**, escolha `main` e a pasta `/ (root)`, depois clique em **Save**.

6. Aguarde cerca de 1 a 2 minutos e acesse o link gerado em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

## Atualizando personalizações no futuro

Sempre que você personalizar cores, textos, departamentos ou cadastros pelo **Painel Gestor** dentro do app:

1. Acesse a aba **Backup & Publicar**.

2. Clique em **Baixar index.html personalizado (pronto p/ GitHub)**.

3. Substitua o `index.html` no seu repositório do GitHub pelo novo arquivo baixado.