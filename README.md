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
