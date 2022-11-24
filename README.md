<h1 align="center">Dmenu-Streaming</h1>
<p align="center">f@#k netflix use Dmenu-Streaming a tool which search magnet links and stream it with peerflix</p>
<p align="center">Fork of <a href=https://github.com/Bugswriter/notflix>Notflix<a/></p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>


### How does this work?

This is a shell script using dmenu to search 1337x movies and get the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

### cURL
cURL **Dmenu-Streaming** to your **$PATH** and give execute permissions.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/charlesmenez/Dmenu-Streaming/master/Dmenu-Streaming" -o /usr/local/bin/notflix
$ sudo chmod +x /usr/local/bin/Dmenu-Streaming
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/Dmenu-Streaming.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

