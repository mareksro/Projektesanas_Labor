# Projektēšanas laboratorija
<h3>Preču piegādes maršrutēšana</h1>
<b>Risinājumu pārskats</b>
  – Līdzīgi tehniskie risinājumi<br>
    • Atrast un izvērtēt līdzīgos risinājums<br>
    • Aprakstīt līdzīgos risinājumus<br>
    • Apkopot novērojumus tabulā<br>
  – Iepazīties ar intelektisko algoritmu<br>
<br>

| Uzņēmums  | algoritms | Funkcionalitāte | Priekšrocības | Trūkumi |
| ------------- | ------------- | -------------  | -------------  | -------------  |
| Google maps  | Dijkstra, VRP | Īsākā maršruta atrašana līdz galamērķim ņemot vērā satiksmi| Ar VRP palīdzību tiek minimizēts veicamo pagriezienu skaits krustojumos | |
| Waze  | Dijkstra | Aprēķina īsāko ceļu no lietotāja atrašanās vietas līdz galamērķim | | |
| Wolt  | GDM (google distance matrix API) | Algoritms ņem vērā ātrāko veidu kā nokļūt līdz izvēlētajam galamērķim ņemot vērā ceļā pavadīto laiku līdz tam no vairākam lokācijām | Efektīva apstrāde izmantojot parallel computing | Izmanto salīdzinoši lielus RAM resursus|
| Routific | Bees Algorithm | Algoritms balstās uz paralēlo algoritma implementāciju (vairākas zonas tiek analizētas vienlaicīgi) | Vienkāršība un smalkas izpētes iespējas savstarpēji līdzīgiem objektiem  | Nav optimāls plašu teritoriju analizēšanai, liela pašizmaksa |
| DHL | Ant Colony Optimization |  | Efektīvs sarežģītu optimizācijas problēmu risināšanā, kā arī dinamiski pielāgojas mainīgiem apstākļiem. | Lēns konverģences ātrums sarežģītos gadījumos un heuristiska metode, kas nenodrošina garantētu optimālu risinājumu. |
| Omniva  | QR, svītru kodi, CTS (Courier tracking systems) | Skeneri nolasa kodus dažādos kontrolpunktos piegādes maršrutā, atjauninot sistēmu ar atrašanās vietas un statusa datiem.| | |

 <h6><em>"Sometimes Google has better traffic data, I assume because they grab location data from every android device, while Waze only uses data from active Waze App users. On routes where many Wazers travel, I find the Waze data to be very percise, ETA times barely differ. Waze foruma ieraksts: https://www.waze.com/forum/viewtopic.php?t=218943"<br>

 <br> "Ant-colony optimization algorithm-based programs have helped companies like DHL identify cost savings in the ground logistic network for supply chain transportation analysts. Publications show that the program has helped the company save millions of dollars annually and increase its profits by more than 15% compared with previous processes."</em></h6>
