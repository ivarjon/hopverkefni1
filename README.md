# hopverkefni1

    1. Hvernig skal keyra verkefnið
Eftir að clonað hefur verið repository, þarf að installa node.js (https://nodejs.org/en/download/).
Þar á eftir skal opna þitt local repository í commandline, og skrifa inn "npm install".
Þegar install er lokið skal einfaldlega skrifa inn "npm run dev" og VOILA, verkefnið opnast í vafra.

    2. Uppsetning verkefnis
Hægt er að finna fimm möppur innan rótar verkefnisins:
"efni" er óþörf en til stuðnings
"img" geymir allar myndir
"node_modules" geymir gögn sem sass notast við
"pages" geymir .html síður sem hægt er að nálgast frá index
"scss" geymir scss skjöl sem styles.scss sækir í
 
Í rót er index.html, styles.css, og styles.scss, sem geyma stoð verkefnisins.
.gitignore hunsar styles.css
.stylelintrc.txt stillir lint fyrir scss skrárnar
.gitattributes kemur í veg fyrir ósamræmi þegar unnið er á milli stýrikerfa
.editorconfig samræmir notkun á tabs og spaces, bilum og fleira
grid.css sýnir grind sem fyrirmynd er unnin eftir

Skrifað er alltaf í scss skrár og EKKI í css skrár í þessu verkefni.
Sass kerfið býr svo til css skrá fyrir vafrann þegar keyrt er npm run dev.

    3. Upplýsingar um alla sem unnu verkefnið
Ívar Jónsson (ivj3@hi.is)
Jón Karl Kristján Traustason (jkk17@hi.is)
Aron Bjarki Kristjánsson (abk18@hi.is)
