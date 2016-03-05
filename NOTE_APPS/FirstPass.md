### FIRST PASS - SIMPLEST OF THE LOT
* We will begin by looking at 20 of the simplest command-line note-taking apps in Python from our original list;
* We are beginning with the simplest because our plan is to go through them one by one and "critique" them, if you will;
* We want to look at paradigms, at idioms, and at (personal) style in code-writing;
* Readability and use of comments + documentation will be taken into account;
* First we introduce the list of 20 Simplest Note-Taking Apps in the Python language (taken from Github repositories).

### 20 SIMPLEST OF THE LOT
* [Ezran/Note: Command line note app](https://github.com/Ezran/Note)
* [icymist/note: Script to take notes from command line](https://github.com/icymist/note)
* [prodicus/tnote: A command line note taking app so simple that even your granny will love it!](https://github.com/prodicus/tnote)
* [pmagwene/notesdotpy: A simple command line note taking script written in Python.](https://github.com/pmagwene/notesdotpy)
* [dmpop/pygmynote: Pygmynote is a Python-based command-line tool for storing and managing heterogeneous bits of data like notes, tasks, links, file attachments, etc.](https://github.com/dmpop/pygmynote)
* [stvnwlsn/note-py: Command-line note program](https://github.com/stvnwlsn/note-py)
* [mtimkovich/pynote: A command-line tool for storing notes](https://github.com/mtimkovich/pynote)
* [xero7689/pNote: Python Command-Line Note Program](https://github.com/xero7689/pNote)
* [gaissa/Notenal: A simple command-line notetaking application](https://github.com/gaissa/Notenal)
* [lowrey/notestore: Command line interface to notepad.cc.](https://github.com/lowrey/notestore)
* [devangb/notes: Command line note taking which works just like git](https://github.com/devangb/notes)
* [mackong/memo: Command line note-taking tool](https://github.com/mackong/memo)
* [Valiev/notes_cli: Command-line client for notes managing tools](https://github.com/Valiev/notes_cli)
* [nmukh/Python-Notebook: A simple command-line notebook application in Python](https://github.com/nmukh/Python-Notebook)
* [jknabl/reading-notes: Command line tool for managing quotations/notes as you read.](https://github.com/jknabl/reading-notes)
* [zmj64351508/mdnote: a note manager with command line interface](https://github.com/zmj64351508/mdnote)
* [jlreeder/snippets: A command line tool to store notes](https://github.com/jlreeder/snippets)
* [technopoetic/tiro: Tiro is a command line note taking application written in python](https://github.com/technopoetic/tiro)
* [kesfrance/snippets-app: A command line note taking app built with python, SQL and postgresql](https://github.com/kesfrance/snippets-app)
* [cgallemore/logit: Sometimes you just need to jot a note down, and since I'm at my command line the majority of the time, this does just that.](https://github.com/cgallemore/logit)

### CRITIQUING SOFTWARE GENRES - NOTE-TAKING APPS - COMMAND-LINE INTERFACE - PYTHON
## No. 1.0 - Ezran/Note
* [Ezran/Note: Command line note app](https://github.com/Ezran/Note)
* COMMENTS:
    * The app is simple enough, besides the README.md file, it consists of two programs, one in Python (main.py), the other an executable (note);
        * Ezran/Note/note: Executable File  87 lines (73 sloc)  2.63 KB;
        * Ezran/Note/main.py: 85 lines (72 sloc)  2.63 KB;
   * Without getting into any details on this, suffice to say that the two files mentioned previously are virtually exactly the same. For various reasons, we will be focusing on the "main.py" file, which is the Python program in question;
   * In the opening lines, three separate modules are imported: the argparse module, the sqlite3 module, and from os.path, expanduser is imported;
   * Essentially, after that we have the body of our program;
   * What we see are a few elements. First of all, we have code that will be dealing with the "os" part as well as the "sqlite3" part of the equation (sqlite3 = database);
   * Otherwise, what we have are relatively simple functions, called: "add", "print_list", and "delete";
   * As we can see, this note-taking app is very simple. We open up a connection to a database and define basic functions, and then add or delete "notes" to and from the database;
   * (More to come...)

## No. 2.0 - icymist/note
* [icymist/note: Script to take notes from command line](https://github.com/icymist/note)
* COMMENTS:
    * (More to come...)

## No. 3.0 - prodicus/tnote
* [prodicus/tnote: A command line note taking app so simple that even your granny will love it!](https://github.com/prodicus/tnote)

## No. 4.0 - pmagwene/notesdotpy
* [pmagwene/notesdotpy: A simple command line note taking script written in Python.](https://github.com/pmagwene/notesdotpy)

## No. 5.0 - dmpop/pygmynote
* [dmpop/pygmynote: Pygmynote is a Python-based command-line tool for storing and managing heterogeneous bits of data like notes, tasks, links, file attachments, etc.](https://github.com/dmpop/pygmynote)

## No. 6.0 - stvnwlsn/note-py
* [stvnwlsn/note-py: Command-line note program](https://github.com/stvnwlsn/note-py)

## No. 7.0 - mtimkovich/pynote
* [mtimkovich/pynote: A command-line tool for storing notes](https://github.com/mtimkovich/pynote)

## No. 8.0 - xero7689/pNote
* [xero7689/pNote: Python Command-Line Note Program](https://github.com/xero7689/pNote)

## No. 9.0 - gaissa/Notenal
* [gaissa/Notenal: A simple command-line notetaking application](https://github.com/gaissa/Notenal)

## No. 10.0 - lowrey/notestore
* [lowrey/notestore: Command line interface to notepad.cc.](https://github.com/lowrey/notestore)

## No. 11.0 - devangb/notes
* [devangb/notes: Command line note taking which works just like git](https://github.com/devangb/notes)

## No. 12.0 - mackong/memo
* [mackong/memo: Command line note-taking tool](https://github.com/mackong/memo)

## No. 13.0 - Valiev/notes_cli
* [Valiev/notes_cli: Command-line client for notes managing tools](https://github.com/Valiev/notes_cli)

## No. 14.0 - nmukh/Python-Notebook
* [nmukh/Python-Notebook: A simple command-line notebook application in Python](https://github.com/nmukh/Python-Notebook)

## No. 15.0 - jknabl/reading-notes
* [jknabl/reading-notes: Command line tool for managing quotations/notes as you read.](https://github.com/jknabl/reading-notes)

## No. 16.0 - zmj64351508/mdnote
* [zmj64351508/mdnote: a note manager with command line interface](https://github.com/zmj64351508/mdnote)

## No. 17.0 - jlreeder/snippets
* [jlreeder/snippets: A command line tool to store notes](https://github.com/jlreeder/snippets)

## No. 18.0 - technopoetic/tiro
* [technopoetic/tiro: Tiro is a command line note taking application written in python](https://github.com/technopoetic/tiro)

## No. 19.0 - kesfrance/snippets-app
* [kesfrance/snippets-app: A command line note taking app built with python, SQL and postgresql](https://github.com/kesfrance/snippets-app)

## No. 20.0 - cgallemore/logit
* [cgallemore/logit: Sometimes you just need to jot a note down, and since I'm at my command line the majority of the time, this does just that.](https://github.com/cgallemore/logit)
