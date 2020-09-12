<h1 align="center">Conky :tv:</h1>
<p align="center">Pequenas modificações feitas para meu uso pessoal em meu Desktop.<br/>Obs: O projeto não foi criado por mim, para conhecer o projeto procure por <a href="https://github.com/Brunomello-xD/conky_settings#conhe%C3%A7a-o-conky">"Conheça o Conky".</p></a>

<p align="center">
  <img src="img/conkyImg.png">
</p>

Informações úteis
=================
No meu caso estou usando um SSD e por isso idêntifiquei como SSD mas você pode alterar e coloca HD. Simplesmente altere as linhas 39 e 40 para as linhas abaixo.<br/>
Linha 39.<br/>
`${voffset 1}${offset 12}${font Ubuntu:pixelsize=12}${color FFA300}HD ${offset 9}$color${fs_free /} / ${fs_size /}${offset 30}${color FFA300}RAM ${offset 9}$color$mem / $memmax${offset 30}${color FFA300}CPU ${offset 9}$color${cpu cpu0}%`<br/>
 Linha 40.<br/>
`${voffset 1}${offset 12}${font Ubuntu:pixelsize=12}${color FFA300}HD ${offset 9}$color${fs_free /home} / ${fs_size /home}${offset 30}${color FFA300}  SWAP ${offset 9}$color$swap / $swapmax${offset 30}${color FFA300}`

Assim você terá algo mais parecido com sua máquina.

**SSD**
* **SSD / (raiz)** - `Memória livre / Total de memória`  
* **SSD /home (home)** - `Memória livre / Total de memória`

**MEMÓRIA RAM**
* **RAM** - `Memória usada / Total de memória`

**MEMÓRIA VIRTUAL**
* **SWAP** - `Memória em uso / Total de memória`

**PROCESSADOR**
* **CPU** - `Uso total`

Conheça o Conky
=================

* <a href="https://github.com/brndnmtthws/conky">GitHub Conky</a>
* <a href="https://github.com/brndnmtthws/conky/wiki">GitHub Wiki</a>

License
=================

Conky is licensed under the terms of the <a href="https://github.com/brndnmtthws/conky/blob/master/LICENSE">GPLv3</a> license.

