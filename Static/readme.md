Staatinen asennus.
Kolme reititintä kulkevat kuin jonona, mutta lisäsin kolmisen välissä on yhteys. Tämä voi olla vähäsen fyysisempi konfigurointi.

![Alt text](images/image1.PNG?raw=true "None")

IP route, kolmen routerin yhteys mistäkin ja jne. Tämä menee kuin (Next-Hop Static Route)
![Alt text](images/image2.PNG?raw=true "None")

Vaihtoehtoinen konfigurointi tapa, jos ei tunnista tai muista routerin vastapäässä oleva ip-osoite
![Alt text](images/image2-1.PNG?raw=true "None")

Default static route & mitä periaatteessa vastaanottaa kaikki melkee, ja mihinkin asti se routerin vastapäässä oleva ip-osoite

![Alt text](images/image2-2.PNG?raw=true "None")


Jos yksi kolmesta menee poikki, ping viesti kulkeutuu toisen reittin kautta. (pun johto) se on serial kaapeli
![Alt text](images/image3.PNG?raw=true "None")

Reititimen R1 ja R3 yhteys kongifurointi
Koska edellisen yhteys kulkeutu R1 <--> R2 <--> R3, nyt jos jokin menee poikki voidaan kulkea mistä tahanssa, kunhan yhteys on oikein


![Alt text](images/image4.PNG?raw=true "None")

