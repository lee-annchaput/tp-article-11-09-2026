---
title: "Diversité entre Paracou et BCI"
# Output formats
format:
  stylisharticle-pdf:
    keep-tex: true
    # Color example, see "Text color"
    header-includes:
      \definecolor{grey}{RGB}{191, 191, 191}
  stylisharticle-html:
    # Color example, see "Text color"
    css: colors.css
# Authors (https://quarto.org/docs/journals/authors.html#author-schema)
author:
  - name: Lee-Ann Chaput
    affiliations:
      - name: Dummy Organization
        department: Scientific Department
        address: Somewhere
        city: City
        country: Country
        postal-code: 9999
    orcid: 0000-0000-0000-0000
    email: JD@example.org
    url: https://example.org/
 # Abstract and Keywords
abstract: |
  This document is only a demo explaining how to use the Stylish Article template.
keywords: [template, demo]
# Bibliography
reference-section-title: References
bibliography: references.bib
# Language
lang: fr-FR
otherlangs: en-GB
# Code options 
# https://quarto.org/docs/computations/execution-options.html
execute:
  # show code chunk output
  include: true
  # Show the code in the output
  echo: false
  # Show messages
  message: false
  # Show warnings
  warning: false
  # Cache code results
  cache: false
# Template specific
journalinfo: "Publication reference"
archive: "DOI: xxx/xx"
keywordlabel: Keywords
corrauthorlabel: Corresponding Author
---


::: {.cell}

:::


# Introduction

- La question de la diversité des forêts tropicales fascine les écologues parce qu'elle a des enjeux très importants [@Gibson2011].
  est qu'elle est difficile à comprendre [@Wright2002b].

- Théorie neutre de Hubbell (hypothèse de saturation des parcelles) = si je fais mourir quelques arbres qui seront remplacés par un autre =\> fluctuations aléatoires =\> homogénéisation des espèces.

- Des modèles ont été publiés [@Liang2022].

- A l'heure des menaces sur la biodiversité [@Fadrique2026], une connaissance plus détaillée de la diversité des forêts très étudiées est utile.

# Matériel et méthodes

- Présentation du site de Paracou


 \scriptsize


::: {.cell}

:::


 \normalsize

La forêt de Paracou est un dispositif de placettes forestières d'environ 120ha géré par le Cirad (UMR EcoFoG).
Située en Guyane française, ce dispositif permanent permet un suivi temporel des placettes.
Celles-ci présentent différents niveaux de gestion forestière.

- Présentation du site de BCI


 \scriptsize


::: {.cell}

:::


 \normalsize

- expliquer nombre de hill [@hill1973]

- expliquer profil de diversité

# Résultats

::: {#fig-Profils}

 \scriptsize


::: {.cell}
::: {.cell-output-display}
![](index_files/figure-pdf/Profils-1.pdf)
:::
:::


 \normalsize

Profils de diversité de Paracou parcelle 6 courbe bleue et BCI courbe rouge.
La figure représente le nombre effectif d'espèce (nombre de Hill) en fonction de l'ordre de la diversité.
:::

# Discussion

- @MacArthur1967 montrent mathématiquement que la richesse spécifique (le nombre d'espèces) d'une île est un équilibre dynamique entre le taux d'immigration et le taux d'extinction, ce dernier étant directement dicté par la taille de l'île.

- BCI est une forêt secondarisée [@Raby2017].

- Sa diversité pourrait être augmentée selon la théorie de la perturbation intermédiaire [@Connell1978].

