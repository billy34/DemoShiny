# DemoShiny

## Execution sans installation

    library("shiny")
    runGitHub("billy34/DemoShiny", subdir="inst/ShinyApp")
    
## Installation

    library("devtools")
    install_github("billy34/DemoShiny")
    
## Execution après installation

    library("DemoShiny")
    gco_demo()
    
    
## Notes
* La fonction de lancement de l'application se trouve dans [**R/gco_demo.r**](R/gco_demo.r)
* Les sources de l'application (**app.r, ui.r, server.r**) doivent se trouver dans un sous dossier du dossier [**inst**](inst). Le contenu du dossier **inst** est copié tel quel lors de l'installation du package.
* La déclaration de l'extension (Addin) de Rstudio se trouve dans le fichier [**inst/rstudio/addins.dcf**](inst/rstudio/addins.dcf)
