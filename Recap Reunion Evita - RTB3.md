xmos - qualite 
nbi- distribution de num entre operateurs

sipcan - selenium - end to end (vad dtmf)
sig - signalisaition - tcp
media - traffic reseau - udp clair/chiffre
volume du test si vol = 0
acces diod

voip sip

jmeter audacity
preparer quesiton jerome et poins avec lui


+xmos - qualite 
nbi- distribution de num entre operateurs

sipcan - selenium - end to end (vad dtmf)
sig - signalisaition - tcp
media - traffic reseau - udp clair/chiffre
volume du test si vol = 0

voip sip
HAR



EVITA :

Pacours 3900		-   ✔   -    SIPCAN + selenium
vérifier le changement de l'offre au svi
Parcours SELFCARE	-   ✔   -    SIPCAN
Pacours EANH		-   ✔   -    SIPCAN + Selenium

Parcours CCB		-   ~~   -    SIPCAN + Selenium
Parcours CTC (jmeter)	-   ❌   -    HTTP + domino + SIPCAN
Parcours RDC (jmeter)	-   ❌   -    HTTP + domino
Parcours MD		-   ❌   -



record puis recup record de la sipcan -> a8k set changement pour "changement offre"
numero court -> surcharge proxy + uri special
usager_mos -> nom des enregistrement
curl pour fichiers audio de ref
multi instance -> generic et credentials param dans centreon avec les tirets pour
Selenium -> set network, unsecure yes, tester via ton pc direct, contains text
wait until success pour stabiliser 
consonle $x(" xpath avec '' ") si pas id ou id generic alors autre method
chropath add on
scenario complex pas de steps pour la voix
faire scenario pour recup .wav et le mettre en ref
pour le oui non il faut le metre ne .a8k pour interagir avec la sipcan

service - services by host : evita
	- sercices enable etc pending


service service by host

pollers expoert poller choose centreon et ensuis cocher 2 case en plus en dessous et enfin export reload

-b all -i pg101 -i pg102 -i pg103 -i pg104 -i pg105 -i pg106 --vendor evita --script=POC_SVI_ADA.robot

curl -k -H "Content-type: audio/vnd.wave" --data-binary @- https://pesqserv.rp-ntk.apps.ocn.infra.ftgroup/cgi-bin/pesq.cgi\?upload\=accueil_self.wav < accueil_self.wav


