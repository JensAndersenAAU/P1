README-fil til det medf�lgende c-program til automatisk highlight og chatfiltrering i af en Twitch Chat

// �ndringer i c-programmet //
I cprogrammet er der mulighed for at �ndre f�lgende v�rdier:
	MIN_SIMIL: Bestemmer hvor striks chat filtreringen skal v�re (Double v�rdi fra 0 - 1)
	HIGHLIGHT_THRESHOLD: Er multiplikatoren for hvorn�r der vurderes der er highlight (Heltal)
	STARTHOUR: Start timen til en chatlog
	STARMIN: Start minuttet til en chatlog
	STARTSEC: Start sekundet til en chatlog


// Overs�ttelse af programmet //
Programmet overs�ttes med 'gcc chatbot.c' ved at bruge en GNU compiler 


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

	Under denne indstilling vil du f�rst blive promptet for hvilken chatfil der skal anvendes
	(1) Nuv�rende chatfil (Bruger chatfilen fra den sidste livechat)
	(2) V�lg en anden fil (V�lg selv en chatfil)

	Efter chatfil valg promptes en ny undermenu
	(1) Emotemenu (Muligheden for at v�lge emotes til emote streaks og highlights)
	(2) S�g chat (S�g efter brugere eller chatbeskeder fra chatten)
	(3) Vis sp�rgsm�l (Viser alle sp�rgsm�l stillet i den chatfil)
	(4) Vis highlights (Viser alle de steder, hvor der er fundet highlights)
	(5) Filtrer chat (Viser hele chatten filtreret)
	(6) G� tilbage til hovedmenuen 

Sidste hovedmenu mulighed er 
3. G� live

	Dette vil starte streamchatten i realtid, hvor emotestreaks, highlights og sp�rgsm�ls ogs� vises


Under b�de live indstillinger og offline indstillinger er der en emotemenu
Funktioner i emotemenuen:

	(1) Slet alle nuv�rende emotes og tilf�j nye
	(2) Tilf�j nye emotes uden at slette de forrige
	(3) G�r emotes til standard emotes (Kan findes i standard_emotes.txt)
	(4) Viser hvilke emotes er standard emotes
	(5) Viser de nuv�rende valgte emotes
	(6) G� tilbage til undermenu

// Udarbejdet af gruppe A408b december 2017 //