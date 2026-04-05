# OpenEPaperLink-Pollenprognos
Visa pollenprognos på OpenEPaperLink display via Home Assistant.

1. Kräver så klart en fungerande OEPL-display ("Open EPaperLink").
https://github.com/OpenEPaperLink/Home_Assistant_Integration

2. Denna nyttjar också följande för själva pollendata:
https://github.com/JohNan/homeassistant-pollenprognos

3. Lägg in innehållet i filen configuration-yaml i Home Assistant configurayion.yaml på rätt plats.
Detta för att skapa sensorer som automationen kan anropa utan att själv behöva ha koll på vilka pollen som är mätbara.

4. Klista sedan in koden från automations-filen i en HA automation. Glöm inte att ändra till korrekt OEPL-tagg/Display.

5. Just nu är koden konfigurerad för at visa pollen mätstation Skövde.

Exempel:

![Pollenprognos](https://github.com/user-attachments/assets/f3771aba-2b52-46ca-a69e-4118a96ddeaa)

