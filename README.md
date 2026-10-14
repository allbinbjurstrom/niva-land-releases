# Nivå Land för Mac

[**Hämta Nivå Land Lokal 0.12.2 för Apple Silicon**](https://github.com/allbinbjurstrom/niva-land-releases/releases/download/v0.12.2/Niva-Land-Lokal-0.12.2-arm64.zip)

Mac med **M1 eller senare** och **macOS 14 eller senare**. ZIP-filen är cirka 134 MB.
Alla som spelar tillsammans ska installera samma version.

## Installera

1. Hämta ZIP-filen och dubbelklicka för att packa upp den.
2. Flytta **Niva Land Lokal.app** till **Program**.
3. Öppna appen. Stäng en tidigare version före uppdatering; dina sparningar ligger separat.

Detta är ett LAN-testbygge med verifierad ad hoc-signatur, ännu inte attesterat av Apple.
Om macOS blockerar första starten kan du, när du litar på hämtningen, följa
[Apples anvisningar](https://support.apple.com/sv-se/102445): försök först öppna appen,
gå sedan till **Systeminställningar → Integritet och säkerhet → Öppna ändå** för just appen.

## Spela med andra på LAN

1. Anslut Macarna till samma Wi-Fi eller Ethernet-nätverk.
2. Värden väljer **Skapa LAN-spel** och antal spelare.
3. Värden kopierar **LAN-inbjudan** och delar den med gästerna.
4. Gästerna väljer **Anslut till LAN-spel** och klistrar in hela inbjudan.
5. Värden väljer **Starta** när alla har anslutit och låter appen vara öppen.

Tillåt appens lokala nätverksåtkomst om macOS frågar. Internet och konto behövs inte
under matchen. Värden sparar världen; varje gäst behåller sin egen session och träningshistorik.
Vid avbrott sparas gästens väntande svar tills samma värd återkommer.

## Ingår

- 1 600 egna frågor från version 5, 200 per HP-delprov, med material och facit.
- 127 modeller i spelet samt 57 tekniker. Ett klick på en teknik visar informationen.
- Solo eller LAN med 2–6 spelare, paus, sparning och återupptagning.

## Verifierat för detta paket

LAN-flödet är kontrollerat med två separata native appinstanser på en fysisk Mac:
lobby, gästanslutning, egna frågor, paus, frånkoppling, köat svar, värdomstart och gästomstart.
Ett separat test på två fysiska Macar över Wi-Fi återstår.

ZIP-integritet, appsignatur och paketerad frågebank är kontrollerade.
Kontrollsumma (SHA-256):

```text
d70593c9ac797347d306f4e9cdc3ebeebc5b967dbc972c08541f0f45f9bfa7fc  Niva-Land-Lokal-0.12.2-arm64.zip
```

[Läs hela installations- och LAN-guiden](https://github.com/allbinbjurstrom/niva-land-releases/releases/download/v0.12.2/Las-mig.txt)
