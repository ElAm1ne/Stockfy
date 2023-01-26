Ce projet a été developpé en utilisant le framework <b>Angular</b>, ce frontend est rattaché au Backend de ce repository : <p><a href="https://github.com/ElAm1ne/ProjectStock" target="_blank"><strong>https://github.com/ElAm1ne/ProjectStock</strong></a></p>

Vous pouvez consulter le site sur ce lien : <p><a href="https://stockfi.netlify.app/" target="_blank"><strong>https://stockfi.netlify.app/</strong></a></p>
ou celui ci :
<p><a href="https://lemon-island-0a1844610.2.azurestaticapps.net" target="_blank"><strong>https://lemon-island-0a1844610.2.azurestaticapps.net</strong></a></p>

Le projet a été developpé en <b>CI-CD</b> en utilisant <b>GitHub Actions</b> et l'intégration de <b>Azure</b> sous forme de <b>Static Web App</b>, un script de deploiement sur GitHub Actions permet le build, test, compression des fichiers Node et Deploiement sur Azure.

Au vu du nom de site "un peu moche" proposé par Azure et l'impossibilité de choisir un nom de domaine personnalisé sur la version étudiante, nous avons opté à l'utilisation d'un service appelé <b>Netlify</b> qui permet le deploiement automatique depuis GitHub après chaque commit vers un site de la forme : https://nomdedomaine.netlify.app. <b>Cette outil est puissant car il repose sur la technologie serverless qui permet de scalé infiniment sans retard et surtout permet le paiement à la requête au lieu d'une execution continue du serveur sur une instance cloud malgré le faible traffic !</b>
