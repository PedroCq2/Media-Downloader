# Oprava OnePlay pluginu (media_engine.novavoyo 0.2.9-35.alpha.4)

Opravuje `NullPointerException` v `Oneplay.getMediaInfo` (Oneplay.java:256),
když odpověď `content.play` neobsahuje `playerControl.tracking.contentData`.

## Instalace
1. Zavřít Media Downloader (spouštět z rozbalené složky, ne přímo z RAR).
2. Zazálohovat `resources\plugin\media-engine-novavoyo.jar`.
3. Nahradit ho souborem `media-engine-novavoyo.jar` z této složky.
4. Spustit aplikaci.

`Oneplay.java` a `oneplay-fix.diff` jsou jen zdroják a přehled změn, k instalaci nejsou potřeba.
