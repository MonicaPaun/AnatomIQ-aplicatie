🧠 AnatomIQ – Platformă Educațională Interactivă de Anatomie
AnatomIQ este o platformă educațională creată pentru a transforma învățarea anatomiei într-o experiență captivantă, vizuală și logică. Se adresează elevilor, studenților, profesorilor și tuturor pasionaților de știință care vor să exploreze corpul uman într-un mod modern și clar.

🔍 Ce oferă AnatomIQ
Modele 3D interactive

Atlase și manuale verificate

Informații structurate schematic

Galerie vizuală și materiale multimedia

BioBot – chatbot educațional pentru suport rapid

Teste și quiz-uri pentru autoevaluare

Pagină de notițe

Noutăți medicale

Comunitate în dezvoltare

⚙️ Instalare locală
Clonează repository-ul:

bash
Copy
Edit
git clone https://github.com/utilizatorul-tau/anatomiq.git
cd anatomiq
Instalează dependențele (asigură-te că ai instalat Node.js – versiunea 14 sau mai nou):

nginx
Copy
Edit
npm install
sau

nginx
Copy
Edit
yarn install
💬 Activarea chatbot-ului BioBot
AnatomIQ include un chatbot educațional integrat, care funcționează cu Dialogflow de la Google.
Pentru ca acesta să funcționeze, trebuie să generezi propriul API key.

Pași pentru a obține un API key de la Google:
Accesează Google Cloud Console

Creează un nou proiect (sau selectează unul existent)

Activează „Dialogflow API”:

Mergi la API & Services > Library

Caută „Dialogflow API” și apasă Enable

Creează un API key:

Mergi la API & Services > Credentials

Apasă Create Credentials > API key

Copiază cheia generată

Creează un fișier .env în directorul principal al proiectului și adaugă următoarea linie:

ini
Copy
Edit
REACT_APP_CHATBOT_API_KEY=cheia-ta-aici
Nu publica această cheie online. Este personală și poate fi folosită abuziv.

▶️ Rulare aplicație local
După ce ai configurat totul, pornește aplicația:

sql
Copy
Edit
npm start
sau

sql
Copy
Edit
yarn start
Aplicația va fi disponibilă la: http://localhost:3000

🧪 Testare
Funcționalitatea chatbotului poate fi testată în aplicație, în secțiunea „BioBot”.
De asemenea, poți verifica quiz-urile, materialele vizuale și restul funcționalităților educaționale.

🛠️ Tehnologii folosite
HTML, CSS, JavaScript

React.js

Dialogflow API (Google Cloud)

GitHub Pages (pentru hosting – dacă este cazul)

👥 Echipa proiectului
Păun Monica-Georgiana

Treantă Daria Mihaela

Coordonator: Măres Mădalina

Unitate de învățământ: Colegiul Național "Tudor Vladimirescu", București

📧 Contact: anatomiq2025@gmail.com

📄 Licență
Acest proiect este destinat exclusiv utilizării educaționale.
Pentru folosirea, adaptarea sau redistribuirea lui în alte scopuri, vă rugăm să ne contactați în prealabil.

💡 Contribuții
Orice feedback, sugestie sau contribuție este binevenită.
Dacă îți place proiectul, nu uita să îi dai ⭐ pe GitHub!

„Studiul nu trebuie să fie o corvoadă. Trebuie să fie clar, vizual și captivant.” – Echipa AnatomIQ
