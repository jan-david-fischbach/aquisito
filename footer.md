% This defines the footer of the site, and is not parsed as a regular "page"
% We point to it with the following in `myst.yml`:
% site:
% parts:
% footer: footer.md

% Here we use `grid` to add a basic grid structure to the HTML,
% but the formatting column sizes are defined manually in css/footer.css
% see the `grid-template-columns` line.
:::::{grid} 3 3 5 5
:class: outer-grid col-screen

<!-- Project description -->

::::{div}

```{image} images/Logo21_dark_ohneHintergrund.svg
:width: 200px
:align: left
```

Aquisito e.V.\
Vorsitzende: Antonia Tröll\
Tel.: 015774266766\
info@aquisito.de

::::

<!-- Spacer between project description and links columns -->

::::{div}
## Sitz
Ant Stäppken 33, 46348 Raesfeld\
SteuerNr.: 201 5905 6228\
Registernummer: VR6037\
Vereinsregister Aachen 
::::

::::{div}

IBAN: DE72 4306 0967 1003 9179 00\
BIC: GENODEM1GLS\
[zum Spendenformular](/donations)


- [Datenschutzerklärung](/datenschutz)
- [Satzung](/satzung)
- [Fördervereinbarung](/foerdervereinbarung)
- [Transparenz](/transparenz)


::::

:::::
