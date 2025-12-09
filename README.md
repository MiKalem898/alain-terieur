# alain-terieur

https://alain-terieur.netlify.app


#### SLIDE 1 : Introduction (2 min)

*   **Accroche**
    
*   **Définition :** Bootstrap n'est pas un langage, c'est une boîte à outils (Framework) CSS
    
*   **3 Mots clés :**
    1.  **Vitesse :** On ne part pas d'une page blanche.
    2.  **Uniformité :** Le site s'affiche pareil sur Chrome, Safari, Firefox
    3.  **Responsive :** C'est le standard de l'industrie pour le mobile
        
*   **Transition :** Comment l'installer sans outils complexes ?
    

#### SLIDE 2 : Installation Vanilla (2 min)

*   **Contexte :** On parle ici d'installation Vanilla, sans React ni Node.js
    
*   **Option A (CDN) :**
    
    *   Comme du **streaming**. Le navigateur va chercher les fichiers chez Google/Bootstrap
    *   _Avantage :_ Ça prend 30 secondes
    *   _Défaut :_ Pas d'internet = pas de style
        
*   **Option B (Local) :**
    *   Comme un **téléchargement** => fichiers chez nous
    *   _Avantage :_ Robuste, marche hors-ligne.
        
*   **⚠️ Point Technique Crucial :**
    *   => Montrer le fichier JS
    *   toujours prendre la version **BUNDLE** (bootstrap.bundle.min.js). => elle inclut **Popper.js**, indispensable pour les menus déroulants et les pop-ups
        

#### SLIDE 3 : La Grille / The Grid (4 min) - _Le plus important_

*   **Concept :** la page est divisée en **12 colonnes**
    
*   **Maths simples :**
    *   1 colonne = 1/12ème
    *   col-6 = 50% de la page (6/12)
    *   col-12 = 100% de la page
        
*   **Responsive (Breakpoints) :**
    *   Expliquer le md dans col-md-6.
    *   => Cela signifie : sur les écrans Moyens (Medium) et plus grands, prends 6 colonnes. En dessous (mobile), reprends le comportement par défaut (100%).
    

#### SLIDE 4 : Espacement / Spacing (2 min)

*   **Problème :** Finis les fichiers CSS avec 50 lignes de margin-top: 20px;
*   **Solution :** Les classes utilitaires
*   **Syntaxe :** m (Marge) ou p (Padding) + t/b/s/e (Direction) + 0-5 (Taille)
    
*   **Exemples :**
    *   mt-5 : Une grosse marge en haut.
    *   px-3 : Un petit padding à gauche et à droite
        
*   **Conclusion :** On construit la mise en page directement dans le HTML. Ça va beaucoup plus vite
    

#### SLIDE 5 : Flexbox (2 min)

*   **Utilité :** Pour l'alignement (centrer des choses)
*   **L'interrupteur :** d-flex active le mode Flexbox sur un élément.
*   **Les commandes :**
    *   justify-content : Gère l'axe horizontal (ex: écarter les éléments)
    *   align-items : Gère l'axe vertical (ex: centrer un texte dans une barre)
*   **Note :** C'est indispensable pour les barres de navigation (Navbars).
    

#### SLIDE 6 : Les Composants (2 min)

*   **Métaphore :** Ce sont les briques LEGO
*   **La "Card" :** C'est le composant roi du web moderne (Instagram, Pinterest, Amazon... tout est une "carte", un **container**)
    
*   **Workflow :**
    1.  Aller sur la doc officielle (GetBootstrap)
    2.  Copier le code
    3.  Coller
    4.  Personnaliser
        
*   **Sémantique :** Mentionner les couleurs : btn-primary (bleu), btn-danger (rouge), btn-success (vert).
    

#### SLIDE 7 : Avantages, Inconvénients & Fin (1 min)
*   **Honnêteté intellectuelle :** Bootstrap n'est pas parfait.
*   **Inconvénients :**
    *   Sites clones ("Bootstrap look"). Il faut personnaliser sinon tout se ressemble
    *   Code lourd
        
*   **Pourquoi l'apprendre quand même ?**
    *   C'est une base 
    *   Très bonne documentation
    *   Si on bloque, la réponse est sur Google
        
*   **Conclusion**
