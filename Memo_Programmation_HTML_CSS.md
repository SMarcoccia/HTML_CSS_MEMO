

- Todo :
  - div[id^="img"] tout les id commençant par img dans des balises div.

<a id="Sommaire"></a>
# SOMMAIRE 

- <a href="#Abreviation"> Abréviation </a>
- <a href="#Definitions"> Définitions </a>
- <a href="#Web"> Web </a>
  - <a href="#Validateur"> Validateur HTML/CSS </a>
  - <a href="#Responsive"> Responsive Design </a>
  - <a href="#HTML_CSS_JS"> HTML/CSS/JS </a>
    - <a href="#HTML"> HTML </a>
    - <a href="#CSS"> CSS </a>
    - <a href="#JS"> JS </a>

# <a id="Abreviation"></a><a href="#Sommaire"> ABREVIATION </a>
  - => : alors.
  - élém : élément.
  - doc : document.
  - nb : nb.
  - dans : dans, des.
  - qe : que.
  - qlq : quelque.
  - attr : attribut.
  - fct° : fonction.
  - cara : caractère.

# <a id="Definitions"></a><a href="#Sommaire"> DÉFINITIONS </a>

- Page web statique :
  - Le contenu ne varie pas, tous le monde reçois la même page.

- Les métadonnées :
    - Informations qui permettent de caractériser un contenu.
    - Permet un meilleurs référencement.

- Balise :
  - Meta :
    - Def : paire mot-clé–valeur.
    - Attribut :
      - name : nom de la balise.
      - content : associé à name.
  - Title : 
    - Def : donne le nom à l'onglet du browser.

- Layout : mise en page de la page html. Façon d'agencer les éléments de la page. 
  - Ex. : <br><a href="https://www.casimages.com/i/19110710224816459916497046.png.html" title="Mon image" target="_blank"><img src="https://nsm09.casimages.com/img/2019/11/07//mini_19110710224816459916497046.png" border="0" alt="Mon image" /></a> <br>
  <center><u><a href=https://openclassrooms.com/fr/courses/1603881-apprenez-a-creer-votre-site-web-avec-html5-et-css3/1605881-structurez-votre-page> Crédit : OpenClassroom.</a><u></center>

<a id="Web"></a>
# <a href="#Sommaire"> WEB </a> 

<a id="Validateur"></a>
## <a href="#Sommaire"><u><center>**Validateur HTML/CSS** </center></u></a>

  - ### <span style="color: #FFFF00">**HTML :**</span> 
    - Lien : https://validator.w3.org/

    - Suppression des erreurs :
      - Mettre un titre dans `<section>`. 

  - ### <span style="color: #FFFF00">**CSS :**</span> 
    - Lien : https://jigsaw.w3.org/css-validator/

    - Suppression des erreurs :
<a id="Responsive"></a>
## <a href="#Sommaire"><u><center>**Responsive Design** </center></u></a>

 - ### <span style="color: #FFFF00">**Site Web Responsive**</span>
    >Définition : ajustement automatique de la page.
 - ### <span style="color: #FFFF00">**Site Web Adaptif :**</span> 
    - Palier résolution écran :
      - 320 : mobiles.
      - 480 : mobiles et mini tablettes.
      - 760 : mini tablettes et tablettes.
      - 960 : grande tablettes et ordi de bureau.
      - 1200 : ordi bureau et grand écrans.
      - 1600 : grand écrans.
    ><span style="color: #00FFFF">***Note :*** 1 résolution = 1 mise en page.</span>

    ><span style="color: #00FFFF">***Note :*** rajouter `<meta name="viewport" content="width=device-width, initial-scale=1.0">` permet d'afficher la vraie taille du site.</span>

<a id="HTML_CSS_JS"></a>
## <a href="#Sommaire"><u><center>**HTML/CSS/JS** </center></u></a>

<a id="HTML"></a>
- ### <a href="#Sommaire"> <span style="color: #FFFF00"><u>**HTML :**</u></span></a>

    - #### <span style="color: #0FF000">**Se déplacer dans la page :**</span>
      - Methode 1 :
        - Point de départ : `<a href="maPage.html#nomDeAncre">Bas de page</a>`<br>
        - &nbsp;&nbsp;&nbsp;  Point d'arrivé : 
      `<a name="nomDeAncre" href="#">Haut de page</a>`
      - Methode 2 :
        - Point de départ : 
          `<a href="#nomDeAncre">Bas de page</a>`
        - &nbsp;&nbsp;&nbsp;  Point d'arrivé : 
          `<div id="nomDeAncre">...</div>`
        - Note, inconvéniant : faire la même chose mais à l'envers.
    - #### <span style="color: #0FF000">**Flex :**</span>
      - ***Note :*** 
        - display: flex; obligatoire, permet de faire fonctionner FlexBox. Les élém. contenus dans le conteneur ou à été déclaré display: flex; seront impactés automatiquement comme des élém. de type flex-item. A mettre dans une régle css. 
        <br>
        Ex. &nbsp;:&nbsp; `#myFlex{display: flex;}`
        - display: inline-flex; idem.

      - **flex-direction :**
        - row : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061301295816459916272524.jpg" border="0" alt="Mon image" />
        - row-reverse : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061301295816459916272525.jpg" border="0" alt="Mon image" />
        - column : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061301295716459916272522.jpg" border="0" alt="Mon image" />
        - column-reverse : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061301295716459916272523.jpg" border="0" alt="Mon image" />

        <span style="color: #00FFFF">***Note :*** row est mis par défaut quand on appel display: flex.</span>

      - **flex-wrap :**
        - nowrap  : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061304565716459916272773.jpg" border="0" alt="Mon image" /> les élém sont redimensionnées pour rester sur la même ligne.
        - wrap  : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061304515616459916272765.jpg" border="0" alt="Mon image" />
        - wrap-reverse : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061304515616459916272766.jpg" border="0" alt="Mon image" />

      - **justify-content :**
        - flex-start : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061305423216459916272854.jpg" border="0" alt="Mon image" />
        - flex-end : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061305423116459916272850.jpg" border="0" alt="Mon image" />
        - center : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061305423116459916272851.jpg" border="0" alt="Mon image" />
        - space-between : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061305423116459916272853.jpg" border="0" alt="Mon image" />
        - space-around : <img src="https://nsm09.casimages.com/img/2019/06/13//mini_19061305423116459916272852.jpg" border="0" alt="Mon image" />

      - **align-items (pour l'axe verticale si on a choisie l'axe principale horizontale et inversement) :** 
        - flex-start : <img src="https://nsm09.casimages.com/img/2019/06/18//mini_19061807380516459916278244.jpg" border="0" alt="Mon image" />
        - flex-end : <img src="https://nsm09.casimages.com/img/2019/06/18//mini_19061807380516459916278243.jpg" border="0" alt="Mon image" />
        - center : <img src="https://nsm09.casimages.com/img/2019/06/18//mini_19061807380516459916278242.jpg" border="0" alt="Mon image" />
        - stretch : <img src="https://nsm09.casimages.com/img/2019/06/18//mini_19061807380516459916278245.jpg" border="0" alt="Mon image" /> <br>
        les élém sont étirés sur tout l'axe.
        - baseline : <img src="https://nsm09.casimages.com/img/2019/06/18//mini_19061807380416459916278241.jpg" border="0" alt="Mon image" /> <br>
        Alignés sur la ligne de base.

      - **align-self :**
    - #### <span style="color: #0FF000">**Balises :**</span>
      - `<div></div>` : crée un block sans marges ni enrobement (padding).
      - `<embed>` : Pour mettre un plug-in (vidéo, image, ...).
      - &nbsp;`<img>` &nbsp;:&nbsp; Pour mettre des images.
        - src (source).
        - Ex. : `<img src="../images/balise/rouge.gif" width="50" height="50">`
      - `<a></a>` &nbsp;:&nbsp; Pour mettre des liens.
        - href (référence de l'hyperlien) : pour   chemin vers le document cible.
      - ##### <span style="color: #00FFFF"><h3>__Balises fondamentales :__</h3></span>
        - `<html></html>` : Balise qui encapsule toute la page web (obligatoire).
        - `<head></head>` : En-tête de la page.
        - `<body></body>` : Corps de la page.
      - ##### <span style="color: #00FFFF"><h3>__Balises d'en-tête :__</h3></span>
        - `<link/>` : relation entre le document et une ressource externe. 
          - #### Attribut : 
            - `rel` (relationship) : relation entre la ressource et le document. Ex. : stylesheet, ...
            - `href`  : chemin de la ressource.
            - `media` : indique le média à utilisé (impression ou taille d'écran).
            - `type`  : définie le type de contenu. Ex. : text/html, text/css, ....
        - `<meta/>` : Info sur la page.
        - `<script><script/>` : Intégrer code JavaScript dans la page html.
        - `<style></style>` : Incorporer code CSS dans la page.
        - `<title></title>` : Titre de la page.

      - ##### <span style="color: #00FFFF"><h3>__Balises de structuration du texte :__</h3></span>
        - `<Section>` : Titre obligatoire avec        `<h1>` à `<h6>` sinon erreur validatoir.w3
        - `<article>` : Idem.
        - `<i></i>`   : pour mettre en italique. 
        - `<p>` :
        - `<span>` :
        - `<br>` :

      - ##### <span style="color: #00FFFF"><h3>__Liste :__</h3></span>
        - `<ol></ol>` : Ordonnée. (affiche des chiffres).
        - `<ul></ul>` : Non ordonnée (affiche des puce).
        - `<li></li>` : Element d'une liste.   
        - `<dl></dl>` : Liste de définitions.
        - `<dt></dt>` : Terme à définir (Ex. : un nom). 
        - `<dd></dd>` : Définition du terme (définition du nom).


    - #### <span style="color: #0FF000">**Tableau :**</span>
      - ##### <span style="color: #00FFFF"><h3>__Balise :__</h3></span>
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<table></table>` &nbsp;:&nbsp; Encapsule le tableau.
        - &nbsp; &nbsp; `<caption></caption>` &nbsp;:&nbsp; Titre du tableau.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<thead></thead>` &nbsp;:&nbsp; Encapsule l'en-tête.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<tbody></tbody>` &nbsp;:&nbsp; Encapsule le corps.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<tfoot></tfoot>` &nbsp;:&nbsp; Encapsule le pied.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<tr></tr>` &nbsp;:&nbsp; Encapsule une ligne. `tr` = table row.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<td></td>` &nbsp;:&nbsp; crée une cellule du corps. `td` = table data cell.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `<th></th>` &nbsp;:&nbsp; idem mais pour l'en-tête et le pied. `th` = table header cell.
        - `<colgroup></colgroup>` &nbsp;:&nbsp; encapsulation de `<col>`. Sert pour la mise en page des colonnes (est lié au `<th>`). 
        - `<col>` : Pour manipuler les cellules d'une colonne. <br><br>

        ><span style="color: #90F000">***Note :*** Attribut pour `<colgroup>`, `<col>` : <br>
            &nbsp; - &nbsp; `span="..."` &nbsp; &nbsp;:&nbsp; nb de colonne. <br>
            &nbsp; - &nbsp; `width="..."` &nbsp;:&nbsp; largeur de la colonne. <br>
            &nbsp; - &nbsp; `align="..."` &nbsp;:&nbsp; aligne horizontalement (left, center, right, justify).</span>

        ><span style="color: #90F000">***Note :*** `<th>` et `<td>` sont encapsulé par les `<col>` ; donc manipulation CSS du texte impossible.</span>

        ><span style="color: #90F000">***Note :*** Attention `<col>` n'est pas prioritaire dans le CSS même si après un td par exemple.</span>

      - ##### <span style="color: #00FFFF"><h3>__Attribut :__</h3></span>
        - `colspan` : fusionne les colonnes. Ex. : `<td colspan="2">`
        - `rowspan` : fusionne les lignes. Ex. : `<td rowspan = "2">` 
        - `scope` : associe les en-têtes (col ou row) à leurs données.
          >Ex. : 
            >>`<th scope="col">...</th>` 
            >>`<th scope="row">...</th>`
        - `headers` : avec `<td>` et `id` avec `<th>` permet d'associer `<td>` et `<th>`.
        ><span style="color: #00FFFF">***Note :*** Attribut headers ne doit pas être en combinaison de l'attr. scope.</span>
        
        ><span style="color: #00FFFF">***Note :*** quand on fusionne on supprime le nb de colonnes ou cellules fusionnées -1. Si 3 colonnes reste 2.</span>
  
      Ex. de code responsive en css : <br>
        - 1 :
          ```css
          @media(max-width: 40rem){
            table{table-layout: auto;}
            /*Redimenssionne le tableau naturellement puis scrolling du browser*/
          }
          ```
          !::[titre-video](//url-video)
          
        - 2 : 

          ```css
            @media(max-width: 40rem){
              table{
                display: block;
                overflow-x: auto; 
              }
              /*Redimenssionne pas correctement le tableau arrivé à 40rem.*/
            }
          ``` 


    - #### <span style="color: #0FF000">**Image :**</span>
      - ##### <span style="color: #00FFFF"><h3>__Balise :__</h3></span>
        - `<figure></figure>` : Pour l'encapsulation de la balise `<img>`.
        - `<figcaption></figcaption>` : La légende de l'image.

Note : les attr. width, height, padding, margin s'utilise qu'avec des balises blocks.

#

<a id="CSS"></a>
- ### <a href="#Sommaire"> <span style="color: #FFFF00"><u>**CSS :**</u></span></a>
    - <span style="color: #0FF000">__Fonction :__</span> 
      - <span style="color: #00FFFF">attr() :</span>  
        - Récupère la valeur d'un attr. d'un élém. pour l'utiliser ds la feuille de style.
        - Peut s'utilisé sur les pseudo-éléments (mot clé ajouté à un selecteur).

    - <span style="color: #0FF000">__Attribut :__</span> 
      - <span style="color: #00FFFF">__table-layout :__</span> 
        - fixed : toutes les cellules, du tableau ont la même dimension. 
        ><span style="color: #00FFFF">***Note :*** le contenu du texte peut débordé. Utilisé overflow.</span>

        - auto : toutes les cellules du tableau sont adapté en fonction du contenu.
        Si le mot de l'en-tête (`<th>`) est plus grand que son voisin sa cellule sera plus grande.
        ><span style="color: #00FFFF">***Note :*** Evite le débordement du mot de la cellule..</span>
        
      - <span style="color: #00FFFF">__text-overflow :__</span>
        - ellipsis : gère les textes trop long.

      - <span style="color: #00FFFF">__text-align :__</span>
        - left.
        - right.
        - center.

      - <span style="color: #00FFFF">__caption-side :__</span> 
        - bottom : met le nom du tableau en bas.

    - <span style="color: #0FF000">__Sélecteurs :__ 
      - <span style="color: #00FFFF">__Définition :__</span>
        - nom donnée pour indiqué à quel élément on      veut donner un style.
          >Ex. : `selecteur{color: red}`
      - <span style="color: #00FFFF">__Poids des sélecteurs :__</span>
        - Elément (balise) : 1.
        - Classe : 10.
        - ID : 100.
        - Attribut de style : 1000.
      - <span style="color: #00FFFF">__!important :__ </span>
        - L'emporte sur tous les autres styles.
      
      - <span style="color: #00FFFF">__Sélecteur Simple :__</span>
        - `uneBalise` &nbsp;:&nbsp; Cible n'importe quel balise  `<uneBalise>`.
        - &nbsp; `.myClass` &nbsp;:&nbsp; Une classe (`class="..."`).
        - &nbsp; &nbsp; &nbsp; `#myId` &nbsp; &nbsp;:&nbsp; Un identifiant (`id = "..."`).
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `*` &nbsp;:&nbsp; Cible tous les élém du doc. 
          >Ex. : <br>`*{`<br> &nbsp; &nbsp;`...` <br>&nbsp;`}`

      - <span style="color: #00FFFF">__Sélecteurs avancés :__</span>
        -  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `td, th` &nbsp;:&nbsp; 2 balises distinctes ayant       les même caractèristiques.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `a img` &nbsp;:&nbsp; Balise contenue dans une autre.
        - &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; `a[title]` &nbsp;:&nbsp; Sélectionne tous les liens    `<a>` qui possèdent un attribut title.
        - &nbsp; `a[title="click"]` &nbsp;:&nbsp; Idem mais l'attribut doit avoir la valeur 'click'.
        -  `a[title*="click"]` &nbsp;:&nbsp; Idem mais dans la chaîne de caractère doit avoir le mot 'click'.

      - <span style="color: #00FFFF">__Les combinateurs :__</span>
        - &nbsp; `tr + td` &nbsp;:&nbsp; Balise qui en suis une autre.
        - `p ~ span` &nbsp;:&nbsp; Cible les `<span>` qui    suivent ou non `<p>` qui on le même élém même parent.
        - `div > ul` &nbsp;:&nbsp; Ciblera qe les `<ul>` qui     sont enfants directs d'une div.
          ><span style="color: #00FFFF">***Note &nbsp; :*** &nbsp;recommandé pour plus de performance et si on utilise moteurs de sélecteur CSS basé sur JavaScript.</span>
        - `col || td` : Cible qe les `<td>` appartenant à une colonne.


      - <span style="color: #00FFFF">__Pseudo-classes :__</span>
        - Cible des élém avec une information d'état. 
          >Ex. : `a:visited` si lien visité => changera de couleur.

      - <span style="color: #00FFFF">__Pseudo-éléments :__</span>
        - Représente des attributs non décrit en HTML.
          >Ex. : `p::first-line` ciblera la 1er ligne de chacun des élém `<p>` du doc.

        - :before : crée un élém., qui sera le 1er enfant de l'élém. ciblé. 
          Ex. :
          ```css
            a:before {
              content: "Salut";
            }
            /*Ajoute "Salut" avant la balise <a>
            */
            /*a est le parent "salut" est l'enfant.*/
          ```
        - content : utilisé avec :before, :after pour créer un élém. <br>
        C'est un élém. remplacé (qui n'est pas modifié par le style du document, il faudra lui créer son propre style) .

    - <span style="color: #0FF000">__Unité de mesure :__ </span>

      - <span style="color: #00FFFF">__Rem :__</span> 
        - Def. : root em.
        - Taille : 1 rem == 12pt == 16px == 100%. <br>
        >Note : rem est relative au tout premier élément d’une page web, la balise html par exemple qui sera la racine (root) de la page.
        Tous les éléments utilisant l’unité de mesure Rem, auront une taille relative à cette taille (100% dans le cas présent).
        Ex. : html{font-size: 100%;}

#

<a id="JS"></a>
- ### <a href="#Sommaire"> <span style="color: #FFFF00"><u>**JS :**</u></span></a>

    - #### **Se déplacer dans la page :** 
      - Methode 1 :  


Notes en vrac.

- Recherche sur : nth-child.

- Ref : https://www.pierre-giraud.com/html-css/cours-complet/float-clear-css.php 

- Propriété `float`, `clear`, `overflow`, `position` :

  - `float` : fait sortir l'élément du flux.
    - Comportement : 
        - Élém suivants se positionne à côté. S'annule avec la propriété clear.
        - Élém positionnés avec position: absolute; ignore float.
        - Élém flottera dans les limites de la largeur de son parent conteneur.
    - `right` : positionne à droite.
    - `left`  :     "      à gauche.

  - `clear` : Évite que des éléments se positionne aux côtés d'élém flottants.
    - `Left`  : annule float: left;
    - `Right` :   "      "  : right;
    - `Both`  :   "    les 2.

  - `overflow` : gère les débordements causé par float. Élém flottant plus grand que son parent débordera verticalement.
    - `visible` : val par défaut.
    - `hidden`  : dépasse sera coupé.
    - `scroll`  : barre de défilement.
    - `auto`    : navigateur décide.
    - ...
    - `initial` : utilisation par défaut.
    - `inherit` : hérite de la propriété CSS overflow de son parent.

  - `overflow-x` : crée une barre de scroll. 
    - Utilisation : Tableau Responsive.
    - Attribut :
      - `auto`
    ><span style="color: #00FFFF">***Note &nbsp; :*** &nbsp; Obligation de l'utilisé avec `display: block;` &nbsp;   (`display: block` se met avant `overflow-x`).</span>

  - `overflow-wrap` : coupe un mot trop long et force le retour à la ligne.
  
  - `hyphens` : césure "intelligente" s'adapte aux règles typographique de la langue et affiche des traits d'union.
  Attention moins performant que : `word-wrap`

  ```css
    div{
      hyphens: auto;
    }
  ```
  - `word-wrap` : idem que `hyphens` en plus performant (coupe les mots).

  ```css
    div{
      word-wrap: break-word;
    }
  ```

  ```css
    div{
       word-break: break-word;
    }
  ```
  - `text-overflow : ellipsis;` : coupe le mot en 3 pts.
  - `position`: 
    - `relative` : positionnement de l'élém. par rapport à son parent.
    - `static` : positionnement par défaut.
    - `fixed` : reste toujours à la même place (même quand on scroll).
    - `absolute` : Positionnement absolu dans la balise conteneur, à condition qu'il ne soit pas statique. 
    - `inherit` : hérite de son parent (couleur, distance, ...).
    - Ex. :

      ```CSS
      div{
        position: relative;
      }
      ```


- z-index : permet le chevauchement de blocs. Utile pour les menus déroulant.

- height: 100%;  Pour être sûr de prendre toute la place en hauteur.

- font-size: 62.5%; Note : Utilisé  pour rem. Taille par défaut du browser pour les fonts et de 16 px donc si on fait 16*62.5% donne 10px soit 1 rem = 10px.

- 1em signifie donc 2 inches.

- border-spacing : distance entre les cellules.

- `display` : mise en page. Valeur par défaut : `block` ou `inline`.
  - Attribut :
    - `block` : s'étire au max sur la gauche et la droite. Prends toute la largeur disponible (avec saut de ligne avant et après). div, p, form, header, footer, section...
    - `inline` : encadre le texte dans un paragraphe. Occupera qe la largeur strictement nécessaire. a, span. 
    - `none` : masque ou affiche des élém CSS. Annule margin, padding, width, height...
      Note : none différent de visibility: hidden; qui masque juste les élém ; conséquence laisse des espaces vides.
    - `inline-block` : combine les 2 propriétées. L'élém sera de type inline (le conteneur) et ce qu'il 
      contient sera de type block. 
    - `table` : émule un tableau. On peut utilisé n'importe quel balise même des balise de tableau `<th>`, `<tr>`, ...<br>
    - `table-cell` : les balises deviennent des cellues. Elle s'aligne par défaut en haut. <br>
    Note :  Changer en faisant un `vertical-align`.
    
      Ex. :
      ```css
        #main{
          display:table;
        }
        /*On se sert d'une div avec un id="main". La div deviendra comme une balise <table>.*/
      ```



  Note : https://developer.mozilla.org/en-US/docs/Web/CSS/display

- BEM (Block, Element, Modifier) : a voir.

- `viewport` :
  - width=device-width : établie une corespondance avec la largeur de l'écran en pixels. 
  - initial-scale=1 : établie une relation entre px CSS et px du mobile. Prend toute la largeur de l'écran (mode paysage).
  - minimum-scale :  
  - maximum-scale :
  - user-scalable :
  
  >Ex. : <meta name="viewport" content="width=device-width, initial-scale=1">
  >Note : 
    - Les navigateur mobiles affiche la page avec la largeur d'écran d'un ordinateur de bureau (~980 px).
      Oblige à zoomer.
    - Les 3 derniers attribut peuvent empécher le zoom. 



#