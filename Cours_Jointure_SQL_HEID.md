# GLOSSAIRE

- [Général](#général) [questions 1 à 17]
- [Front-end](#front-end) [questions 18 à 34]
- [UX / UI](#ux-ui) [questions 35 à 42]
- [Programmation orientée objet](#programmation-orientée-objet-poo) [questions 43 à 59]
- [Architecture](#architecture) [questions 60 à 66]
- [Modélisation / Base de données](#modélisation---base-de-données) [questions 67 à 83]
- [Symfony](#symfony) [questions 84 à 93]
- [Sécurité](#sécurité) [questions 94 à 103]
- [RGPD](#rgpd) [questions 104 à 113]
- [SEO](#seo) [questions 114 à 126]
- [Gestion de projets / DevOps](#gestion-de-projets---devops) [questions 127 à 142]
- [English](#english)

___
___

# Général
  
  
## 1.	Quel est l’environnement à installer pour exécuter un script PHP ? Citer 2 logiciels permettant ce contexte.


![Calcul de la densité de mots clés](images/join_sql/types-of-sql-joins-1.webp)

![Calcul de la densité de mots clés](images/17_densite.jpg)

![Calcul de la densité de mots clés](images/17_densite.jpg)



function afficherVariable() {
    global $variableGlobale; // Déclaration de la variable globale
    echo $variableGlobale;
}



```
class MaClasse {
    public $publicVar = "Public";
    protected $protectedVar = "Protected";
    private $privateVar = "Private";

    public function afficherVariables() {
        echo $this->publicVar;    // Accessible
        echo $this->protectedVar; // Accessible
        echo $this->privateVar;   // Accessible
    }
}

$obj = new MaClasse();
$obj->afficherVariables();
// echo $obj->protectedVar; // Provoquera une erreur
// echo $obj->privateVar;   // Provoquera une erreur
```


es
1. **Asynchrone** : les requêtes AJAX se font de manière asynchrone, ce qui signifie que l'utilisateur peut continuer à interagir avec la page pendant que la requête est en cours.

2. **Formats de données** : bien que le nom fasse référence à XML, AJAX peut également utiliser d'autres formats de données comme JSON, HTML ou texte brut.

3. **Utilisation de JavaScript** : AJAX s'appuie sur JavaScript, souvent en utilisant l'objet ``XMLHttpRequest` ou la méthode `fetch()` pour effectuer des requêtes.

#### Exemples simples

![Un exemple de code de requête AJAX](images/08_ajax.jpg)

#### Avantages
- **Expérience utilisateur améliorée** : les pages se chargent plus rapidement et de manière plus fluide.

- **Réduction de la bande passante** : seules les données nécessaires sont échangées, pas la page entière.

#### Utilisations courantes
- Chargement de contenu dynamique (comme les commentaires ou les articles).

- Envoi de formulaires sans recharger la page.

- Mise à jour de sections spécifiques d'une page (comme les notifications).

___

## 26.	Quel sélecteur CSS permet de sélectionner tous les éléments d’une classe spécifique ? D’un identifiant spécifique ? (déjà répondu à la question 23)

Le premier s'appelle le **sélecteur de classe** qui cible tous les éléments ayant une classe spécifique, **préfixée par un point (.)**.
```
.mon-style {
    font-weight: bold; /* Tous les éléments avec la classe "mon-style" seront en gras */
}
```

Le deuxième s'appelle le **sélecteur d'identifiant** qui cible un élément unique ayant un identifiant spécifique, **préfixé par un dièse (#)**.
```
#mon-id {
    background-color: yellow; /* L'élément avec l'id "mon-id" aura un fond jaune */
}
```



___
