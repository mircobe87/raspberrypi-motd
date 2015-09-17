# raspberrypi-motd
Messaggio del giorno personalizzato per **Raspberry Pi**.

![motds.png](./motds.png "Antemprima")

## Installazione
Nella seguente sezione, con il simbolo `$` si intende il normale prompt, mentre
con `#` si vuole indicare un root prompt.

1.	Clonare questo repo nella propria home su Raspberry Pi
    ```
		$ git clone https://github.com/mircobe87/raspberrypi-motd.git
    ```
2.	Entrare nel repo clonato:
    ```
        $ cd raspberrypi-motd
    ```
3.	Copiare il messaggio del giorno desiderato nel sistema creando prima
	una copia di backup del messaggio di default:
	```
    # mv /etc/motd /etc/motd.backup
    # cp src/motd-<DISTRO> /etc/motd
	```
	dove `<DISTRO>` sta per una delle distribuzioni linux tra quelle diponibili:

		- raspbian
		- archlinux
