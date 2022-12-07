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
Sit ut velit sed ut velit quiquia. Magnam adipisci est sit adipisci amet. Dolor etincidunt velit amet velit numquam etincidunt velit. Dolorem modi non dolore. Quisquam tempora aliquam quisquam est labore labore. Tempora adipisci dolore quisquam.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Savaanstraat.csv.png)
## grafiek van gemiddelde
Modi quiquia aliquam quiquia. Velit sit dolore modi est voluptatem dolorem neque. Adipisci modi quiquia tempora dolor dolore ipsum dolor. Adipisci numquam sit neque est quiquia non aliquam. Magnam neque labore non. Etincidunt modi porro sed aliquam tempora. Magnam modi numquam neque ut ipsum porro.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/gemiddelde.csv.png)
## grafiek van Sint-Michiels
Etincidunt porro quaerat non quisquam est. Sed sit consectetur voluptatem. Tempora magnam est quisquam consectetur est. Porro dolor numquam adipisci. Quisquam labore numquam sed aliquam. Velit est labore quaerat ipsum consectetur modi. Voluptatem numquam dolore est voluptatem sed adipisci. Dolorem quaerat sit sit quisquam non quiquia.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Sint-Michiels.csv.png)
## grafiek van Ledeberg
Labore adipisci sed aliquam quiquia neque eius est. Ipsum voluptatem neque velit labore quaerat dolorem dolore. Neque etincidunt dolore quiquia. Amet labore tempora neque. Dolorem magnam consectetur tempora etincidunt quiquia. Dolorem quisquam ipsum eius. Ipsum modi dolore velit dolor sit sit velit. Sit etincidunt magnam amet velit adipisci velit.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Ledeberg.csv.png)
## grafiek van Reep
Dolorem sit dolorem modi. Adipisci modi sit eius dolore velit voluptatem. Porro aliquam etincidunt porro quisquam porro modi. Voluptatem ut quaerat dolor modi est quisquam consectetur. Magnam quiquia ipsum neque etincidunt eius aliquam non. Aliquam amet numquam modi consectetur est. Velit neque sed aliquam. Eius voluptatem velit consectetur. Magnam labore ipsum adipisci. Voluptatem neque ipsum sed velit magnam voluptatem labore.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Reep.csv.png)
## grafiek van B-Park_Dampoort
Numquam sit neque ut neque. Quiquia etincidunt voluptatem neque ut numquam. Magnam etincidunt aliquam consectetur etincidunt quaerat tempora porro. Voluptatem dolore eius dolore quiquia. Porro adipisci labore quiquia etincidunt quaerat non ut. Dolor numquam adipisci eius. Porro consectetur velit voluptatem tempora sit velit. Etincidunt neque voluptatem ipsum sed quaerat numquam eius. Ipsum tempora sit tempora.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/B-Park_Dampoort.csv.png)
## grafiek van Ramen
Aliquam dolorem amet adipisci quisquam. Quisquam sed numquam ut aliquam. Labore consectetur amet labore sit neque amet. Dolorem est dolor quisquam quiquia eius magnam. Tempora sed quaerat modi. Aliquam porro dolor velit. Etincidunt numquam etincidunt sit numquam velit. Adipisci labore ut est tempora magnam voluptatem sed. Quaerat neque non ut numquam etincidunt quisquam.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Ramen.csv.png)
## grafiek van B-Park_Gent_Sint-Pieters
Tempora non velit amet quisquam. Ut magnam est amet sit tempora. Velit porro quaerat quaerat consectetur labore non quisquam. Amet dolor consectetur amet sit numquam quaerat voluptatem. Ipsum adipisci neque amet. Ipsum velit quiquia voluptatem adipisci tempora porro modi. Dolore etincidunt numquam eius tempora amet dolore. Labore quaerat dolore dolore quiquia. Non aliquam velit labore amet consectetur quaerat modi.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/B-Park_Gent_Sint-Pieters.csv.png)
## grafiek van Sint-Pietersplein
Voluptatem quisquam aliquam est. Quiquia modi adipisci numquam dolore eius. Etincidunt quiquia dolore dolor dolore numquam consectetur. Quiquia ut dolore amet. Magnam porro dolorem numquam dolore quaerat. Ut velit aliquam dolore voluptatem. Quisquam numquam quiquia dolorem velit aliquam. Aliquam velit consectetur non eius consectetur sed sed.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Sint-Pietersplein.csv.png)
## grafiek van Dok_noord
Etincidunt modi non porro amet dolor porro. Adipisci magnam velit voluptatem modi est dolor quisquam. Est aliquam etincidunt eius ipsum. Dolore neque eius dolorem dolorem dolorem modi ut. Neque voluptatem est velit etincidunt. Dolorem numquam magnam labore.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Dok_noord.csv.png)
## grafiek van Getouw
Sed amet quisquam magnam sed porro. Neque dolor eius velit sed. Aliquam consectetur amet voluptatem tempora dolore. Tempora dolor ipsum est magnam ut dolore sit. Dolorem dolorem porro neque ut. Quiquia adipisci quisquam tempora aliquam quaerat magnam voluptatem. Ipsum ipsum voluptatem adipisci porro.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Getouw.csv.png)
## grafiek van Vrijdagmarkt
Sed adipisci modi quiquia etincidunt sed neque sed. Sed velit labore ut quiquia quiquia. Quiquia quisquam modi dolore quisquam ipsum amet ipsum. Ipsum aliquam numquam consectetur velit dolorem magnam adipisci. Porro neque sed porro eius. Labore porro voluptatem dolorem consectetur sit. Voluptatem ut etincidunt modi modi ut magnam. Porro dolorem numquam numquam dolor. Consectetur quaerat consectetur porro consectetur velit. Dolore velit ut neque quisquam porro dolor etincidunt.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Vrijdagmarkt.csv.png)
## grafiek van Tolhuis
Dolorem magnam adipisci quisquam quiquia. Modi dolorem est numquam dolorem dolorem quaerat amet. Dolore etincidunt amet eius numquam. Velit quiquia modi voluptatem adipisci. Amet magnam sit sit modi velit. Velit eius adipisci est quisquam magnam voluptatem voluptatem.
![image](https://github.com/BrechtDeSchryver/iataak/blob/main/data-workflow/csvimage/Tolhuis.csv.png)
## grafiek van totaal
