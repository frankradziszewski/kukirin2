# KuKirin Mod (Fabric, Minecraft 1.21.1, Java 21)

## Kompilacja
    ./gradlew build          # gotowy .jar: build/libs/kukirin-mod-1.0.0.jar
    ./gradlew runClient      # test w grze (dev)

Wymagania: JDK 21. Wersje (Loom 1.8, Yarn 1.21.1+build.3, Loader 0.16.10, Fabric API 0.105.0+1.21.1)
zmienisz w `gradle.properties`.

## Sterowanie
| Akcja | Klawisz |
|---|---|
| Wsiadanie | PPM na hulajnodze |
| Gaz / hamulec / wsteczny | W / S |
| Skręt | A / D |
| WHEELIE (pitch -30°, iskry) | trzymana SPACJA (wymaga jazdy) |
| NITRO (+30%, ogień z wydechu) | podwójne W (przytrzymaj drugie) lub Lewy Ctrl |
| Klakson | H |
| Zsiadanie | Shift (vanilla) |

Wszystkie klawisze (poza WSAD/Spacją) można zmienić w Ustawienia -> Sterowanie -> KuKirin Mod.

## Zawartość
- Encje: `kukirin:kukirin_g2_pro` (0.65 bloku/tick ≈ 47 km/h), `kukirin:kukirin_g4_ultra_max` (1.25 bloku/tick ≈ 90 km/h)
- Itemy: 2x hulajnoga, Easy Boost (Speed III + Haste II 45 s + pełne nitro), Kask Full-Face Carbon
  (blokuje obrażenia od upadku i uderzenia w ścianę, kosztem wytrzymałości)
- Zakładka kreatywna "KuKirin Mod"
- Dźwięki (syntezowane, podmień pliki .ogg w assets/kukirin/sounds/ na własne): silnik, klakson, nitro
- Cząsteczki: iskry (wheelie), płomienie + dym (nitro)
