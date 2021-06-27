<H1>DIABETE DETECTOR</H1> (training project)
<p>This application allows to add/read/update patients. Foreach patient, notes can be added/read/updated. Then a report can be generated to see if a patient is at risk of developping diabete.
<p>This project contains three API and an Angular frontend : 
<ul>
<li>API Patient : <a href="https://github.com/Helloz18/P9-patient"> repository</a></li>
<li>API History : <a href="https://github.com/Helloz18/P9-history"> repository</a></li>
<li>API Report : <a href="https://github.com/Helloz18/P9-report"> repository</a></li>
<li>frontend diabetedectorui : <a href="https://github.com/Helloz18/P9-diabetedetectorui"> repository</a></li>
</ul>
</p>
<p>A Docker compose is set to generate a docker container with all parts of this application.</p>
<p>First make sure your Docker environment is ready.
<P>You need to get all repositories of this project and group them in the diabetedetector folder. You can create docker image foreach repository (follow information displayed in each readme file).
<P>
 Then go to the diabetedetector folder and type in a terminal : <b>docker-compose up</b>
<P>
Once everything is launched you can open your application at this address : <b>localhost:5002</b>
</p>
