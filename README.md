# Statistička analiza uticaja spavanja, kafe i ekrana na produktivnost i raspoloženje

## Opis projekta

Ovaj projekat ispituje kako faktori poput spavanja, unosa kofeina, vremena provedenog ispred ekrana i fizičke aktivnosti utiču na produktivnost, raspoloženje i nivo stresa kod pojedinaca.
Analiza je izvedena korišćenjem podataka iz fajla sleep_cycle_productivity.csv.

## Cilj
	•	Utvrditi povezanost između navika spavanja i radne produktivnosti
	•	Ispitati uticaj kofeina i ekrana na raspoloženje i stres
	•	Primeniti parametarske i neparametarske statističke testove
	•	Prikazati rezultate kroz grafičke vizualizacije (box plot, histogram, violin plot, kontingentne tabele)

## Dataset

Dataset sadrži sledeće grupe podataka:
	•	Demografija: Age, Gender
	•	Spavanje: Sleep Start Time, Sleep End Time, Total Sleep Hours, Sleep Quality
	•	Životni stil: Exercise (mins/day), Caffeine Intake (mg), Screen Time Before Bed (mins), Work Hours (hrs/day)
	•	Ishodi: Productivity Score, Mood Score, Stress Level

Ukupno: oko 8000 zapisa i 14 kolona.
Svaka opservacija predstavlja jednog ispitanika u jednom danu.

## Korišćene biblioteke
	•	pandas, numpy – obrada podataka
	•	matplotlib – vizualizacija
	•	scipy.stats – statistički testovi (t-test, ANOVA, Mann-Whitney, Kruskal-Wallis, Chi-kvadrat)

## Analitičke sekcije
	1.	Eksploratorna analiza (EDA) – opisne statistike i distribucije
	2.	Parametarski testovi – t-test i ANOVA
	3.	Neparametarski testovi – Mann-Whitney, Kruskal-Wallis
	4.	Chi-kvadrat test – povezanost kategorijskih varijabli
	5.	Vizualizacija – box plotovi, violin plotovi, kontingentne tabele

## Rezultati (primeri)
	•	Više sati sna i bolji kvalitet spavanja povezani su sa višim skorom produktivnosti
	•	Prekomerno vreme pred ekranom povezano je sa višim nivoom stresa
	•	Umeren unos kofeina povezan je sa boljim raspoloženjem
