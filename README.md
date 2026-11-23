# Bom Frete — site pronto pra GitHub Pages

Neste pacote:

- **`index.html`** → o **site dos motoristas**, agora como página principal:
  https://SEU-USUARIO.github.io/nome-do-repo/ abre direto ele
- **`cliente.html`** → o site do cliente (opcional de subir): …/cliente.html
  Os botões "🚛 Sou motorista" dele já apontam pra `index.html`
- **`.nojekyll`** → arquivo vazio que evita aviso do GitHub

O `index.html` funciona sozinho: o botão "Sou cliente" da barra de navegação
abre o WhatsApp com mensagem pronta, sem depender do outro arquivo.

## Como colocar no ar (5 minutos, grátis)

1. github.com → **+ → New repository** → nome (ex.: `bom-frete`) → público → criar
2. Dentro do repositório: **Add file → Upload files** → arraste
   `index.html`, `cliente.html`, `.nojekyll` (se não quiser subir o site do
   cliente, mande só `index.html` e `.nojekyll` que nada quebra)
3. **Commit changes**
4. **Settings → Pages** → **Deploy from a branch** → `main` / `/ (root)` → Save
5. ~1 minuto depois: **https://SEU-USUARIO.github.io/bom-frete/**
   (se o seu repositório já existe com esse nome, o endereço que já existe é
   quem vale — só sobem os arquivos e commitam)

## Detalhes

- Todo o conteúdo (fotos, logo, CSS, JavaScript) está embutido nos próprios
  arquivos — não precisa subir mais nada
- WhatsApp: **(31) 99698-6542** (`wa.me/5531996986542`). Trocou de número?
  Procure `5531996986542` nos arquivos e troque por tudo
- Rodapé diz "Site fictício de demonstração" — apague a frase dentro dos
  arquivos se quiser tirar
- Domínio próprio (bomfrete.com.br)? Depois, em **Settings → Pages → Custom domain**
