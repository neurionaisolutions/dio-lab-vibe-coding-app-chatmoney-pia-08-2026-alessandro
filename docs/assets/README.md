# docs/assets — imagens e assets do projeto

Esta pasta contém placeholders e instruções para armazenar imagens, GIFs e outros ativos usados no README e na documentação do projeto.

Como usar
- Nomeie arquivos de forma clara: `screenshot-chat-01.png`, `gif-demo-conversa.gif`.
- Preferência por PNG para screenshots e GIF/WebM para animações curtas.
- Tamanho recomendado: width até 1280px para screenshots; otimize com ferramentas como `pngquant` ou `gifsicle`.

Adicionando assets
1. Faça upload dos arquivos para `docs/assets/` no repositório.
2. No README, atualize as tags `<img>` para usar caminhos relativos, por exemplo:
   `<img src="docs/assets/screenshot-chat-01.png" alt="Conversa com o Piá" />`
3. Mantenha os arquivos com nomes descritivos e registre no PR quais arquivos foram adicionados.

Observação: atualmente o README referencia imagens hospedadas externamente; quando os arquivos locais estiverem prontos, substitua os URLs externos pelos caminhos relativos acima.
