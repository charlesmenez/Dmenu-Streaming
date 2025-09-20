<h1 align="center">Dmenu-Streaming</h1>
<p align="center">Um script minimalista que integra <b>dmenu</b>, <b>webtorrent-cli</b> e <b>mpv</b> para streaming direto via terminal.</p>
<p align="center">Fork de <a href="https://github.com/Bugswriter/notflix">Notflix</a></p>

---

## 🎯 O que é

O **Dmenu-Streaming** é um script em shell voltado a quem prefere ambientes **minimalistas** e fluxos de trabalho **orientados ao teclado** — ideal para usuários de *tiling window managers* (i3, dwm, bspwm, etc.).

Com ele, você pode pesquisar títulos diretamente no `dmenu`, escolher uma opção e decidir entre:

* **Assistir imediatamente** no **mpv player** via `webtorrent-cli`.
* **Adicionar para download** no Transmission.

---

## ⚡ Como funciona

1. Digite o nome do título no prompt do `dmenu`.
2. Veja os resultados e escolha a versão desejada.
3. O script obtém o *magnet link*.
4. Escolha entre:

   * **Assistir** → streaming instantâneo no `mpv`.
   * **Baixar** → adiciona o torrent ao Transmission em segundo plano.

👉 Tudo isso sem sair do teclado, com a simplicidade do `dmenu`.

---

## 🔧 Dependências

* [dmenu](https://tools.suckless.org/dmenu/) – Menu minimalista para X.
* [webtorrent-cli](https://github.com/webtorrent/webtorrent-cli) – Streaming de torrents no terminal.
* [mpv](https://mpv.io) – Player de vídeo.
* [transmission](https://transmissionbt.com/) (opcional) – Cliente para downloads.

Instale o `webtorrent-cli` com:

```sh
npm install -g webtorrent-cli
```

---

## 📥 Instalação

Baixe o script para o seu **\$PATH** e torne-o executável:

```sh
sudo curl -sL "https://raw.githubusercontent.com/charlesmenez/Dmenu-Streaming/master/Dmenu-Streaming" -o /usr/local/bin/Dmenu-Streaming
sudo chmod +x /usr/local/bin/Dmenu-Streaming
```

* Para **atualizar**, repita o comando `curl` (não é necessário `chmod` novamente).
* Para **remover**, basta excluir o script:

```sh
sudo rm -f /usr/local/bin/Dmenu-Streaming
```

---

## ⚠️ Observação legal

Este projeto tem caráter educacional e demonstra como integrar ferramentas de linha de comando de forma minimalista.
**Use apenas com conteúdos que você tem direito de acessar** (ex.: filmes de domínio público, arquivos pessoais ou material com licença aberta).

---

## 📖 Licença

Este projeto está licenciado sob [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).
