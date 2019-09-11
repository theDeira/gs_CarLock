# gs_CarLock-v1.03
Versie 1.03
# Depancy 
Dit script is nodig om het geluid te horen van je voertuig die sluit of open gaat:
Interact Sound : https://github.com/plunkettscott/interact-sound

Zet het bestand "carlock.ogg" in het script van interact sound: In Client -> html -> sounds
EN in de __resource.lua !!

In je server.cfg :
start interact-sound
start gs_carlock 

Zet altijd interact sound BOVEN gs_carlock in je server.cfg !

#Config

    ControlKey          = 217,       -- CAPSLOCK , voor andere keybinds kijk : https://docs.fivem.net/game-references/controls/
    NotCarOwner         = "Je bezit ~b~niet~w~ over de sleutels van dit voertuig..",
    CarLocked           = "Je voertuig zit ~r~op slot~s~.",
    CarOpen             = "Je voertuig is ~g~open~s~.",
    BlinkingLighstON    = true,     -- Knipperende Koplampen bij Openen en Sluiten voertuig
    CarBleepOnOpen      = true,     -- Bleep bij Openen van voertuig
    CarBleepOnClose     = true,     -- Bleep bij Sluiten van voertuig
    CarBleepDistance    = 5.0,      -- Radius hoe ver het geluid hoorbaar is voor andere spelers
    CarBleepVolume      = 0.5,      -- Volume van het geluid / MAX = 1.0 / MIN = 0.1
    TextBovenVoertuig   = false,     -- Bij true zie je of het voertuig "Open" of "Gesloten" is boven je voertuig
    BegrenzerAAN        = true,     -- Optie om een begrenzer aan of uit te zetten
    BegrenzerKey        = 201,      -- Welke knop voor de begrenzer? standaard: 201= ENTER/NUMPAD ENTER , voor andere keybinds kijk : https://docs.fivem.net/game-references/controls/
    -- Uitzetten Begrenzer : LEFT SHIT + BegrenzerKey
