## 🚀 Installation et exécution

### 1. Compilation
Assurez-vous que le fichier `compile.list` contient la liste de tous les fichiers source à compiler.
Depuis le dossier contenant vos fichiers `.java` :
- Pour les terminaux Linux:
```bash
javac @compile.list -d ../class
```
- Pour les terminaux Windows:
```bash
javac (Get-content compile.list) -d ../class  
```

### 2. Exécution
Un répertoire `class` vient, normalement, d'être créé. Assurez-vous que ce soit le cas.
Déplacez-vous dans ce répertoire avec la commande:
```bash
cd ../class
```

et exécutez la commande:
```bash
java MPM.Controleur
```
