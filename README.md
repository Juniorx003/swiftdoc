# SwiftDoc Studio Pro (SD)

Aplicativo web completo (Triple-Engine: Documentos PDF, Foto & Vídeo/Motion) pronto para hospedagem gratuita no **GitHub Pages**.

## Como publicar no GitHub Pages (Passo a Passo Rápido)

### Passo 1: Criar o repositório no GitHub
1. Acesse [github.com/new](https://github.com/new) conectado à sua conta.
2. Em **Repository name**, digite um nome simples, por exemplo: `swiftdoc` (ou `swiftdoc-pro`).
3. Deixe marcado como **Public** (Público — necessário para o GitHub Pages gratuito).
4. Clique no botão verde **Create repository**.

### Passo 2: Enviar os arquivos
1. Na tela do repositório recém-criado, clique no link **uploading an existing file** (ou em **Add file** > **Upload files**).
2. Arraste o arquivo **`index.html`** (e opcionalmente o `.nojekyll` e `README.md`) para a área de upload.
   - *Importante:* O arquivo principal deve se chamar exatamente **`index.html`** na raiz do repositório.
3. Lá embaixo, clique no botão verde **Commit changes**.

### Passo 3: Ativar o site no GitHub Pages
1. No menu superior do seu repositório, clique em **Settings** (Configurações ⚙️).
2. No menu lateral esquerdo, clique em **Pages**.
3. Em **Build and deployment** > **Branch**, troque de `None` para **`main`** (ou `master`), mantenha a pasta **`/ (root)`** e clique em **Save**.
4. Aguarde cerca de **1 a 2 minutos** e atualize a página. O GitHub mostrará o link oficial do seu aplicativo no topo:
   - `https://SEU-USUARIO.github.io/swiftdoc/`

---
### Estrutura deste pacote
- `index.html`: Aplicativo completo SwiftDoc Studio Pro com ícone `SD` em Azul Royal e motores de PDF, Imagem e Vídeo integrados.
- `.nojekyll`: Desativa o processamento Jekyll do GitHub para publicação instantânea.
- `.github/workflows/deploy.yml`: Fluxo opcional de publicação automática via GitHub Actions.
