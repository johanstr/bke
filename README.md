# Bronbestanden voor de lessen JavaScript

## Inleiding
In deze repo kun je alle bronbestanden vinden van de lessen rondom JavaScript.  


## Gebruik van de repo
### Voorbereidingen
Om optimaal gebruik te kunnen maken van repo's op github.com dien je Git Bash te installeren (alleen voor Windows). Dit installeert een Linux gelijkende commandline omgeving op je systeem. Dit vereenvoudigd het gebruik van commandline commando's, zoals die voor <span style="color: cyan;">*git*</span>.  
  
Je kunt Git Bash downloaden van:    https://git-scm.com/downloads  
![Image of GitBash](https://res.cloudinary.com/vishnupadmanabhan/image/upload/v1491753329/git/original.jpg)  

  
In deze repo vind je ook het bestand **git_basic_manual.pdf**, dit is een basis handleiding voor <span style="color: cyan;">*git*</span>.  
Neem deze vooral door!  
  
Ieder serieus te nemen ontwikkelaar heeft een eigen GitHub account, dus maak zelf ook een account aan.  
  

### Wat je <span style="color: red;">*_NIET_*</span> moet doen
Je moet de repo niet downloaden als een ZIP.

### Wat je <span style="color: green;">*_WEL_*</span> moet doen
1. Eerste keer  
    Clone de repo in de rootmap van je lokale webserver.  
    Maak je gebruik van XAMPP dan is dit waarschijnlijk <span style="color: #EC407A;">*c:\xampp\htdocs*</span> 
    ![Rootmap of XAMPP](http://www.mytoptutorials.com/php/wp-content/uploads/2013/07/htdocs.png)  

    Maak je gebruik van WAMPP dan is dit waarschijnlijk <span style="color: #EC407A;">*c:\wampp\www*</span>  
    ![Rootmap of WAMP](https://hsnyc.co/wp-content/uploads/2015/03/wamp-server-files-in-www.png)
      
    De commando die je dan in bash intikt is:  
      
    ```bash
    git clone https://github.com/johanstr/bke-1920 <eigen naam voor de map waarin alles moet komen>
    ```  
      
2. Bijhouden van updates  
    Daarna wil je steeds de nieuwste versie van de repo binnenhalen. Door gebruik te maken van git haal je steeds alleen maar de laatste wijzigingen binnen. Dit maakt het downloaden van de laatste updates ook sneller.  
      
    Dit doe je met de volgende commando:  
      
    ```bash
    git pull --rebase origin master
    ```
      
    Door de bovenstaande commando te gebruiken kun je je eigen wijzigingen behouden, dus de code die jezelf nog hebt aangebracht in de code. Let wel <span style="color: #FB8C00;">*master*</span> is de naam van de hoofdbranch van de repo, terwijl er ook andere branches zijn, voor iedere les een eigen branch. Wil je de verschillende branches nog even apart binnenhalen dan kun je in bovenstaande commando het woord <span style="color: #FB8C00;">*master*</span> vervangen door de naam van de branch, bijvoorbeeld <span style="color: #FB8C00;">*les01*</span>.

  
## TIPS
Je kunt uiteraard ook gebruik maken van een GUI voor het werken met repo's. Voorbeelden van dergelijke apps zijn:  
  
1. SourceTree (Gratis)  
    ![Image of SourceTree](https://git-scm.com/images/guis/sourcetree@2x.png)  
    Download link: https://www.sourcetreeapp.com/  
      
2. GitHub Desktop (Gratis)  
    ![Image of GitHub Desktop](https://git-scm.com/images/guis/github-desktop@2x.png)  
    Download link: https://desktop.github.com/  
      
3. GitKraken (Beperkt Gratis)  
    ![Image of GitKraken](https://git-scm.com/images/guis/git-kraken@2x.png)  
    Download link: https://www.gitkraken.com/  

<span style="color: red;">*PAS OP!!!!!*</span> Je zult als o.a. web applicatie ontwikkelaar nog heel veel moeten doen met de bash terminal/commandline, dus het is aan te bevelen om zeker te leren via de commandline te werken.