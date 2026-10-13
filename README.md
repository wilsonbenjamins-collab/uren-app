# Uren

Schermen van de Mac-app Uren (urenregistratie met agenda en AFAS-weekrapport).

De app haalt `index.html` hier automatisch op. Een nieuwe versie uitrollen:

1. Verhoog in `index.html` de regel `<meta name="uren-web-version" content="JJJJ.MM.DD.n">`.
2. Heeft de pagina een nieuwere app nodig, verhoog dan ook `uren-min-app`.
3. Commit en push naar `main`. Apps pakken het binnen 6 uur op, of direct via Instellingen > Koppelingen > Nu controleren.

Er staan hier geen uren, agenda's of andere persoonlijke gegevens; die blijven lokaal op de Mac.
