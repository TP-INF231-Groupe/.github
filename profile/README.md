## Informatique L2

UE : INF 231 – Structure de Données II

Encadrant : Pr. Metatagia



---

📂 Contenu du TP

 Notre travail contient 9 programmes en C, chacun correspondant à un exercice du TP.

somme_matrices.c → Somme de deux matrices

produit_matrices.c → Produit de deux matrices

recherche_seq.c → Recherche séquentielle dans un tableau

multiplication_plus1.c → Multiplication a × b (avec uniquement +1)

est_trie.c → Tester si un tableau est trié

mediane.c → Calcul de la médiane d’un tableau

inverser_tableau.c → Inverser un tableau

produit_vectoriel.c → Produit vectoriel (3D uniquement)

vecteur_matrice.c → Produit d’un vecteur par une matrice


 Nous nous sommes permis d'ajouter un Makefile  pour faciliter la compilation.


---

⚙️ Compilation

Pour compiler tous les programmes d’un coup,  on se placera dans le dossier du TP et on lancera :

make

👉 Cela génère 9 exécutables :
somme_matrices, produit_matrices, recherche_seq, multiplication_plus1, est_trie, mediane, inverser_tableau, produit_vectoriel, vecteur_matrice.

Pour compiler un seul programme, par exemple la médiane, on fait 

gcc mediane.c -o mediane


---

▶️ Exécution

Exemple: exécution du programme de somme de matrices :

./somme_matrices

Exemple: exécution du programme de produit vectoriel :

./produit_vectoriel


---

🧹 Nettoyage

Pour supprimer tous les exécutables générés, on pourra faire :

make clean


---

📑 Remarques

Tous les programmes utilisent des tableaux statiques pour simplifier la saisie et l’exécution.

Les entrées sont fournies par l’utilisateur via le clavier.

Les sorties affichent les résultats directement dans le terminal.

Le code est écrit en C standard (C11) et compilable avec gcc.
C'était tout pour notre TP INF231.
