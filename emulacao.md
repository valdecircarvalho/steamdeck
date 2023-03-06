# Emulação no Steam Deck

O Steam Deck é o paraiso dos emuladores. Ele pode em teoria emular qualquer coisa, desde o antigo Atari 2600 até o Xbox 360 e Playstation 3 sem grandes problemas.

Existem diversas maneiras de rodar emuladores no seu Steam Deck. 

+ Instalar cada emulador separadamente
+ Usar o EmuDeck ou outras ferramentas como RetroDeck ou Batocera


## O Guia do idiota para Emudeck
Estou usando o Emudeck como base para este guia, embora existam outras ferramentas como RetroDeck e Batocera. 
As dicas sobre BIOS e ROMs serão basicamente as mesmas, mas podem variar.

O vídeo e o guia de instalação feito pelo Russ do blog Retro Game Corp no site da Emudeck irá guiá-lo através da instalação do Emudeck 2.0.

[Este outro guia](https://wagnerstechtalk.com/sd-emudeck/) escrito por Wagnerstechtalk também é incrivelmente útil

### Quais emuladores eu quero?!

+ **RetroArch** vai emular Atari, NES, SNES, DS, N64, Sega Genesis, Neo Geo, Saturn, Dreamcast, GB, GBA, GBC e muitos outros

+ **Dolphin** é o emulador padrão para Nintendo GameCube e Nintendo Wii

+ **Prime Hacks** é um fork do Dolphin para Metroid Prime Wii Trilogy

+ **PPSSPP** é o emulador para Sony PSP

+ Duckstation é o emulador para Sony Playstation 1/PS1

+ Citra é o emulador para Nintendo 3DS

+ MelonDS é o emulador para Nintendo DS

+ PCSX2 é o emulador para Sony Playstation 2/PS2

+ RPCS3 é o emulador para Sony Playstation 3/PS3

+ Yuzu e Ryujinx são ambos Nintendo Switch (não vou entrar nessa emulação)

+ Xemu é o emulador para OG Xbox

+ CEMU é o emulador para o Nintendo WII U

+ MAME é o emulador de fliperama

+ VITA3K é o emulador para Playstation Vita

+ SCUMMVM é o emulador para PC de jogos apontar e clicar (_point & click_) em aventuras como as antigas da LucasArts (Monkey Island, Full Throttle, Indiana Jones and the Fate of Atlantis)

### Onde encontro os arquivos do BIOS?!

E é aqui que todos os outros guias param devido a temores de “violação de direitos autorais”, dos quais BIOS e ROMs se enquadram diretamente. Mas não este guia porque somos todos adultos e sabemos sobre abandonware. Tem todos os links para você começar e todos eles estão no GitHub, archive.org, Vimm's Lair (site de ROM confiável) ou no site oficial do PlayStation.

Não vou entrar na emulação do Switch.

BIOS RetroArch completo ([link do GitHub](https://github.com/Abdess/retroarch_system) ou [link alternativo]() direto do meu site)

Arquivos de BIOS do XBox ([link archive.org](https://archive.org/details/xemustarter) ou [link alternativo]() direto do meu site))

Firmware PS3 ([site oficial da Sony](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) ou [link alternativo]() direto do meu site)) 

### Onde coloco os arquivos da BIOS?!

Esses sistemas comuns que requerem BIOS vão DIRETAMENTE na pasta BIOS:

+ PS1
+ PS2
+ Sega Saturn (Três núcleos RetroArch separados)
+ CD Sega
+ Sega Genesis
+ Nintendo DS
+ XBox (Não - RetroArch)
+ Dreamcast BIOS vai para a pasta 'dc' dentro da pasta BIOS
+ O firmware PS3 deve ser instalado via desktop RPCS3.

Esses sistemas comuns NÃO requerem arquivos de BIOS:

+ NES
+ SNES
+ N64
+ Game Cube
+ Wii
+ wii u
+ Game Boy
+ Game Boy Color
+ Game Boy Advance
+ Nintendo 3ds
+ PSP
+ Game Gear

Para todos os outros sistemas, consulte a documentação do Emudeck e RetroArch. [Informações do BIOS do Emudeck](https://github.com/dragoonDorise/EmuDeck/wiki/Cheat-Sheet)
[Informações do BIOS do RetroArch](https://docs.libretro.com/library/bios/)

### Como faço para verificar se tenho o arquivo BIOS correto no lugar certo?!

Você pode verificar usando o verificador de BIOS do Emudeck. Vá para o modo de área de trabalho, abra o Emudeck, Tools and Stuff, verifique o BIOS.

Isso verificará se o arquivo está no lugar correto e se possui o hash correto, mas ainda pode ter um nome incorreto (a capitalização é importante). Todos os arquivos do BIOS do RetroArch são nomeados corretamente, assim como os arquivos do BIOS do XBox, mas lembre-se de que, se o verificador do BIOS estiver verde, ele ainda pode ter sido nomeado incorretamente.

### Agora, onde consigo jogos (AKA ROMS)?!

Vou fornecer três links, alguns termos de pesquisa e um vídeo.

Duas coisas para manter em mente.

Às vezes, os arquivos baixados estão no formato .zip ou .7z, que é compactado. Alguns sistemas RetroArch podem reproduzir os arquivos condensados, mas a maioria dos sistemas não pode, então você terá que extrair os arquivos. No Steamdeck, clique com o botão esquerdo no arquivo e clique em Extrair.

A outra coisa é que os downloads do archive.org são extremamente lentos, a menos que você use um gerenciador de downloads. Na loja Discover, há um programa chamado Free Download Manager que funciona muito bem. Basta arrastar o arquivo de archive.org para o programa e ele acelerará consideravelmente o download.

1. https://myrient.erista.me/ 

1. Covil de Vimm (https://vimm.net/)

* Tem tudo até Wii e PSP

* Velocidades de download dolorosamente lentas (apenas uma de cada vez), mas seguras, confiáveis e incrivelmente intuitivas

* Downloads do XBox no formato .xiso que rodam automaticamente no Xemu (o emulador é instalado pelo Emudeck)

* Cada arquivo que você baixa vem como um arquivo compactado junto com um arquivo .txt do Vimm's Lair depois de extrair os arquivos. Você pode deletar isso.

2. Página Github 2.r-ROMs também conhecida como “o Megathread” (https://r-roms.github.io/)

* Para navegar para encontrar um jogo, use a barra de menu na parte superior (ou clique no botão de 3 linhas para expandir o menu)

* NÃO use a barra de pesquisa porque ela não encontrará todos os jogos, apenas alguns jogos populares.

* Depois de navegar para o sistema (por exemplo, Sony - Sony PlayStation - Internet Archive (Redump) (CHD) ), clique em download e ele o levará a um arquivo em archive.org. Você pode rolar para encontrá-lo ou “Localizar na página”/Control + F para encontrar seu jogo.

Alguns dos arquivos podem estar atrás de um bloqueio. Você precisa criar uma conta archive.org para

3. O último é apenas Archive.org

+ Se tudo o que foi dito acima não ajudou você a descobrir por que estava procurando, o archive.org o cobre.

+ Aqui está um vídeo do Sr. Sujano no YouTube que explica como usar o Archive.org para encontrar ROMs para download. Na última etapa, em vez de clicar no arquivo, você pode arrastá-lo para o Free Download Manager e ele deve ser processado.

+ Assim, com um gerenciador de download e depois de assistir ao Mr. Sujano, posso fornecer algumas palavras-chave que devem ajudá-lo a encontrar alguns bons ROMsets.

    + Cylum (muitos ROMsets)
    + Ghostware
    + usuário do reddit u/EBZero tem ótimos pacotes de ROM, pesquise EBZero
    + https://archive.org/details/retro-roms-best-set

É claro que “(inserir sistema) ROMset” também funciona

Deixe-me saber se isso é útil ou pode ser adicionado. Apenas um primeiro rascunho.


---

## Coleção de Links (para arrumar)
+ https://retrogamecorps.com/2022/10/16/steam-deck-emulation-starter-guide/

+ https://wagnerstechtalk.com/sd-batocera/

+ https://wagnerstechtalk.com/steamdeck/


- [RetroArch](https://www.retroarch.com/)
- [Dolphin](https://dolphin-emu.org/)
- [PCSX2](https://pcsx2.net/)
- [PPSSPP](https://www.ppsspp.org/)
- [yuzu](https://yuzu-emu.org/)
- [Citra](https://citra-emu.org/)


+ [Steam Deck Emulation by @nchristopher](https://github.com/nchristopher/steamdeck-emulation)

+ [RetroDECK](https://github.com/XargonWan/RetroDECK)

+ [EmuDeck](https://github.com/dragoonDorise/EmuDeck/)

+ 🇺🇸 [EmuDeck Wiki](https://github.com/dragoonDorise/EmuDeck/wiki)


### Nintendo Switch

+ https://github.com/dragoonDorise/EmuDeck/wiki/Ryujinx

+ https://yuzu-emu.org/
+ https://yuzu-emu.org/game/
+ https://www.reddit.com/r/yuzu/

+ https://ryujinx.org/
+ https://www.reddit.com/r/Ryujinx/


## Youtube
+ https://www.youtube.com/watch?v=LI7957GoM3k - Steam Deck: EmuDeck PS2 Emulation Full Guide - PCSX2 Emulator - by https://www.youtube.com/@ED4T

+ https://www.youtube.com/watch?v=PwO7P9u1Xag - Steam Deck: EmuDeck Nintendo 3DS Emulation Guide - Citra Emulator - by https://www.youtube.com/@ED4T

+ https://www.youtube.com/watch?v=m1FhvXbcvVs&t=466s - Steam Deck: EmuDeck PS3 Emulation Guide - RPCS3 Emulator - by https://www.youtube.com/@ED4T

+ https://www.youtube.com/watch?v=m8RdY5pxR34 - RPCS3 PS3 Emulator ISO Games Booting Fail Invalid File & Folder Fix - by https://www.youtube.com/@ED4T

+ https://www.youtube.com/watch?v=BmvUZKbXY9c - Steam Deck: EmuDeck Wii U Emulation Guide - CEMU Emulator - by https://www.youtube.com/@ED4T

+ https://www.youtube.com/watch?v=RajbovmLgTE&t=19s - Steam Deck: EmuDeck Nintendo Switch Emulation Guide - YuZu Emulator - by https://www.youtube.com/@ED4T

+ https://www.youtube.com/watch?v=oajbqjT_7RM - How to Run Android Games and Apps on Steam Deck at Maximum Performance ! - by https://www.youtube.com/@ED4T