## Poker
This repository contains two perl based poker programs. While not written to the highest of perl coding standards and best practices, they might be useful in one form or another. Both programs have documentation included in the code. Place the code in a convenient location on your system and use **perl pgm.pl** at the operating system command line to run. Use **cpanm** or **MCPAN** at your OS command line to install any needed perl modules. Use each program's **-h** option to display it's usage text. The programs are provided as-is and function as described. You may need to modify them for the needs of your operating environment.<br/>

### OS: Linux
**DrawPoker.pl** - Proof of concept perl based five card draw poker game. Linux only. CLI based and ANSI color/character cards. 
Only basic game play is implemented and win/lose checking is incomplete.<br/>

**DrawPokerGUI.pl** - Perl/Tk based five card draw poker with game selectable options. Use CLI option **-h** for usage details. Use `cpanm` to install 
TK and GD perl modules. Some versions of TK don't include the `waitVariableX.pm` module. An old version is included in this archive. Copy it to your 
`perl\site\lib\Tk` directory.<br/>
