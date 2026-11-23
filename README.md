# Pamebo Pinturas — GitHub Pages

Site estático, sem Node.js, instalação ou compilação.

1. Extraia este ZIP e envie TODOS os arquivos e a pasta images à raiz do repositório. O index.html precisa ficar na raiz, não dentro de uma subpasta.
2. No GitHub, abra Settings → Pages.
3. Em Build and deployment, selecione Deploy from a branch.
4. Selecione main e / (root), depois Save.
5. Aguarde a publicação e abra o endereço exibido pelo GitHub.

Os caminhos são relativos: funcionam tanto em usuario.github.io/repositorio/ quanto em domínio próprio. Nenhum domínio foi fixado neste pacote.

Edite index.html para alterar os textos, styles.css para a aparência e script.js para galeria e WhatsApp. As fotos estão em images/acervo. O formulário prepara a mensagem; o visitante confirma o envio no WhatsApp.

Para testar localmente, abra index.html no navegador. Opcionalmente execute python -m http.server 8000 nesta pasta.
