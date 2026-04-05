# OpenEPaperLink-Pollenprognos
Visa pollenprognos på OpenEPaperLink display via Home Assistant.

Kräver så klart en fungerande OEPL-display ("Open EPaperLink").
https://github.com/OpenEPaperLink/Home_Assistant_Integration

Denna nyttjar också följande för själva pollendata:
https://github.com/JohNan/homeassistant-pollenprognos

Lägg in innehållet i filen configuration-yaml i Home Assistant configurayion.yaml på rätt plats.
Detat för att skapa sensorer som automationen kan ansopa utan att själv behöva ha koll på vilka pollen som är mätbara.

Klista sedan in koden från automations-filen i en HA automation. Glöm inte att ändra till korrekt OEPL-tagg/Display.

Exempel:

![Pollenprognos](https://github.com/user-attachments/assets/f3771aba-2b52-46ca-a69e-4118a96ddeaa)

