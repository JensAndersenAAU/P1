README-fil til program med automatisk highlight og chatfiltrering i en Twitch Chat

// Overs�ttelse af programmet //
Programmet overs�ttes med 'gcc chatanalyser.c' ved at bruge en GNU compiler 


// Her vil menu funktionerne beskrives //
Programmet kan derefter k�res og man vil blive promptet til en hovedmenu med tre muligheder
Den f�rste mulighed er:

1. Live chat indstillinger
	
	Under denne indstilling bliver du promptet for en undermenu med forskellige muligheder
	(1) Emotemenu (Muligheden for at v�lge emotes til emote streaks og highlights)
	(2) Gem chatten til en fil (Redigere hvilken fil chatten gemmes til, standard = dato)
	(3) Kun sp�rgsm�l (Programmet vil kun vise sp�rgsm�l sendt i chatten)
	(4) Kun highlight (Programmet vil kun vise tidspunkter, hvor der er et highlight)
	(5) Vi sp�rgsm�l og highlights (Programmet viser p� highlights og sp�rgsm�l) 
	(6) G� tilbage til hovedmenuen

Den anden mulighed i hovedmenuen er:
2. Offline indstillinger

	Under denne indstilling vil du f�rst blive promptet for hvilken chatfil skal bruges
	(1) Nuv�rende chatfil (Bruger chatfilen fra den sidste livechat)
	(2) V�lg en anden fil (V�lg selv en chatfil)

	Efter chatfil valg promptes en ny undermenu
	(1) Emotemenu (Muligheden for at v�lge emotes til emote streaks og highlights)
	(2) S�g chat (S�g efter brugere eller chatbeskeder fra chatten)
	(3) Vis sp�rgsm�l (Viser alle sp�rgsm�l stillet i den chatfil)
	(4) Vis highlights (Viser alle de steder, hvor der er fundet highlights)
	(5) Filtrer chat (Viser chatten filtreret)
	(6) G� tilbage til hovedmenuen 

Sidste hovedmenu mulighed er 
3. G� live

	Dette vil starte streamchatten i realtid, hvor emotestreaks, highlights og sp�rgsm�ls ogs� vises



Under b�de live indstillinger og offline indstillinger er der en emotemenu
I emotemenuen promptes man for:

(1) Slet alle nuv�rende emotes og tilf�j nye
(2) Tilf�j nye emotes uden at slette de forrige
(3) G�r emotes til standard emotes fra standard_emotes.txt
(4) Viser hvilke emotes er standard emotes
(5) Viser de nuv�rende valgte emotes
(6) Tilbage til undermenu

// Udarbejdet af gruppe A408b //