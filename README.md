# Pedal-Access

Painel de edição acessível por voz para as pedaleiras **TC-Helicon VoiceLive 3** e **VoiceLive 3 Extreme**, pensado desde o início para quem usa leitor de tela ([NVDA](https://www.nvaccess.org/) e outros).

O programa descobre sozinho qual pedal está ligado (VL3 ou VL3X) e dá acesso, por teclado e com retorno falado, ao que o pedal oferece pelo MIDI: os efeitos de voz e de guitarra, Looper, Mix, Setup, footswitches, troca e gravação de presets, presets em arquivo (.syx) e backup completo. Os menus seguem o visor do próprio pedal, e o que for mexido no pedal é anunciado na hora. Quem não usa leitor de tela pode desligar a fala.

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)**. O pacote `Pedal-Access-Windows.zip` já vem pronto para rodar no Windows: é só extrair e abrir o `Pedal-Access.exe`. Não precisa instalar nada.

Para Mac (chip Apple ou Intel, macOS 11 ou mais novo, com VoiceOver) há o `Pedal-Access-Mac.zip`, ainda em teste: veja o `LEIA-ME-MAC.txt` na mesma Release para abrir na primeira vez. A partir da 0.2.4 o Mac também se atualiza sozinho (quem tem a 0.2.3 ou anterior no Mac baixa a 0.2.4 uma vez, pela aba Releases).

Para Linux (64 bits, com interface gráfica: BigLinux, Manjaro, Ubuntu, Mint, Fedora e parecidos) há o `Pedal-Access-Linux.tar.gz`, também em teste: extraia e abra o `Pedal-Access` de dentro da pasta. Veja o `LEIA-ME-LINUX.txt` na mesma Release.

Cada Release traz nas notas o **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali.

O programa se atualiza sozinho (Windows, Mac e Linux): ao abrir, confere se há versão nova e pergunta se você quer instalar. Presets, backups e configurações ficam como estão.

## Requisitos

- Windows 10/11 (64 bits), pedal ligado por USB (no pedal: SETUP, aba MIDI, Source em USB e SysEx ID em 0).
- Mac: macOS 11 ou mais novo, pedal ligado por USB; fala pelo VoiceOver.
- Linux: 64 bits (x86_64), pedal ligado por USB (sem driver); fala pelo speech-dispatcher, o mesmo do leitor de tela Orca.
- [NVDA](https://www.nvaccess.org/) é o leitor com suporte principal; também fala por leitores compatíveis com o Tolk e pela voz do Windows.

## Licença

Veja [LICENSE](LICENSE) para os termos de uso e os créditos de terceiros.
