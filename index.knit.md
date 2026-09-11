---
title: "Demo Stylish Article"
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
  - name: Elyse Lievre
    affiliations:
      - name: Université de Montpellier
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

La question de la diversité des forêts tropicales fascine les écologues parce qu'elle a des enjeux très importants [@Gibson2011].A l'heure des menaces pèsent sur la biodiversité [@Fadrique2026], une connaissance plus détaillée de la diversité des forêts très étudiées est plus que jamais nécessaire.Pourtant, celle-ci est qu'elle est difficile à comprendre [@Wright2002b].
Différents modèles ont été publiés sur ce sujet [@Liang2022].

L’objectif de ce rapport est de comparer la diversité de deux forêts étudiées possède une plus grande diversité.La première forêt étudiée est celle de Paracou et la seconde est celle de BCI.

La forêt de BCI étant en situation insulaire, il est possible d'émettre l'hypothèse que la forêt BCI possède une diversité moindre que l'autre forêt.

Correction : - [@Gibson2011] dit que sous les tropiques ce qui est important c'est les forêts !!
- [@Wright2002b] Pleins de mécanismes pour déterminer biodiversité mais on sait pas vraiment lesquels utiliser - théorie neutre de Stephen P. Hubbell permet de prédire la diversité - [@Liang2022] Prédiction nombre espèces en fonction de la latitude - [@Fadrique2026] une connaissance plus détaillée de la diversité des forêts est utile

# Matériels et méthodes

C'est quoi un nombre un hill ?
[@hill1973]

- Présentation du site de Paracou.


 \scriptsize


::: {.cell}

:::


 \normalsize

- Présentation du site de BCI.

BCI est une forêt secondarisée [@Raby2017] se trouvant sur l'île de Barro Colorado.
Sa diversité pourrait être augmentée selon la théorie de la perturbation intermédiaire [@Connell1978].


 \scriptsize


::: {.cell}

:::


 \normalsize

# Résultats

Création d'un tableau d'abondances avec une ligne par site.

::: {#fig-Profils}

 \scriptsize


::: {.cell}
::: {.cell-output-display}
![](index_files/figure-pdf/Profil-1.pdf)
:::
:::


 \normalsize

Profils de la diversité de Paracou parcelle 6 courbe bleue et BCI courbe rouge.
La figure représente le nombre d'effectif d'espèce (nombre de Hill) en fonction de l'ordre de la diversité
:::

# Discussion

Correction :

- \@MacArthur1967 montrent mathématiquement que la richesse spécifique (le nombre d'espèces) d'une île est un équilibre dynamique entre le taux d'immigration et le taux d'extinction, ce dernier étant directement dicté par la taille de l'île.

- BCI est une forêt secondarisée [@Raby2017].
  Sa diversité pourrait être augmentée selon la théorie de la perturbation intermédiaire [@Connell1978].

