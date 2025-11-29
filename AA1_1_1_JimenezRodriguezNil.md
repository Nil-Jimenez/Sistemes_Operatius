## Computadors

#### 1. Quina és la diferència principal entre una GPU i una CPU?

La diferència principal és que la CPU se la centra de processament en general, en canvi, la GPU només fa el treball gràfic.

#### 2. Què és la memòria RAM i què implica que tingui accés aleatori a la memòria en comparació a la memòria d’emmagatzematge?

La memòria ram és Random Access Memori, està dissenyada per permetre que el processador accedeixi a la informació amb molta velocitat, en canvi, un disc dur, com que ha de guardar les dades (no són volàtils), tardaria molt a donar les dades a la CPU.

#### 3. Utilitza les comandes Bash vistes a classe i una màquina virtual amb Linux per a consultar el model de la CPU a través de comandes Bash.

Comanda: 
```
lscpu
```
<img width="1334" height="987" alt="image" src="https://github.com/user-attachments/assets/73550cfb-4c31-4a7d-ab05-e2d4db9da4fb" />

## Sistemes Operatius

#### 4. Per què creus que els sistemes operatius més utilitzats en dispositius incrustats estan basats en UNIX, així com en servidors i en consoles?

Els sistemes basats en UNIX van millor per que són mes estables, flexibles, portables, segurs, oberts i tenen un gran suport professional.

#### 5. Busca a internet algun exemple del sistema operatiu que podem trobar en un cotxe, en un dispositiu Wi-Fi i en un servidor.

Per els routers el mes famos es OpenWrt, esta basat en Linux, per un servidor el millor es Debian GNU/Linux, i per els coches QNX es un sistema operatiu fet per BlackBerry.

## Llicències de programari

#### 6. Busca el repositori oficial d’un programa de codi obert (exemple: Firefox o GIMP), i explica:

  #### a. Quina llicència utilitza. Explica en què consisteix.
  
Fa servir la llicència GNU General Public License v3 (GPL-3.0+), aquesta llicència et permet modificar, redistribuir, estudiar el programa pero sempre s'ha de poblicar amb la mateixa llicència, el que seria copyleft.
        
  #### b. Podries modificar el seu codi font? Per què?
        
Si que es pot modificar el seu codi ja que la llicència t'ho permet.
        
  #### c. Explica quina diferència hi hauria si aquest programa fos propietari.
  
No podries accedir ni modificar el codi, ni redistribuir-lo.

#### 7. Quins punts engloba la filosofia del free software que hem vist a classe?

Els punts son les llibertats d’ús, d’estudi, de modificació i de distribució.

## Comandes Bash

#### 8. Documenta i explica l'ús de les comandes “echo”, “bash”, “touch”, “read”, “sleep”.

##### echo

Mostra per pantalla un text o el contingut d’una variable.
```
echo "Hola"
```
<img width="747" height="187" alt="image" src="https://github.com/user-attachments/assets/2e8632e4-04bc-45ee-9576-22c5741dfe31" />

##### bash

Executa un script, per exemple un script on imprimeix la data
```
bash script.sh
```
<img width="745" height="208" alt="image" src="https://github.com/user-attachments/assets/8e9bfe47-8e4b-487a-8485-2c6ff2fa0334" />


##### touch

Crea un fitxer buit amb el nom que tu vulguis y el tipus de fitxer.

```
touch script.sh
```

<img width="756" height="197" alt="image" src="https://github.com/user-attachments/assets/a938a2ad-1254-4b35-9e21-fec15d13ce2f" />

##### read

Llegeix dades introduïdes per l’usuari i les guarda en una variable.

```
read nom
```
<img width="756" height="197" alt="image" src="https://github.com/user-attachments/assets/b47437bf-957f-4b1c-b71f-9300da83d413" />

##### sleep

Atura l'execució durant un temps determinat.
```
sleep 2
```

#### 9. Fes un script amb “nano” d’una vaca que saluda i mostra el contingut del directori que demana. Necessitaràs les comandes vistes en el punt anterior.

##### a. La vaca saluda.
##### b. El programa pregunta a l’usuari quina ruta vol consultar i guarda la resposta en una variable.
##### c. El programa confia que la ruta existeix i mostra el seu contingut.
##### d. El programa s’espera 2 segons.

```
cowsay Hola
echo "Quina ruta vols consultar?"
read ruta
ls "$ruta"
sleep 2
```
<img width="752" height="288" alt="image" src="https://github.com/user-attachments/assets/4e918a5b-d08d-4752-80f5-ce7b517b0048" />
<img width="775" height="390" alt="image" src="https://github.com/user-attachments/assets/8754efe5-70ee-4583-aa9b-382170ad1e2b" />

#### 10. Investiga com pots mostrar el resultat d’una comanda amb un altre color i explica cada paràmetre que has utilitzat.

##### a. Posa exemples usant altres colors.

Segons el que he trobat per canviar el color d'una comanda en concret, es pot fer fent servir la taula de colors ANSI, dependent del número que posis sortirà un color o un altre.

Primer "-e" permet interpretar el: \033 que serveix per indicar a la terminal que després venen uns paràmetres especials, [ comença la seqüència, el 31 és el numero que equival al color i finalment "m" indica el final de la seqüència.

En aquets cas es vermell:
```
echo -e "hola \033[31mhola\033[31m"
```
<img width="724" height="282" alt="image" src="https://github.com/user-attachments/assets/8a8e188d-a945-4d58-862a-00d5e65c90e8" />

## Bibliografía:

#### Chronigan. (n.d.). Buscando un sistema operativo para un router : r/homelab. https://www.reddit.com/r/homelab/comments/1ih2uwd/looking_for_an_os_for_a_router/?tl=es-es

#### (How to Change the Command Line Directory Text Color Permanently : R/Ubuntu, n.d.) https://www.reddit.com/r/Ubuntu/comments/ppvs4r/how_to_change_the_command_line_directory_text/ 

#### Wikipedia contributors. (2025, November 19). QNX. Wikipedia. https://en.wikipedia.org/wiki/QNX

