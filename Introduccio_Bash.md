## Exercici1. Escriu en un document markdown una introducció a bash:

### a) Investiga quina diferència hi ha entre emular i virtualitzar un sistema. Perquè parlem de virtualitzar una distribució Linux i, en canvi, parlem d'emular una consola?
```
Virtualitzar una distribució de Linux es refereix que a crear una màquina virtual  completa (tot el sistema operatiu) dintre d’un altre.
En canvi, emular una consola és només obrir una consola d’un altre OS, sense tenir tot el seu sistema operatiu.
```

### b) Documenta i explica l'ús de les comandes vistes anteriorment. Afegeix una captura mostrant un exemple d'ús i indica l'origen del seu nom si s'escau (Exemple: "mkdir" té el seu origen en l'expressió "make directory").
```
whoami
# Mostra l'usuari actual, whoami (qui soc jo)
```
<img width="320" height="114" alt="image" src="https://github.com/user-attachments/assets/a7b5791b-416c-4e10-b9a9-1c20627a77e4" />

```
clear
# Neteja l'intèrpret de comandes
```
<img width="464" height="133" alt="image" src="https://github.com/user-attachments/assets/1076b2dd-e9ec-4ce8-ba9e-a758e10b57ff" />

```
Pwd (print working directory)
# Mostra el directori actual
```
<img width="331" height="113" alt="image" src="https://github.com/user-attachments/assets/1528d37a-2841-46f6-bf59-1319259597e5" />

```
cd [ruta]
# Canvia la direccio de directoris (cd: change directory) 
```
<img width="331" height="113" alt="image" src="https://github.com/user-attachments/assets/1528d37a-2841-46f6-bf59-1319259597e5" />

```
# /home/enti/Documents/exercicis -> ruta absoluta
```
<img width="564" height="64" alt="image" src="https://github.com/user-attachments/assets/70e12a31-091b-4d6e-b99b-005f6d9cd561" />

```
# ./exercicis-> ruta relativa des de Documents
```
<img width="395" height="61" alt="image" src="https://github.com/user-attachments/assets/38bf58de-8220-4fd8-af58-8c15c8b5cc41" />

```
ls (list segment)
# Llista el contingut del directori actual
```
<img width="1008" height="367" alt="image" src="https://github.com/user-attachments/assets/d709b579-09db-4f9b-b8ac-caad4d75be94" />

```
mkdir {nou_directori} (make directory)
# Crea un directori nou
```
<img width="542" height="125" alt="image" src="https://github.com/user-attachments/assets/a0fbdae9-5ff1-4d77-875f-e3aca3482372" />

```
touch {nou_fitxer}
# Crea un fitxer nou
```
<img width="528" height="130" alt="image" src="https://github.com/user-attachments/assets/a51ef20b-caf8-476e-bd31-442717cf8607" />

```
Cp: copia un fitxer/directori a una nova posició, en aquest cas que creat un .txt i l’he posat dintre la carpeta de exercicis
```
<img width="616" height="148" alt="image" src="https://github.com/user-attachments/assets/ed0e2f36-fb42-45af-ba7e-1445b5eebe3a" />

```
Mv: mou un fitxer/directori a un nou directori, en aquest cas que mogut el directori test dintre la carpeta exercicis
```
<img width="616" height="189" alt="image" src="https://github.com/user-attachments/assets/c2162354-b788-458d-8872-03dcc1a0b8df" />

```
Rm: elimina un fitxer, i rm –r elimina un directori, en aquest cas he eliminat el directori mogut anteriorment.
```
<img width="625" height="158" alt="image" src="https://github.com/user-attachments/assets/6e76f66e-4b3f-4ef2-a2ef-f6125d205f44" />

```
Cat: mostra la visualització o d’un fitxer:
```
<img width="603" height="109" alt="image" src="https://github.com/user-attachments/assets/5d69b0d6-77f6-4387-b101-1ca9bf195150" />

```
tail 
# Mostra les 10 últimes línies del fitxer, es pot veure la diferència entre el cat que mostra tot el fitxer i el tail que només mostre les últimes línies
```
<img width="741" height="719" alt="image" src="https://github.com/user-attachments/assets/e96e5834-01e8-4257-ae80-35190da13b6a" />

```
Nano: obre l’editor gnu del fitxer
```
<img width="903" height="366" alt="image" src="https://github.com/user-attachments/assets/e3586070-5629-4954-84e3-466494ccbba4" />

```
Vim: Igual que el nano, vim és un altre editor:
```
<img width="883" height="939" alt="image" src="https://github.com/user-attachments/assets/9ac79de1-5ff9-4a6b-ab1c-e236c8a69c16" />

```
Man: Mostra el manual de la instrucció de la comanda que li hagis preguntat
```
<img width="939" height="523" alt="image" src="https://github.com/user-attachments/assets/d774234b-5f29-46d2-b9c9-37b1c3982e78" />

```
--help: mostra un resum de manual de la comanda que li hagis posat:
```
<img width="939" height="673" alt="image" src="https://github.com/user-attachments/assets/9ab8d7dd-6f6a-4d53-b6d2-1e1d46fea6de" />

### c) Explica la diferència entre un llenguatge de programació compilat i unllenguatge de programació interpretat. Documenta el procés de creació i execució d'un arxiu ".cpp" i un ".sh".
```
Un llenguatge compilat tradueix el codi font a codi màquina abans d’executar-se, fent-lo més ràpid però menys flexible.
Un llenguatge interpretat s’executa línia per línia mitjançant un intèrpret, sent més lent però fàcil de provar i portable.
```

#### Codi C++
<img width="772" height="114" alt="image" src="https://github.com/user-attachments/assets/4b0ec9f4-6ee6-4dcf-9db7-c318adddde25" />
<img width="924" height="244" alt="image" src="https://github.com/user-attachments/assets/b2882ff5-e7b9-4a28-bc01-289799eadff0" />
<img width="438" height="129" alt="image" src="https://github.com/user-attachments/assets/72cd8a03-d66c-4ce4-9f7c-3ab58781b4b4" />

#### Codi Bash
<img width="939" height="164" alt="image" src="https://github.com/user-attachments/assets/57ac190a-be80-4e1f-952b-a47f729fb24a" />
<img width="439" height="106" alt="image" src="https://github.com/user-attachments/assets/4527f4b9-d8f5-459c-8128-488a7d754d45" />



