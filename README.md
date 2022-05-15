# Cloud-Computing-Back

Introducere:

Aplicatia construita doreste sa creeze un portal web pentru useri, astfel acestia pot trimite, prin intermediul unui formular mesaje(traduse in multe limbi) catre adresa de mail a unei persoane. 

Descriere problema:

Aplicatia este una web, folosind react pentru partea de front-end, node.js si javascript pe partea de back-end. Se folosesc api-uri precum: translate API, Sendgrid, Heroku(pentru deply). Aplicatia de fata prezinta o pagina web realizata pentru useri, care, acestia in urma completarii unui formular, reusesc sa trimita mesaje, traduse in mai multe limbi, catre mail-ul unei persoane dorite. De asemenea se foloseste o baza de date locala MySql cat si google cloud pentru o conexiune cloud a aplicatiei.

Descriere API:

Translate Api(Translation AI) - Un API care poate traducre in mod dinamic text intre mii de perechi de limbi. Traducrea permite site-urilor web si programelor sa integreze programatic serviciul de traducere.

SendGrid - Conectorul Sendgrid permite sa trimitem e-mailuri si sa interactionam direct cu fluxuri de mail-uri. Putem de asemenea sa trimitem mail-uri individuale, de tip bloc.

Fluxuri de date:

1. Creare parte back-end (set-up back-end local, setup cloud storage/mysql, 
definire/creare rute, initializare translate API/sendgrid API)
2. Creare parte front-end (set-up front end local -> utilizare react)
3. Deploy aplicatie(Heroku)
4. Exemple de request / response + metode HTTP

![image](https://user-images.githubusercontent.com/64654536/168485358-3f6ebcf2-97cb-4dcb-be9a-150288b2d909.png)
![image](https://user-images.githubusercontent.com/64654536/168485361-7b73327b-b2e4-4db4-abc9-6fdfa4b843b0.png)

5.	Autentificare și autorizare servicii utilizate (dacă este cazul)
-Heroku:
![image](https://user-images.githubusercontent.com/64654536/168485370-361c3702-1775-4fc7-9837-c75ab5204273.png)


Capturi de ecran:
![image](https://user-images.githubusercontent.com/64654536/168339878-c6976c69-c1b1-492b-91b3-c896423c9ace.png)
![image](https://user-images.githubusercontent.com/64654536/168339925-0831fb70-f5dc-4367-a163-b2e8d1ddd861.png)


DEMO LINK: https://youtu.be/Xs4gAmvCYcQ

Heroku Deploy Link: https://dashboard.heroku.com/apps/infinite-brushlands-03970
