# Treegenerator

Software designed by Massimo Ronzulli, 2025.

**Italiano:** 
✨ Caratteristiche principali

🚀 Standalone: basta lanciare l’eseguibile, senza installare nulla.

📄 Output automatico: genera un file struttura.txt leggibile e pronto da condividere.

🔒 Sicuro e privato: funziona in locale, nessun dato inviato all’esterno.

🧑‍💻 Per tutti: utilizzabile sia da utenti privati che da professionisti in azienda.

🖥️ Windows ready: compatibile con ambienti Windows, senza dipendenze extra.

**English:**
✨ Key Features

🚀 Standalone: just run the executable, no installation required.

📄 Automatic output: generates a clean struttura.txt file, ready to share.

🔒 Secure & private: runs locally, no data sent outside.

🧑‍💻 For everyone: suitable for both personal and professional use.

🖥️ Windows ready: works on Windows environments with no extra dependencies.

## Descrizione / Description

**Italiano:** 
Treegenerator è un programma a riga di comando che genera automaticamente la struttura di cartelle e file di un progetto, salvando il risultato in un file `struttura.txt` nella stessa cartella del programma.  

Il programma:

- Sale di una cartella rispetto alla sua posizione.
- Esclude la cartella in cui è eseguito.
- Genera una rappresentazione ad albero simile a questa:

**English:**  
Treegenerator is a command-line program that automatically generates the folder and file structure of a project, saving the result in a `struttura.txt` file in the same folder as the program.

The program:

- Moves up one folder relative to its location.
- Excludes the folder where it is executed.
- Generates a tree-like representation similar to this:

```bash
Software designed by Massimo Ronzulli 2025
PSM/
├─ index.html
├─ struttura.txt
├─ Config/
│ ├─ index.html
│ └─ settings.php
└─ public/
  ├─ .htaccess
  ├─ index.php
  ├─ css/
  │ ├─ template.css
  │ ├─ base/
  │ │ ├─ buttons.css
  │ │ ├─ colors.css
  │ │ └─ forms.css
  │ ├─ components/
  │ │ └─ card.css
  │ ├─ layout/
  │ │ └─ navbar-buttons.css
  │ ├─ modals/
  │ │ └─ modaltablewindow.css
  │ ├─ tables/
  │ └─ widgets/
  │ └─ tablestyle.css
  └─ img/
```

## Installazione / Installation

**Italiano:**
Clonare il repository:
```bash
git clone https://github.com/maironz/TreeGenerator.git
```

Spostarsi nella cartella del programma:

```bash
cd TreeGenerator
```
**English:**
Clone the repository:
```bash
git clone https://github.com/maironz/TreeGenerator.git
```

Go to the program folder:
```bash
cd TreeGenerator
```

## Utilizzo/ Usage

**Italiano:**
Eseguire il programma da riga di comando:

```bash
TreeGenerator.exe
```

Dopo l'esecuzione, il file struttura.txt sarà generato nella stessa cartella del programma.

**English:**
Run the program from the command line:

```bash
TreeGenerator.exe
```
After running, the file struttura.txt will be generated in the same folder as the program.

## Licenza / License

**Italiano:**
Uso personale. Tutti i diritti riservati a Massimo Ronzulli, 2025.

**English:**
For personal use only. All rights reserved by Massimo Ronzulli, 2025.
