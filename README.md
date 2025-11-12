# Exercicis Bash

### a) Moviment de fitxers:

#### • Crea un directori anomenat docs_bash dins de la teva carpeta personal. 

```
mkdir docs_bash
```
<img width="418" height="92" alt="Captura de pantalla 2025-10-31 134540" src="https://github.com/user-attachments/assets/a5448f01-8240-4ab9-8c1e-6271e5743b1a" />

#### • Dins de docs_bash, crea els dos subdirectoris scripts i info. 

```
cd docs_bash
mkdir scripts
mkdir info
```
<img width="489" height="144" alt="Captura de pantalla 2025-10-31 134614" src="https://github.com/user-attachments/assets/e134e955-7433-4e34-8b1c-9d80c66f2d1b" />

#### • A la mateixa carpeta, utilitza touch per crear un fitxer buit anomenat 

```
touch README.md
```
<img width="505" height="91" alt="Captura de pantalla 2025-10-31 134700" src="https://github.com/user-attachments/assets/0f6e03ea-8df9-4c43-a69d-f3571c920eb0" />

#### • Combina l'instrucció echo, whoami i date per mostrar per pantalla la informació de l'usuari i data actuals. 

```
echo "$(whoami)" - "$(date)"
```
<img width="637" height="86" alt="Captura de pantalla 2025-10-31 134741" src="https://github.com/user-attachments/assets/23348633-1555-4413-be40-9a8fdc81ca19" />

#### • Utilitza $ echo "..." >> usuaris.log per crear un fitxer usuaris.log que registri l'informació de l'usuari i data actuals (punt anterior). 

```
echo "$(whoami)" - "$(date)" >> usuaris.log
cat usuaris.log
```
<img width="808" height="103" alt="Captura de pantalla 2025-10-31 134824" src="https://github.com/user-attachments/assets/8951e411-f804-460a-99c2-96415741bb3e" />


### b) Scripting bàsic:

#### • Crea el script sys_check.sh a la carpeta scripts i mostra l'escructura del projecte amb $ ls * des del directory docs_bash.

```
cd scripts/
touch sys_check.sh
cd ..
ls *
```
<img width="621" height="268" alt="Captura de pantalla 2025-10-31 140416" src="https://github.com/user-attachments/assets/acceacb2-e092-4268-9fd5-ba97c85c2ce7" />

#### • Utilitza nano o vim per editar el fitxer, aquest ha d'imprimir la data actual i actualitzar la llibreria de paquets del sistema.

```
sudo nano sys_check.sh

    echo "$(date)"
    sudo apt update
    sudo apt upgrade
```

<img width="627" height="159" alt="Captura de pantalla 2025-10-31 141906" src="https://github.com/user-attachments/assets/fec6b947-1fcf-4a19-883c-ea054bf2ac07" />


#### • Executa el fitxer resultant amb $ bash sys_check.sh i documenta per què surt un error i com solucionar-ho.

```
bash sys_check.sh
```
<img width="897" height="273" alt="Captura de pantalla 2025-10-31 141846" src="https://github.com/user-attachments/assets/4fa6e8ab-27ff-49a2-bc54-39f445eb001f" />

### c) Documentació de comandes:

#### • Executa les instruccions vistes anteriorment per obtindre la descripció de la comanda tail.
```
cd scripts/
touch sys_check.sh
cd ..
ls *
```
<img width="621" height="268" alt="Captura de pantalla 2025-10-31 140416" src="https://github.com/user-attachments/assets/acceacb2-e092-4268-9fd5-ba97c85c2ce7" />

#### • A partir de la descripció de tail, busca el paràmetre per mostrar l'última fila d'un fitxer.

```
sudo nano sys_check.sh

    echo "$(date)"
    sudo apt update
    sudo apt upgrade
```

<img width="627" height="159" alt="Captura de pantalla 2025-10-31 141906" src="https://github.com/user-attachments/assets/fec6b947-1fcf-4a19-883c-ea054bf2ac07" />


#### Executa el fitxer resultant amb $ bash sys_check.sh i documenta per què surt un error i com solucionar-ho.

```
bash sys_check.sh
```
<img width="897" height="273" alt="Captura de pantalla 2025-10-31 141846" src="https://github.com/user-attachments/assets/4fa6e8ab-27ff-49a2-bc54-39f445eb001f" />

### d) Documentació tècnica del projecte:

#### •  Afegeix al README les instruccions del fitxer sys_check.sh mitjançant la terminal utilitzant la comanda cat ... >> .... Revisa aquest apartat de GitHub per donar el format adequat als blocs de codi.
```
cd scripts/
touch sys_check.sh
cd ..
ls *
```
<img width="621" height="268" alt="Captura de pantalla 2025-10-31 140416" src="https://github.com/user-attachments/assets/acceacb2-e092-4268-9fd5-ba97c85c2ce7" />

#### • A partir de la descripció de tail, busca el paràmetre per mostrar l'última fila d'un fitxer.

```
sudo nano sys_check.sh

    echo "$(date)"
    sudo apt update
    sudo apt upgrade
```

<img width="627" height="159" alt="Captura de pantalla 2025-10-31 141906" src="https://github.com/user-attachments/assets/fec6b947-1fcf-4a19-883c-ea054bf2ac07" />


#### • Afegeix un apartat explicant el per què hem utilitzat l'usuari normal en comptes de l'usuari root i per què és perillòs utilitzar sudo su.
```
bash sys_check.sh
```
<img width="897" height="273" alt="Captura de pantalla 2025-10-31 141846" src="https://github.com/user-attachments/assets/4fa6e8ab-27ff-49a2-bc54-39f445eb001f" />
