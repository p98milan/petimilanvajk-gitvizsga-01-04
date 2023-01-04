Git inicializálása a projekt mappába:
    -git init

readme.md és .gitignore fájl hozzáadása a gyűjteményhez
    -git add .

readme.md és .gitignore rögzítése egy verzióban
    -git commit -m "Readme.md és .gitignore fájl létrehozva, .gitignore fájl kitöltve"

Új ág létrehozása console néven
    -git branch console

Átváltás a main ágról a console ágra
    -git checkout console

App.js módosítása után fájlok hozzáadása a gyűjteményhez
    -git add .

App.js módosításának rögzítése egy verzióban
    -git commit -m "App.js módosítva, console-ba üzenet kiíratva"

Style.css módosítása után fájlok hozzáadása a gyűjteményhez
    -git add .

Style.css módosításának rögzítése egy verzióban
    -git commit -m "Style.css módosítva, új átmenetes háttérkép beállítva"

readme.md hozzáadása a gyűjteményhez
    -git add readme.md

változtatások rögzítése egy verzióban
    -git commit -m "Readme.md fájl véglegesítése"

távoli gyűjtemény megadása
    -git remote add origin git@github.com:p98milan/petimilanvajk-gitvizsga-01-04.git

feltöltés a távoli gyűjteménybe
    -git push -u origin main
