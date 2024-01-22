# Projet-Final-L2

Le fichier Javascript

Partie 1: Définition des produits et des catégories

Le tableau `product` contient des objets qui représentent différents produits, chacun ayant des propriétés telles que `id`, `image`, `title` et `price`.

Le tableau `categories` est créé à partir des titres uniques des produits en utilisant `Set`.

Partie 2: Affichage des produits sur la page

Le code utilise la méthode `map` pour créer une chaîne HTML représentant chaque produit et l'insère dans la balise avec l'ID 'root'. Chaque produit est affiché avec une image, un titre, un prix et un bouton "Add to cart".

Partie 3: Fonctions du panier d'achat

- `addtocart(itemId)`: Ajoute un produit au panier en utilisant l'ID du produit.
- `delElement(a)`: Supprime un élément du panier en utilisant l'indice de l'élément dans le panier.
- `displaycart()`: Affiche les produits dans le panier, met à jour le total et le nombre d'articles dans le panier.

Partie 4: Interaction avec le DOM

- `document.getElementById('root').innerHTML`: Initialise la page en affichant les produits.
- `document.getElementById('count').innerHTML`: Met à jour le nombre d'articles dans le panier.
- `document.getElementById('cartItem').innerHTML`: Affiche les éléments du panier ou un message si le panier est vide.
- `document.getElementById("total").innerHTML`: Affiche le total du panier.

Remarques supplémentaires :

- Le bouton "Add to cart" utilise la fonction `addtocart` pour ajouter le produit correspondant au panier.
- Chaque élément du panier a un bouton de suppression (`fa-trash`) qui utilise la fonction `delElement` pour retirer l'élément du panier.
