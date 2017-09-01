# Ampersand

Ça serait un genre de Aide-memoire, mais on-steroids, et dont la disposition
des snippets ne se défait pas si on l'affiche dans une résolution différente
par après.

Les objets pourraient être de différentes natures:
- avec markdown, on pourrait linker vers divers endroits dans le document.
car chaque element (noeud) aurait un slug (ou un ID attribué), et ce slug pourrait etre le hash
pour l'atteindre par un scroll où il est.
- videos
- airtable views
- google maps
- images (from web or uploaded)
- links
- text (markdown or wysiwyg)
- each text box could display an image in the same canvas since every image
would make its own URL available somehow.
- exportable as a folder that would be read-only (in a zip folder that would
be self-contained)

## TODO:

- [ ] (frontend is done) draggable via: https://jqueryui.com/draggable/#constrain-movement

- [ ] (frontend is done) resizable via: https://jqueryui.com/resizable/#constrain-area

- [ ] rendre zoomable via: http://jaukia.github.io/zoomooz/

- [ ] peu importe ou on est, qu'on ait des boutons dans toutes les directions du
canvas pour nous dire ce qui existe dans chaque direction pour y aller
rapidement. (voir le code en dessous) (comme des fleches ou des tooltips qui
pointent vers les directions autour du viewport vers les autres destinations
pertinentes du canvas)

