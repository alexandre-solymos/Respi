## Tifly FR
`1.2.0.0`NOUVEAU !

Besoin d'un Framework CSS pour la gestion d'une grille ?
12 colonnes par défaut prochainement l'ajout de root pour l'utilisation des couleurs courantes

`#La version sccs est en phase de processus`

## DESCRIPTIF
L'objectif ici est de faire du mobile first ou du responsive rapidement.
Une CSS légère à 12 colonnes pour vous aider à créer rapidement des sites Web réactifs.
Chaque colonne est contenue dans des lignes, qui sont contenues est dans un container. 
Le container est défini sur une largeur maximale de 90% environ 960px, mais vous pouvez le modifier rapidement.

Il prend en compte le reset CSS +  Le système de grid

## Comment il fonctionne ?

<p>col-1-m = mobile</p> 
<p>col-1-t = Tablette</p> 
<p>col-1   = Desktop</p> 
<p>col-1-l = Desktop - Tv Extra large</p> 


> MOBILE

```css
 .col-1-m {
	width: 4.33%;
  }
  
  .col-2-m {
	width: 12.66%;
  }
  
.....
```

> TABLETTE

```css
 @media only screen and (min-width: 45em) {  /* 720px */
	.col-1-t {
		width: 4.33%;
	  }
	
	  .col-2-t {
		width: 12.66%;
	  }
.....
```


> DESKTOP

```css

	.col-1 {
		width: 4.33%;
	  }
	
	  .col-2 {
		width: 12.66%;
	  }
	
	  .col-3 {
		width: 21%;
	  }
.....
```


## CREATION COLONNE
Dans notre exemple, nous proposons un format type :

Le premier block avec la class="col-12-m col-3-t col-6 est défini tel quel :

- 12 colonnes pour la version mobile soit toute la surface
- 3 colonnes en version tablette et
- 6 colonnes pour la verion desktop/pc
 
 

```html
 <div class="container">
 
      <div class="row">
        <div class="col-12-m col-3-t col-6">
          <H1>test</H1>
          <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, temporibus!</h2>
        </div>
        
        <div class="col-4-m col-3-t col-6">
          <H1>test</H1>
          <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, temporibus!</h2>       
         </div>
         
        <div class="col-4-m col-3-t col-6">
          <H1>test</H1>
          <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, temporibus!</h2>       
         </div>
         
         <div class="col-4-m col-3-t col-6">
          <H1>test</H1>
          <h2>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, temporibus!</h2>       
         </div>

      </div>
 </div>
```

## RESULTAT DU CODE
Voici ce que donne l'exemple du code

> MOBILE

On remarque que nous avons le premier bloc qui prend toute la surface soit 12 colonnes.

Les 3 autres blocs sont sur une autre ligne automatiquement puisqu'il on une valeur de 4 colonnes
<div>
<img src="https://i.ibb.co/bWXzNbW/mobile.png"  width="50%" alt="kross portfolio template by themefisher">
</div>


> TABLETTE

On remarque ici, qu'il y à 4 blocs de 4 colonnes (soit 12 au total)
<div>
<img src="https://i.ibb.co/Mp2WfqD/tablette.png"  width="50%" alt="kross portfolio template by themefisher">
</div>

> DESKTOP

Ici chaque div prend 6 colonnes, donc le positionnement sera effective sur deux lignes 
<div>
<img src="https://i.ibb.co/q7pkYvc/desktop.png"  width="50%" alt="kross portfolio template by themefisher">
</div>

## MAJ 

`1.2.0.0`
- Ajout de col-l Objectif mettre en place le responsive également sur les écrans de minimum 1200 px

PROCHAINEMENT
Root + Couleurs

## SUPPORT & QUESTION

Si vous avez des questions ou avez besoin d'aide vous pouvez ouvrir un problème. Merci

## LICENCES

- Copyright 2020 Alexandre Solymos ()
