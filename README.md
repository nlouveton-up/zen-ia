# Le Zen de l'IA

Plutôt qu'un long discours... un petit texte à méditer sur l'usage des IA génératives à l'attention des étudiants comme des enseignants.

La forme du texte est inspirée de la PEP 20 du langage Python, le ton faisant humoristiquement penser à un texte de tradition asiatique.

Le texte est disponible :
- En [PDF](zen-ia.pdf) via LaTeX
- En [HTML](zen-ia.htm) via pandoc

# Publication

J'utilise le fichier LaTeX comme fichier source. Il est compilé via `pdflatex`. J'utilise pandoc pour générer la version HTML :

```{bash}
pandoc zen-ia.tex -s -c tufte.css -o zen-ia.htm
```

Les deux formats peuvent être produits en une seule commande (bash) :

```{bash}
./build.sh
```

# Crédit

- [PEP 20](https://peps.python.org/pep-0020/)
- [Tufte CSS de Dave Liepmann](https://edwardtufte.github.io/tufte-css/)
