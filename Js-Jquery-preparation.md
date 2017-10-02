#Structure de la page index
    SECTION class="project" id="project1"
        HEADER class="projectHeader"
            H2
            ARTICLE class="projectPresentation"
                P class="oldProjectPresentation" + BUTTON edit
                FORM class="form newProjectPresentation"
                    INPUT name"projectTitleForm" id="projectTitleForm1"
                    TEXTAREA name"projectPresentationForm" I id="projectPresentationForm1"
                    BUTTON save
        DIV BUTTON dell    
        SECTION class="projectContent container
            SECTION class="table" id="table1">
                HEADER class="tableHeader"
                    H3
                    ARTICLE class="tablePresentation"
                        P class="oldProjectPresentation" + BUTTON edit
                        FORM class"newTablePresentation"
                            INPUT name="tableTitleForm" id="tableTitleForm1-1"
                            TEXTAREA name="tablePresenationForm" id="tablePresenationForm1-1"
                            BUTTON save
                DIV BUTTON dell  
                SECTION class="tableContent"
                    ARTICLE class="articles"
                        DIV class="articleContent" + BUTTON edit
                        FORM class ="newArticle"
                            INPUT class="newArticleDate form-control" id="newArtilcleDate1-1-1"
                            INPUT name="newArticleContent" id="newArticleContent1-1-1"
                            INPUT name="newArticleChecked" id="newArticleChecked1-1-1"
                            BUTTON save
                            BUTTON dell

  $list.on('click', 'li', function() {
    var $this = $(this);
    $this.remove();
  });

button
id="editProjectPresentatio1n" > p class="oldProjectPresentation" id="oldProjectPresentation1"HIDDEN >Form
id="saveProjectPresentationForm1" >form class="form editProjectPresentation" id="editProjectPresentation1" HIDDEN > p
id="dellProjectPresentation1" > section class="project" id="project1"> 

id="editTablePresentation1-1" > p class="oldTablePresentation" id="oldTablePresentation1-1"
id="saveTablePresentationForm1-1" > form class="form editTablePresentation" id="editTablePresentation1-1"
id="dellTablePresentation1-1" > section class="project" id="table1-1"> 

id="editArticleContent1-1-1" > p class="articleContent" id="articleContent1-1-1"
id="saveArticleContentForm1-1-1" > form class="form-inline editArticle" id="editArticle1-1-1"
id="dellArticle1-1-1" >article class="articles" id="article1-1-1">
--------------------
$('button[id="editProjectPresentation1"]')
<<< HIDDEN $('p[id="oldProjectPresentation1"]') ECHO $('button[id="formProjectPresentation1"]')
&&& GOOD
$('button[id="saveProjectPresentationForm1"]')
<<< HIDDEN $('form[id="editProjectPresentation1"]')' ECHO $('p[id="oldProjectPresentation1"]')
&&& GOOD
$('button[id="dellProjectPresentation1"]')
<<< SUPPRIMER $('section[id="project1"]')
&&& GOOD
&&&&&&&&&&&&&&&&&& IDEM POUR STRUCTURE RESTANTE
$('button[id="editTablePresentation1-1"]')
<<< class="oldTablePresentation" id="oldTablePresentation1-1"
&&&
$(button[id="saveTablePresentationForm1-1"]')
<< form class="form editTablePresentbation" id="editTablePresentation1-1"
&&&
$('button[id="dellTablePresentation1-1"]')
<<< section class="project" id="table1-1"> 
&&&&&&&&&&&&&&&&&&
$('button[id="editArticleContent1-1-1"]')
<<< p class="articleContent" id="articleContent1-1-1"
&&&
$('button[id="saveArticleContentForm1-1-1"]')
<<< form class="form-inline editArticle" id="editArticle1-1-1"
&&&
$('button[id="dellArticle1-1-1"]')
<<< article class="articles" id="article1-1-1">
&&&&&&






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


