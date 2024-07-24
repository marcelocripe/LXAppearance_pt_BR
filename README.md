# LXAppearance_pt_BR

Repositório oficial do programa "LXAppearance"

https://github.com/lxde/lxappearance/
e
https://github.com/lxde/lxappearance/blob/master/po/pt_BR.po


Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/LXAppearance_pt_BR/blob/main/lxappearance_pt_BR_marcelocripe_10-05-2022.po

https://github.com/marcelocripe/LXAppearance_pt_BR/blob/main/lxappearance_pt_BR_marcelocripe_22-07-2024.po

https://github.com/marcelocripe/LXAppearance_pt_BR/blob/main/lxappearance.desktop

- - - - -

Para utilizar o arquivo "lxappearance_pt_BR.po" e o "lxappearance.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"lxappearance_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt lxappearance_pt_BR_marcelocripe_10-05-2022.po -o lxappearance.mo

ou

$ msgfmt lxappearance_pt_BR_marcelocripe_22-07-2024.po -o lxappearance.mo


Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp lxappearance.mo /usr/share/locale/pt_BR/LC_MESSAGES


"lxappearance.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp lxappearance.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
