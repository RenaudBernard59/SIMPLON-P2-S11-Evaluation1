#Structure de la page index
    SECTION class="project" id="project1"
        HEADER class="projectHeader"
            H2
            ARTICLE class="projectPresentation"
                P class="oldProjectPresentation" + BUTTON edit
                FORM class="form newProjectPresentation"
                    INPUT class"projectTitleForm" id="projectTitleForm1"
                    INPUT class"projectPresentationForm" I id="projectPresentationForm1"
                    BUTTON save
        DIV BUTTON dell    
        SECTION class="projectContent container
            SECTION class="table" id="table1">
                HEADER class="tableHeader"
                    H3
                    ARTICLE class="tablePresentation"
                        P class="oldProjectPresentation" + BUTTON edit
                        FORM class"newTablePresentation"
                            INPUT class="tableTitleForm" id="tableTitleForm1-1"
                            INPUT class="tablePresenationForm" id="tablePresenationForm1-1"
                            BUTTON save
                DIV BUTTON dell  
                SECTION class="tableContent"
                    ARTICLE class="articles"
                        DIV class="articleContent" + BUTTON edit
                        FORM class ="newArticle"
                            INPUT class="neArticleDate form-control" id="newArtilcleDate1-1-1"
                            INPUT class="newArticleContent" id="newArticleContent1-1-1"
                            INPUT class="newArticleChecked" id="newArticleChecked1-1-1"
                            BUTTON save
                            BUTTON dell





# Afficher ou non form

## Sélectionner contenu

### Project-Presentation
$('article[ class=" projetPresentation pro1"] p[class="oldPresentation"]')
switch HIDDEN
$('input[id="projet-presentation-1"')

### Table-Presentation
$('article[ class=" tablePresentation pro1 tab1"] p[class="oldPresentation"]')
switch HIDDEN
$('input[id="table-presentation-1-1"]')

### Article-Content
$('article[class="tableContent pro1 tab1 art1"]  div[class="articleContent"]')
switch HIDDEN
$('article[class="tableContent pro1 tab1 art1"] form[class="form-inline"]')

## Switcher les classes HIDDEN ou non
### Project
MonProjet.show()
MonProjet.hide()
Transitions en fondu
MonProjet.fadeIn(600) 'slow' 0.5s
MonProjet.fadeOut(300) 'fast' 0.2s DEFAULT 400
### Table

### Article

## Récupérer contenu des formulaires
### Project
MonContenu.replaceWith() // Remplace par
MonContenu.prependd() // Ecrit à l'intérieur des balises
MonContenu.attr() // Récupère/Insère Attribu
MonContenu.removeAttr() //Suppr Attribu
MonContenu.addClass() 
MonContenu.removeClass()
### Table

### Article

## Ecrire le contenu des formulaires
### Project

### Table

### Article

# Création nouveau bloc

## Création des itérateur
### Project

### Table

### Article

## Création des blocs avec les classes perso
### Project

### Table

### Article

## Ecrire les blocs préparés précédemments
### Project

### Table

### Article

# EVENTS sur les boutons
## New
### Project
.on('click', function() { … }

$('p').on( 'click', function () {
    alert("Quelqu'un a cliqué sur un paragraphe!")
});

### Table

### Article

##Edit SWITCHER HIDDEEN
### Project

### Table

### Article

## Suppr
### Project

### Table

### Article


