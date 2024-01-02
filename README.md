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

**[Proiect PCLP3 -- NOANbot]{.underline}**

**[(VLADISLAV NORIS-VICTOR & NEACȘU ANDREI-GEORGIAN)]{.underline}**

**[GRUPA 424D]{.underline}**

CUPRINS:

> 1.ReadMe\
> 2.Obținere API key\
> 3.Dovadă funcționalitate program NOANbot\
> 4.Dovadă funcționalitate program NOANbot_GUI 5.Probleme întâmpinate\
> 6.Link ChatGPT & github\
> 7.Bibliografie

-1-

**[README pentru Interfața NOANbot]{.underline}**

Această documentație oferă o prezentare a codului NOANbot Interface, o
interfață simplă pentru interacțiunea cu modelul OpenAI GPT-3.5 Turbo
prin intermediul API-ului OpenAI, folosind Tkinter pentru interfața
grafică.

***#DESCRIERE GENERALĂ***

NOANbot Interface permite utilizatorilor să comunice cu modelul OpenAI
GPT-3.5 Turbo, introducând mesaje de text într-o interfață grafică
bazată pe Tkinter. Istoricul conversației este stocat, iar fiecare
interacțiune cu modelul este afișată într-un format de chat.

***#CERINȚE DE SISTEM***

Înainte de a rula codul, asigurați-vă că aveți:

Python 3.x: Versiunea 3.x a limbajului de programare Python este
necesară pentru a executa codul.

***#BIBLIOTECI PYTHON***

Tkinter: Tkinter este o bibliotecă standard Python utilizată pentru
crearea interfețelor grafice.

OpenAI GPT-3.5 Turbo: Acest cod utilizează serviciul GPT-3.5 Turbo
oferit de OpenAI. Asigurați-vă că aveți acces la API-ul OpenAI și că ați
configurat cheia API corespunzătoare.

***#INSTALARE***

Copiați codul într-un fișier Python.

Configurați cheia API OpenAI înlocuind șirul de caractere \"API KEY\" în
openai.api_key = \"API KEY\" cu cheia API reală.

-2-

***#UTILIZARE***\
Rulați scriptul după configurarea cheii API OpenAI.

Fereastra GUI va apărea cu o zonă de text pentru afișarea conversației
și o zonă de introducere pentru trimiterea mesajelor către NOANbot.

Tastați întrebarea în zona de introducere și faceți clic pe butonul
\"→\" pentru a trimite mesajul.

Răspunsul NOANbot va fi afișat în zona de conversație.

***#STRUCTURA CODULUI***\
Clasa NOANbotInterface administrează GUI Tkinter și gestionează
interacțiunile utilizatorului.

Metoda send_message trimite inputul utilizatorului la modelul OpenAI
GPT-3.5 Turbo și afișează răspunsurile în zona de conversație.

Metoda display_message formatează și afișează mesajele în fereastra de
chat.

***#NOTE***\
Asigurați-vă că cheia API OpenAI este păstrată confidențial și nu este
distribuită public.

Acest cod este un exemplu de bază și poate fi extins pentru cazuri de
utilizare mai complexe sau integrate în alte aplicații.

-3-

**[OBȚINERE API KEY]{.underline}**

Accesând site-ul ys avem\
posibilitatea de a genera o cheie secretă API, cu ajutorul căreia vom
executa programul. Astfel, se va realiza dialogul între utilizator și
NAONbot cu succes.

Cheia API (Application Programming Interface) este necesară pentru
autentificarea și autorizarea accesului la serviciul OpenAI, în acest
caz, la modelul GPT-3.5 Turbo. Pentru a utiliza serviciile oferite de
OpenAI, trebuie să ave o cheie API validă.

Cheia API servește drept mijloc de identificare, permitând OpenAI să
urmărească și să gestioneze utilizarea serviciului lor. De asemenea,
ajută la asigurarea securității și controlului asupra accesului la
resursele computaționale oferite de OpenAI pentru execuția modelelor lor
de limbaj, cum ar fi GPT-3.5 Turbo.

  ---------------------------------------------------------------------------------------------
  ![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image1.png){width="5.868055555555555in"
  height="3.6708333333333334in"}
  ---------------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------------------

*[Screen capture -- Site OpenAI/API keys]{.underline}*

-4-

**[Dovadă funcționalitate program NOANbot]{.underline}**

După ce executați programul \"NOANbot.py\", localizat în fișier, veți
putea iniția un dialog interactiv în terminal între utilizator și
NOANbot. Această conversație va continua până când introduceți textul
\"quit\", moment în care programul se va încheia corespunzător.

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image2.png){width="5.861111111111111in"
height="3.6819444444444445in"}

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image3.png){width="5.861111111111111in"
height="3.6638888888888888in"}

-5-

**[Observație:]{.underline}**

Manipulând codul și schimbând rolul asistentului:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image4.png){width="6.522222222222222in"
height="1.3319444444444444in"}

vom primi răspunsuri diferite pentru aceleași întrebări formulate mai
sus. Aceste răspunsuri vor fi evident într-un ton sarcastic, adăugând un
element de umor sau ironie la interacțiunea cu asistentul:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image5.png){width="6.268055555555556in"
height="3.9430544619422574in"}

\*Există o varietate mare de roluri pe care le putem atribui botului,
fie că este vorba despre asistență virtuală, facilitarea dialogului,
furnizarea informațiilor sau orice altă funcționalitate specifică
necesităților utilizatorului. Flexibilitatea acestor roluri permite
adaptabilitatea și personalizarea experienței oferite de bot în funcție
de contextul și scopul utilizării sale.

-6-

**[Dovadă funcționalitate program NOANbot_GUI]{.underline}**\
După ce executați programul **NOANbotInterface**, veți vedea o fereastră
de interfață grafică (GUI) care vă permite să introduceți întrebări și
să primiți răspunsuri de la bot. Aici este un exemplu reprezentativ al
functionalitatii programului:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image6.png){width="5.801388888888889in"
height="3.6333333333333333in"}

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image7.png){width="5.8069444444444445in"
height="3.6333333333333333in"}

-7-

**[Probleme intâmpinate]{.underline}**

În timpul rulării codului în mediul de dezvoltare VSCode pe sistemul de
operare Windows, a apărut următoarea eroare:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image8.png){width="6.758333333333334in"
height="2.3375in"}

*Am urmat sugestiile din terminal:*

Prima variantă nu a funcționat din cauza faptului că „migration CLI" nu
este încă suportată în sistemul de operare Windows:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image9.png){width="6.268055555555556in"
height="1.1402777777777777in"}

A doua variantă nu a funcționat din cauza unei erori survenite în cadrul
unui subproces:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image10.png){width="6.286111111111111in"
height="1.8916655730533682in"}

-8-

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image11.png){width="6.874998906386701in"
height="2.525in"}

Din cauza că nu am avut succes cu niciuna dintre variante, ne-am decis

> să instalăm Ubuntu pe o mașină virtuală (Oracle VM VirtualBox):
>
> ![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image12.png){width="6.625in"
> height="3.7291666666666665in"}

-9-

După instalarea a VSCODE in linux și executarea programului, am aflat că
modulul „pip" nu este instalat:

> ![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image13.png){width="6.6in"
> height="4.145833333333333in"}
>
> Dar odată cu încercarea instalării acestui modul am aflat că userul
> „vmbox" nu se află în soders file:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image14.png){width="6.663888888888889in"
height="1.3055555555555556in"}

-10-

> Am repornit mașina virtuală în modul de boot pentru a aplica noile
> setări și pentru a asigura o funcționare corespunzătoare a sistemului
> de operare:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image15.png){width="5.9875in"
height="4.129166666666666in"}

> Am optat pentru modul de recuperare și am ales accesul cu privilegii
> de administrator (root):
>
> ![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image16.png){width="5.425in"
> height="3.3944433508311462in"}

-11-

Ulterior, am adăugat utilizatorul în grupul sudo pentru a-i acorda
privilegii administrative. Această acțiune ne permite să utilizăm
comenzi cu privilegii de administrator prin intermediul comenzilor sudo,
contribuind astfel la eficiența și securitatea configurării sistemului:

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image17.png){width="6.268055555555556in"
height="4.905555555555556in"}

\*Atenție! Anumite imagini sunt preluate de pe internet, indicând astfel
utilizarea mai multor utilizatori. Rezolvarea problemei nu diferă și a
fost realizată pentru utilizatorul „vmbox".

-12-

**[Rate limit]{.underline}**

Când apelezi API-ul OpenAI în mod repetat, este posibil să întâlnești
mesaje de eroare care indică codul 429: \'Too Many Requests\' sau\
RateLimitError. Aceste mesaje de eroare apar atunci când se depășesc
limitele de rată ale API-ului.

**De ce există limite de rată?**

Limitele de rată reprezintă o practică obișnuită pentru API-uri și sunt
impuse din câteva motive diferite.

În primul rând, acestea contribuie la protejarea împotriva abuzului sau
utilizării neadecvate a API-ului. De exemplu, un actor malefic ar putea
să inunde API-ul cu cereri încercând să-l supraîncarce sau să provoace
întreruperi în serviciu. Prin stabilirea unor limite de rată, OpenAI
poate preveni astfel de activități nocive.

În al doilea rând, limitele de rată asigură că fiecare utilizator are
acces echitabil la API. Dacă o persoană sau organizație efectuează un
număr excesiv de cereri, ar putea încetini API-ul pentru toată lumea.
Prin limitarea numărului de cereri pe care un singur utilizator le poate
face, OpenAI se asigură că fiecare are oportunitatea de a utiliza API-ul
fără a întâmpina încetiniri.

În cele din urmă, limitele de rată pot ajuta OpenAI să gestioneze
încărcarea totală pe infrastructura sa. Dacă cererile către API cresc
drastic, ar putea suprasolicita serverele și provoca probleme de
performanță. Prin stabilirea limitelor de rată, OpenAI poate contribui
la menținerea unei experiențe fluide și consistente pentru toți
utilizatorii. Chiar dacă atingerea limitelor de rată poate fi
frustrantă, acestea există pentru a proteja\
funcționarea fiabilă a API-ului pentru toți utilizatorii săi.

**Limitele implicite de rată**

Limitele tale de rată și limita de cheltuieli (cota) sunt ajustate
automat în funcție de mai mulți factori. Pe măsură ce folosești API-ul
OpenAI și plătești cu succes factura, OpenAI crește automat nivelul de
utilizare.

-13-

**Exemplu vizual**

![](vertopal_bd26feb7e40f4f1d84d150530bd074da/media/image18.png){width="6.843055555555556in"
height="4.3027766841644794in"}

**Cum am reușit să evităm problema**\
Am evitat problema prin crearea de noi conturi OpenAI și monitorizarea
atentă a frecvenței de compilare a programului, astfel încât să nu
depășim limita de rată impusă de OpenAI.

-14-

**[Link ChatGPT]{.underline}**

6

**[Link github]{.underline}**

-15-

**[Bibliografi]{.underline}e**\
***1. How to Install vscode on Ubuntu***

***2. Installing OpenAI on Linux***

***3. User is not in the sudoers file***\
n

***4. Ubuntu new user login but username@ does not exist***

***5. How to use install modules on linux ubuntu?***

***6. How to Fix "Username is not in the sudoers file. This incident
will be reported" in Ubuntu***

***7. How do I install a Python module for use on Linux systems at
SEAS?***

-16-

***8. PIP Install OpenAI not working \-- Unable to locate Package***

***9. ChatGPT API keys***

-17-

