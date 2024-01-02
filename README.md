# PCLP3-ProiectFinal
#README pentru Interfața NOANbot

Această documentație oferă o prezentare a codului NOANbotInterface, o interfață simplă pentru interacțiunea cu modelul OpenAI GPT-3.5 Turbo prin intermediul API-ului OpenAI, folosind Tkinter pentru interfața grafică.

##DESCRIERE GENERALĂ

NOANbotInterface permite utilizatorilor să comunice cu modelul OpenAI GPT-3.5 Turbo, introducând mesaje de text într-o interfață grafică bazată pe Tkinter. Istoricul conversației este stocat, iar fiecare interacțiune cu modelul este afișată într-un format de chat.

##CERINȚE DE SISTEM

Înainte de a rula codul, asigurați-vă că aveți:
Python 3.x: Versiunea 3.x a limbajului de programare Python este necesară pentru a executa codul.

##BIBLIOTECI PYTHON
Tkinter: Tkinter este o bibliotecă standard Python utilizată pentru crearea interfețelor grafice.

OpenAI GPT-3.5 Turbo: Acest cod utilizează serviciul GPT-3.5 Turbo oferit de OpenAI. Asigurați-vă că aveți acces la API-ul OpenAI și că ați configurat cheia API corespunzătoare.

##INSTALARE

Copiați codul într-un fișier Python.
Configurați cheia API OpenAI înlocuind șirul de caractere "API KEY" în openai.api_key = "API KEY" cu cheia API reală.

##UTILIZARE

Rulați scriptul după configurarea cheii API OpenAI.
Fereastra GUI va apărea cu o zonă de text pentru afișarea conversației și o zonă de introducere pentru trimiterea mesajelor către NOANbot.
Tastați întrebarea în zona de introducere și faceți clic pe butonul "→" pentru a trimite mesajul.
Răspunsul NOANbot va fi afișat în zona de conversație.

##STRUCTURA CODULUI

Clasa NOANbotInterface administrează GUI Tkinter și gestionează interacțiunile utilizatorului.
Metoda send_message trimite inputul utilizatorului la modelul OpenAI GPT-3.5 Turbo și afișează răspunsurile în zona de conversație.
Metoda display_message formatează și afișează mesajele în fereastra de chat.

##NOTE
Asigurați-vă că cheia API OpenAI este păstrată confidențial și nu este distribuită public.
Acest cod este un exemplu de bază și poate fi extins pentru cazuri de utilizare mai complexe sau integrate în alte aplicații.
