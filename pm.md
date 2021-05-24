
# Titel

Mattis Kindblom   2021-02-22

## Inledning

Vi skulle göra en hemsida i desktop och de första gångerna så ville jag bara få det klart och färdit men nu, sista gången jag jobbar på den här hemsidan så tänkte jag verkligen på att knyta ihop säcken och det gjorde jag genom att inte göra allt för komplicerat men ändå få allt att se väldigt bra ut. Jag gjorde en väldigt minimalistisk footer och header som jag tycker ser väldigt bra ut och main delen av hemsidan (texten) passar in och det gör inte ont att kolla på.

## Bakgrund

Jag har gjort en css och en HTML kod för hemsidan. Jag använde mig av VS code eftersom det är den hemsidan vi ska jobbba med.
Jag testade min hemsida genom att hosta en hemsida där jag kan se vad som händer när jag gör mina ändringar live. De senaste veckorna så har jag jobbat ganska mycket på egna project (gjort en hemsida åt mig själv) och jag har lärt mig ganska mycket nytt när det kommer till kodningen, jag har blivit bättre på att förstå vad som är fel och hur jag ska göra när jag skapar en ny hemsida.

## Prövning

Jag prövade min hemsida genom att använda "tool-et" som finns för visual studio för att göra en server där hemsidan hostas så att man kan se vad som händer när man ändrar på element
Jag testade min hemsida och märkte att headern inte kunde resize-a men det fixade jag genom att ta bort loggan ifrån .inner_header genom att göra display: none och gjorde ett till logo element genom att göra en reverse logga. Jag satte den som display none i början och när innerheader loggan försvinner kommer den andra loggan upp i headern (outer header) och det fixade problemet jag hade med navigationen (tills man kommer till width: 530px)
Jag har prövat hur hemsidan blir när den resize-as, jag såg att bilden under mat-texten i index dokumentet inte såg så bra ut så jag ändrade på det så att när hemsidan blir tillräckligt liten så smälter den ihop med footern och jag ändrade dessutom så att bilden är större "over all" så att den sticker ut mer och ger hemsidan lite mer variation så att allt inte bara blir rakt och tråkigt men tänkte också på att den inte ska sticka ut för mycket. 
Jag såg också ganska tidigt hur jag inte tyckte om hur texten såg ut i about sektionen så jag ändrade den och gjorde mycket mer luft i texten så att allt inte ska se ut som en låda där allt bara har pressats in men det fixade jag bara genom att lägga till margin

## Positiva erfarenheter

Jag har blivit mycket bättre på linjering och veta vad jag ska göra, t.ex. ta bort margin, padding och sätta det som standard på hemsidan så man slipper krångla med en massa små problem längs vägen och jag känner mig också mycket tryggare när det kommer till att designa och veta hur jag vill att det ska se ut. När det kom till valideringen så hade jag bara några små slarvfel och några errors eftersom de inte gillar att mina länkar inte leder någon vart (förutom "about us")

## Negativa erfarenheter

Jag har inga riktigt dåliga erfarenheter förutom mitt första försök på hemsidan där jag inte blev klar eftersom jag gjorde det för krångligt för mig och lite grann med nya designen att headern inte kunde re-size-as.

## Saker som kan förbättras

En sak som jag skulle kunna förbättra hade kunnat vara att fixa så att i about.html att det inte ska vara style's i html texten och fixa så att allt finns i css dokument men jag tog en genväg och det som offras med det är att alla styles inte är i samma dokument (style.css). 

## Sammanfattning

Jag är väldigt nöjd med sidan, när jag öppnade hemsidan idag så var jag tvungen att ta bort en massa skit, allt gick kors och tvärs och det var ingen årning. t.ex. så kunde footern vara längst upp i css dokumentet och main texten vara i botten. det gör inget dåligt till sidan för sig men det är svårt att gå in och fixa så det var en sak jag tänkte på nu när jag fixade hemsidan
