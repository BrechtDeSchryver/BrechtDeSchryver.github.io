## Rapport van de IATAAK
### Auteurs:
 - [Brecht De Schryver]
### Inhoudsopgave:
 - [Inleiding](#inleiding)
 - [Uitvoering](#uitvoering)
 - [Resultaten](#resultaten)
 - [Conclusie](#conclusie)
### Inleiding
In dit rapport wordt de uitvoering van de IATAAK beschreven. voor deze taak maakte ik gebruik van het dataportaal van stad gent. Ik nam een kijkje naar de data van real time beztting van parkeergarages in Gent
### Uitvoering
1.1
 - tijdens dit deel werd de data gescraped
[bash script](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/scripts/webscraper.sh)

1.2
 - tijdens dit deel werd de data getransformeerd
[bash script](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/scripts/transform.sh)

 - dit genereerd een SC2001 warning die niet valt op te lossen omdat de sed code te complex is zie [hier](https://www.shellcheck.net/wiki/SC2001)

1.3
 - tijdens dit deel werd de data gevisualiseerd
[python script](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/scripts/analyse.py)

1.4
 - tijdens dit deel werd de data mooi opgemaakt
[python script](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/scripts/report.py)

1.5
 - tijdens dit deel werd het gehele process geautomatiseerd
gegeven dat je alle scripts op de juiste plaats hebt staan en in de code deze gelinkt hebt + je toegang hebt tot de github repo kan je dit script uitvoeren
dit vult elke 5 min de csv files aan en elk uur maakt hij nieuwe raporten die hij dan commit op github
[bash script setup](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/scripts/setup.sh)
[bash script automatic run](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/scripts/automated.sh)
### Resultaten
## grafiek van Savaanstraat
Quisquam voluptatem tempora consectetur. Aliquam eius labore modi dolorem. Dolorem magnam eius voluptatem. Dolore etincidunt porro neque quiquia labore numquam. Quisquam quaerat etincidunt quaerat labore consectetur etincidunt neque.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Savaanstraat.csv.png)
## grafiek van gemiddelde
Aliquam dolor quiquia velit ipsum ut. Quaerat aliquam modi dolorem quisquam modi eius. Quisquam non quaerat neque etincidunt porro. Dolorem porro eius non aliquam aliquam. Sit quiquia etincidunt voluptatem sed adipisci dolor. Sit ut quisquam consectetur ut quiquia ipsum dolorem. Sed velit sed neque tempora labore.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/gemiddelde.csv.png)
## grafiek van Sint-Michiels
Dolore sed porro velit quaerat dolore amet consectetur. Etincidunt quiquia sit voluptatem porro voluptatem. Est numquam magnam aliquam. Magnam modi quiquia etincidunt voluptatem ipsum labore. Quaerat etincidunt numquam sed dolor dolorem eius. Ipsum non dolorem tempora. Non ipsum sed dolorem sit non numquam. Dolore sit etincidunt aliquam labore. Quaerat adipisci quaerat labore sit sed. Quaerat dolorem quiquia numquam adipisci neque.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Sint-Michiels.csv.png)
## grafiek van Ledeberg
Est modi amet aliquam non quaerat consectetur modi. Labore consectetur tempora modi ut modi. Dolorem voluptatem etincidunt dolore sit quaerat numquam numquam. Aliquam sit adipisci neque adipisci. Sed ipsum sit non labore.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Ledeberg.csv.png)
## grafiek van Reep
Voluptatem ut ipsum aliquam quiquia quiquia etincidunt porro. Non voluptatem dolorem ipsum dolor numquam. Quaerat quiquia adipisci consectetur. Velit amet quiquia dolore sed. Sed ut numquam dolore etincidunt eius. Modi neque dolor amet aliquam dolor. Sit consectetur modi porro neque.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Reep.csv.png)
## grafiek van B-Park_Dampoort
Sed est non quaerat quaerat voluptatem ut dolore. Aliquam amet voluptatem consectetur neque quiquia adipisci amet. Velit dolore labore adipisci dolorem adipisci. Velit labore est numquam dolorem. Ipsum dolorem sit ipsum aliquam. Est consectetur dolor quisquam non. Dolor labore sed velit eius numquam. Non dolorem dolore non modi etincidunt voluptatem neque.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/B-Park_Dampoort.csv.png)
## grafiek van Ramen
Dolorem tempora ut sit labore magnam amet. Aliquam voluptatem tempora sed neque quaerat aliquam. Aliquam consectetur modi sed. Aliquam magnam sit eius. Quaerat velit non labore dolorem. Non labore dolor dolor ut quiquia quaerat. Labore labore magnam modi eius quisquam tempora neque. Eius sit adipisci dolore aliquam etincidunt ipsum sed. Ipsum tempora labore labore. Amet eius non dolore voluptatem sed quiquia labore.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Ramen.csv.png)
## grafiek van B-Park_Gent_Sint-Pieters
Labore non quaerat etincidunt etincidunt neque dolor ut. Quisquam ut porro eius quiquia quisquam tempora voluptatem. Ipsum adipisci eius dolor est velit magnam. Dolorem velit aliquam quaerat velit consectetur. Dolor eius sit non porro tempora porro consectetur.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/B-Park_Gent_Sint-Pieters.csv.png)
## grafiek van Sint-Pietersplein
Quaerat dolor modi voluptatem amet dolore porro. Sed magnam sit velit eius dolor. Eius ipsum voluptatem quaerat magnam dolorem dolor velit. Aliquam adipisci quaerat ipsum voluptatem tempora adipisci. Est eius dolorem consectetur quisquam est sed dolorem. Quaerat consectetur ipsum velit ipsum dolor. Consectetur dolorem dolore sed consectetur non est magnam.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Sint-Pietersplein.csv.png)
## grafiek van Dok_noord
Modi dolore dolor ipsum neque sit. Tempora non porro tempora. Dolore quisquam quisquam quiquia quaerat voluptatem. Neque quaerat neque tempora velit sed numquam quiquia. Modi aliquam dolore tempora. Magnam quisquam eius eius aliquam magnam. Eius quaerat quisquam dolore sed. Neque neque amet aliquam. Eius voluptatem quiquia consectetur dolor. Aliquam aliquam est ut adipisci porro.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Dok_noord.csv.png)
## grafiek van Getouw
Velit non neque sed dolore labore dolor. Etincidunt dolore ipsum est aliquam quaerat modi dolor. Voluptatem sit numquam eius quaerat dolore voluptatem quisquam. Etincidunt labore magnam velit eius dolorem magnam porro. Modi neque sed numquam consectetur dolor. Aliquam amet tempora sit numquam velit dolore.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Getouw.csv.png)
## grafiek van Vrijdagmarkt
Non aliquam dolor dolore porro quiquia est aliquam. Quisquam porro ipsum etincidunt magnam ut quiquia. Adipisci non non velit labore velit dolorem. Voluptatem magnam sed labore dolorem sed sed. Etincidunt voluptatem quisquam etincidunt. Adipisci eius sit etincidunt labore est consectetur amet. Ipsum consectetur etincidunt quisquam.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Vrijdagmarkt.csv.png)
## grafiek van Tolhuis
Voluptatem quaerat dolorem dolore ipsum. Est dolor aliquam dolore dolorem quaerat etincidunt magnam. Etincidunt eius dolorem sed. Neque est adipisci neque dolor. Sit consectetur quisquam numquam sit modi. Velit sit sed non quiquia quisquam. Quisquam ut sed aliquam sit quaerat. Etincidunt quaerat etincidunt velit adipisci consectetur amet adipisci. Labore consectetur porro labore. Sit adipisci neque eius.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Tolhuis.csv.png)
## grafiek van totaal
Sit sit porro est modi neque eius. Consectetur labore etincidunt tempora velit ipsum. Eius ipsum amet porro dolorem quisquam labore. Magnam non magnam eius ut modi dolorem. Magnam labore adipisci sit ut est ipsum consectetur. Aliquam neque voluptatem eius. Aliquam numquam modi consectetur etincidunt dolor.
