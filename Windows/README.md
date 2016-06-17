# Windows build

# requisiti
- Visual Studio
- [svn](https://tortoisesvn.net/) bisogna installare anche i tool da riga di comando, che di default non vengono installati 

Il progetto da aprire con Visual Studio si trova nella cartella PCBuild

# Steps
- lanciare lo script get_externals.bat per ottenere i progetti esterni
- compilare pcbuild.sln con visual studio (release)
- per essere autocontenuta la release finale deve contenere anche la cartella Lib con tutta la libreria standard di python oltre agli eseguibili e librerie compile