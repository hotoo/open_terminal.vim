# open terminal, filemanager : Open native terminal , file manager app for various platforms

Some vim user want to shell like emacs's eshell. But vim don't support shell,
terminal interface in vim (at least  7.x version).

In this situation, I try some terminal patches or shell attached plugins.
But everyone don't perfectly emulate native terminal or have much dependencies.
So I use simple native terminal and filemanager open script for my various platforms.



Commmands

    :OpenTerminal              Open native terminal sw.
    :OpenFilemanager        Open native file manager.



Key map recommendations (I'm using)

   nnoremap <silent> <F9> :OpenTerminal<CR>
   nnoremap <silent> <F10> :OpenFilemanager<CR><CR>



Tested platform

* Mac  ~ Terminal.app,      finder
  * MacVim
* Windows 7 64bit, XP ~cmd.exe , explorer
  * [portable] gVim
* Gnome  ~ gnome-terminal,  nautilus
  * gVim

This is very simple script. If plugin show wrong operation feedback to me. I can't test in windows xp, KDE etc  :)

## install details

open "open_terminal.vba" with vim
:so %
:help open-terminal
