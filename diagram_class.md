classDiagram
    class Oeuvre {
        +int id
        +string titre
        +string auteur
        +string description
        +string contexte
    }

    class Pratique {
        +int id
        +string nom
        +string description
    }

    class Valeur {
        +int id
        +string nom
        +string description
    }

    class StandardProfessionnel {
        +int id
        +string nom
        +string description
    }

    class Preuve {
        +int id
        +string extrait
        +string source
        +string localisation
    }

    class Analyse {
        +int id
        +string interpretation
        +string justification
    }

    Oeuvre "1" --> "0..*" Pratique : met en oeuvre
    Oeuvre "1" --> "0..*" Valeur : porte
    Oeuvre "1" --> "0..*" StandardProfessionnel : reflete
    Oeuvre "1" --> "0..*" Preuve : est documentee par

    Analyse "1" --> "1" Oeuvre : concerne
    Analyse "0..*" --> "0..1" Pratique : analyse
    Analyse "0..*" --> "0..1" Valeur : analyse
    Analyse "0..*" --> "0..1" StandardProfessionnel : analyse
    Analyse "1" --> "1..*" Preuve : s'appuie sur
