# tint2-conf
Arquivo de configuração do painel Tint2

## transparente.tint2rc
![](https://raw.githubusercontent.com/tuxslack/tint2-conf/refs/heads/master/transparente.tint2rc.png)

$ mv -fv "$HOME/.config/tint2" "$HOME/.config/tint2.bak"

$ mkdir -p ~/.config/tint2/

$ cp transparente.tint2rc ~/.config/tint2/

Depois de realizar as alterações, reinicie o tint2 para ver o efeito:

$ pkill tint2 ; tint2 -c ~/.config/tint2/transparente.tint2rc &
