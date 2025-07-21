Début

    Initialiser longueur ← 0
    Initialiser nbMots ← 1
    Initialiser nbVoyelles ← 0
    Définir voyelles ← "aeiouAEIOU"

    Écrire "Entrez une phrase se terminant par un point :"
    Lire caractère

    Tant que caractère ≠ '.'
        longueur ← longueur + 1

        Si caractère = ' '
            nbMots ← nbMots + 1
        FinSi

        Si caractère ∈ voyelles
            nbVoyelles ← nbVoyelles + 1
        FinSi

        Lire caractère
    FinTantQue

    longueur ← longueur + 1   // Pour inclure le point final

    Écrire "Longueur de la phrase : ", longueur
    Écrire "Nombre de mots : ", nbMots
    Écrire "Nombre de voyelles : ", nbVoyelles

Fin
