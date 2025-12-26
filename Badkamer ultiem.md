🧠 1. WAT DEZE AUTOMATISERING KAN
💡 Licht
Aan bij aanwezigheid
Tijd-afhankelijk dimmen:
Dag / Avond / Nacht
🌙 Nacht WC-stand
Heel zacht licht
Alleen bij korte aanwezigheid
🎛️ Handmatige draaiknop = override
🔘 Automatisch licht aan/uit te schakelen
💨 Ventilatie
Aan bij:
Langere aanwezigheid
Douche-detectie
Hoge luchtvochtigheid
Nalooptijd instelbaar
🔘 Volledig aan/uit te schakelen
🛑 Altijd handmatig te overrulen
🚿 Douche-detectie (slim)
Douche =
👉 lang aanwezig + licht aan + (optioneel) vocht stijgt
Gebruik:
Ventilatie forceren
Script starten
Later uitbreiden (muziek, extra licht, etc.)
⏱️ Extra lange aanwezigheid
Bijvoorbeeld:
Make-up
Scheren
Schoonmaken
➡️ Kan:
Script starten
Licht helderder maken
Ventilatie langer laten lopen
🔌 Scripts aanroepen
Bij events:
Nacht WC
Douche
Extra lange aanwezigheid
👉 Jij bepaalt later wat die scripts doen.
📘 2. README – DIT MOET JE VOORAF DOEN
✅ Helpers aanmaken
Instellingen → Apparaten & diensten → Helpers
🔘 Schakelaars (input_boolean)
Maak deze exact zo:
Code kopiëren
Text
input_boolean.badkamer_auto_licht
input_boolean.badkamer_auto_ventilatie
input_boolean.badkamer_auto_douche
input_boolean.badkamer_auto_nacht_wc

input_boolean.badkamer_licht_handmatig
input_boolean.badkamer_ventilatie_handmatig
Aanbevolen start:
auto_licht → AAN
auto_ventilatie → UIT
auto_douche → UIT
auto_nacht_wc → AAN
