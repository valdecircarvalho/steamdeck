# Primeiras Configurações

- Desmontar o Steam Deck
- Trocar o SSD
- Fazer a instalação do SteamOS
- Configurar o Steam OS
- Acessar o modo desktop
- Particionar o SSD - Deixar a particao livre como NTFS
- Reboot
- Acessar o modo desktop
- Configurar senha sudo
- Instalar Google Chrome, Microsoft Edge
- Instalar o Decky Loader (https://deckbrew.xyz/)
  - Instalar os plugins: (https://plugins.deckbrew.xyz/)
    - CSS Loader
    - VibrantDeck
    - Fantastic
    - ProtonDB Badges
    - Bluetooth
    - Powertools
    - HLTB for Deck
    - AutoSuspend
    - MetaDeck
    - MoonDeck
    - Controller Tools
    - DeckSettings
- Instalar o CryoUtilities (https://github.com/CryoByte33/steam-deck-utilities)
-----
- Instalar o Windows
  - Baixar ISO
  - Baixar os driver do Windows para o Steam Deck (https://help.steampowered.com/pt-br/faqs/view/6121-ECCD-D643-BAA8)
  - Gravar ISO no pendrive com Rufus
  - Boot no Steam Deck com o pendrive
  - Fazer a instalação do Windows usando a particao livre
  - Após a instalacao finalizar, instalar os drivers do Steam Deck
  - Rodar o Debloat do Windows para remover os software não necessários (https://github.com/builtbybel/ThisIsWin11)
  - Ativar o Windows - eu tive que usar o comando no prompt do windows `slmgr /ipt <windows-key>` e funcionou. Pela UI não estava aceitando a minha chave.
  - Instalar o (Windows) Steam Deck Tools [https://github.com/ayufan/steam-deck-tools] / [https://steamdecklife.com/2022/12/26/steam-deck-tools-for-windows/]
## Instalar o SteamOS

- [Instruções de recuperação do Steam Deck](https://help.steampowered.com/pt-br/faqs/view/1b71-edf2-eb6d-2bb3)

Use as instruções abaixo para recuperar, reparar ou reaplicar a imagem do sistema do Steam Deck. Pode ser necessário segui-las caso não consiga inicializar o Deck, tenha instalado outro sistema operacional e deseje restaurar a versão do SteamOS que veio com o Deck ou esteja enfrentando outros problemas graves.

Para os curiosos, essa imagem de sistema ainda não é exatamente o SteamOS 3. Dependendo de onde você tentar instalar (computador de mesa, outro portátil, geladeira, torradeira), ela pode não funcionar corretamente. A versão final do SteamOS 3 será lançada depois do lançamento do Steam Deck (e, mesmo assim, ele pode não funcionar com a sua torradeira).


Instruções de recuperação do Steam Deck
Baixe a imagem de recuperação aqui.
Prepare um pendrive USB (mínimo 8GB) com a imagem de recuperação:

No Windows , recomendamos o uso do utilitário Rufus. Selecione o arquivo de recuperação e grave-o em seu pendrive USB (isso formatará o conteúdo do pendrive). Quando finalizar, selecione "Fechar" e ejete o pendrive.
No macOS, você pode usar Balena Etcher para gravar o arquivo de recuperação no seu pendrive USB.
No Linux, você também pode usar Balena Etcher para gravar o arquivo de recuperação no seu pendrive USB — ou, se preferir, pode fazê-lo diretamente do terminal:
bzcat steamdeck-recovery-1.img.bz2 | dd if=/dev/stdin of=/dev/sdX oflag=sync status=progress bs=128M
(troque /dev/sdX pelo identificador do pendrive USB inserido)

Use um adaptador ou hub USB-C para conectar o pendrive com a imagem ao Steam Deck.
Desligue o Steam Deck caso ainda esteja ligado. Segure o botão Diminuir Volume (-) e aperte o botão Liga/Desliga. Quando ouvir um som, solte o botão Diminuir Volume (-) — o Steam Deck deve exibir o gerenciador de inicialização (Boot Manager).
No gerenciador de inicialização, escolha inicializar a partir do "EFI USB Device" (o seu pendrive USB).
A tela ficará preta durante a inicialização — espere um minuto.
Depois de inicializado, você estará em um ambiente de área de trabalho. Navegue usando o trackpad e o gatilho.

Opções de recuperação
No ambiente de recuperação, há quatro opções diferentes para escolher:
Re-image Steam Deck (Reaplicar imagem ao Steam Deck) — Realiza uma restauração completa do sistema. Tudo, incluindo dados de usuários, jogos, aplicativos e sistemas operacionais, será apagado e substituído pela versão padrão do SteamOS.
Clear local user data (Limpar dados locais de usuários) — Reformata as partições "home" do Steam Deck, o que removerá os jogos baixados e todos os dados pessoais armazenados no Steam Deck, incluindo as configurações do sistema.
Reinstall SteamOS (Reinstalar o SteamOS) — Reinstalará o SteamOS no Steam Deck, tentando preservar os jogos e dados pessoais.
Recovery tools (Ferramentas de recuperação) — Abre uma janela com opções para realizar alterações na partição de inicialização do Steam Deck.


## Videos no Youtube que eu assisti durante essa jornada
- https://www.youtube.com/watch?v=CIJjFTsPgbY


## Links Uteis
- https://steamdecklife.com/?s=windows
- https://baldsealion.github.io/Steam-Deck-Ultimate-Windows-Guide/Master1000@!
- https://github.com/ayufan/steam-deck-tools
- https://github.com/mKenfenheuer/steam-deck-windows-usermode-driver
- https://github.com/ryanrudolfoba/SteamDeck-Clover-dualboot
- https://github.com/SteamDeckWindows/Steam-Deck-Windows / https://steamdeckwindows.github.io/Steam-Deck-Windows/
- https://github.com/TomBayne/SteamDeck-Windows-Script


[] Todo - Criar um script para fazer tudo isso de uma vez :) 