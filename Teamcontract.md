Teamcontract
Teamgegevens en rollen

Teamnaam: RHMN
Projectlidgegevens:
Reinout van Schilt, Scrum Master, Git-beheerder, D254889@edu.curio.nl, D254889
Hubert Szamrej, Product Owner-contact, D311551@edu.curio.nl, hoebart123
Mohamed Derrazi, Notulist, D311584@edu.curio.nl, Mo-749
Naod Teklemichael, Tester, D295700@edu.curio.nl, naod234
Rouleren de rollen? Zo ja, wanneer?
Elke sprint, maar uiteindelijk is iedereen een Notulist of Tester.

Communicatie en overleg
Welk kanaal gebruiken jullie waarvoor (Teams, Discord, WhatsApp, GitHub Issues)?
Op teams in het groupkanaal

Binnen hoeveel tijd reageer je op een bericht? Geldt dat ook in het weekend of 's avonds?
Zo snel mogelijk, buiten les tijd alleen wanneer het echt nodig is om privacy te beschermen en anders eerst volgende ‘werkdag’

Wanneer is de stand-up (dag, tijd, duur) en wat bespreek je daar?
15 minuten lang in de eerste 15 minuten van de les en we bespreken wat we gedaan hebben, wat we gaan doen en of er problemen zijn ermee.

Waar leggen jullie besluiten vast?
Op teams in het groupkanaal

Beschikbaarheid en werktijden
Op welke momenten werk je aan het project (lestijd, thuis, vaste uren)?
Tijdens de aangegeven lessen eventueel thuis wanneer dit een mogelijkheid is voor de projectleden.

Hoeveel uur per week verwacht je van elk teamlid?
Alle uren tijdens projectlessen

Hoe geef je bekend wanneer je niet beschikbaar bent (bijbaan, stage, sport)?
Via het teams kanaal

Afwezigheid en uitval

Gepland afwezig (afspraak, vakantie):
Als een teamlid gepland afwezig is, bijvoorbeeld door een afspraak of vakantie, meldt diegene dit minimaal 3 werkdagen van tevoren in het Teams-groepskanaal. Hierbij wordt de Scrum Master geïnformeerd.

 Onverwacht afwezig (ziek):
Als een teamlid ziek is of onverwacht niet aanwezig kan zijn, meldt diegene dit zo snel mogelijk en uiterlijk vóór 09:00 uur op de betreffende schooldag in het Teams-groepskanaal. De Scrum Master wordt hiervan op de hoogte gebracht.

Overdracht:
Bij afwezigheid zorgt het teamlid ervoor dat anderen met het werk verder kunnen. Dit betekent:
- De gemaakte code is gepusht naar de eigen Git-branch.
- Het takenbord in GitHub is bijgewerkt.
- Er staat een korte notitie in Teams met wat af is en wat nog gedaan moet worden.
- Eventuele problemen of fouten worden vermeld.

Wie neemt over?:
De Scrum Master verdeelt de openstaande taken onder de aanwezige teamleden. Hierbij wordt rekening gehouden met ieders beschikbare tijd en huidige werklast. Taken worden zo eerlijk mogelijk verdeeld. Niemand krijgt zonder overleg alle taken van een afwezig teamlid toegewezen.

Langdurig afwezig (meer dan een week):
Wanneer een teamlid langer dan één week afwezig is, bespreekt de Scrum Master dit met de docent. Als de afwezigheid invloed heeft op de studievoortgang, wordt ook de SLB'er betrokken. Het team maakt samen een nieuwe taakverdeling.

Ongemeld afwezig:
Wanneer een teamlid niet aanwezig is en niets laat weten, probeert de Scrum Master contact op te nemen via Teams. Als er binnen één schooldag geen reactie komt, wordt dit besproken met de docent. Bij herhaaldelijk ongemeld afwezig zijn, wordt de docent opnieuw ingeschakeld.

Inhalen: 
Een teamlid dat afwezig is geweest, is zelf verantwoordelijk voor het inhalen van gemist werk en gemiste kennis. Dit gebeurt door:
- De notulen en berichten in het Teams-groepskanaal terug te lezen.
- Het takenbord en de GitHub-branches te bekijken.
- Bij een teamlid uitleg te vragen over gemiste werkzaamheden.
- Openstaande eigen taken zo snel mogelijk weer op te pakken.
De Scrum Master controleert tijdens de eerstvolgende stand-up of het teamlid weer op de hoogte is en zijn werkzaamheden kan hervatten.


Taakverdeling en planning
Welk takenbord gebruiken jullie (GitHub Projects, Trello, Jira)?
Github Projects

Hoe worden taken verdeeld en wie mag een taak oppakken?
Tijdens de stand-up worden taken verdeeld. De Scrum Master houdt overzicht over de taakverdeling. Teamleden mogen zelf een beschikbare taak van het GitHub-projectbord oppakken, zolang dit eerst duidelijk wordt aangegeven in het Teams-groepskanaal. Per taak is één persoon verantwoordelijk.

Wat is jullie Definition of Done: wanneer is een taak echt af?
Een taak is pas af wanneer:
- De code werkt zoals afgesproken.
- De code is getest en bevat geen bekende fouten.
- De code naar GitHub is gepusht.
- De code is gecontroleerd door minimaal één ander teamlid.
- De taak op het GitHub-projectbord op 'Done' staat.

Hoe lang mag een taak "in progress" staan voordat je hulp vraagt?
Wanneer iemand langer dan één werkdag vastloopt op een taak, vraagt diegene hulp in het Teams-groepskanaal. Zo voorkomen we onnodige vertraging.

Git-workflow
Welke branching-strategie gebruiken jullie (bijvoorbeeld feature branches of GitHub Flow)?
We gebruiken GitHub Flow. Voor iedere nieuwe functie of aanpassing wordt een aparte feature- of fix-branch aangemaakt. Na controle wordt deze samengevoegd met main.

Is main beschermd? Mag iemand direct op main pushen?
De main-branch is beschermd. Niemand mag rechtstreeks naar main pushen. Wijzigingen worden alleen via een pull request samengevoegd.

Hoe noem je branches (bijv. feature/login-pagina, fix/123-crash)?
We gebruiken Engelse namen met een herkenbaar voorvoegsel:
- feature/login-pagina
- feature/registreren
- fix/login-error
- fix/bug-123

Hoe schrijf je commitberichten (taal, vorm, koppeling met issue-nummer)?
Commitberichten worden in het Engels geschreven en beschrijven kort wat er veranderd is. Bijvoorbeeld:
- Add login page
- Fix navigation bug
- Update homepage styling

Hoe vaak commit en push je minimaal (bijv. aan het eind van elke werksessie)?
Ieder teamlid commit en pusht minimaal aan het einde van iedere werksessie. Bij grote wijzigingen wordt tussendoor ook gepusht, zodat werk niet verloren gaat.

Wie lost een merge conflict op, en hoe?
De persoon die de pull request heeft aangemaakt, lost het merge conflict op. Bij problemen helpt de Git-beheerder. Daarna wordt gecontroleerd of de code nog correct werkt.

Wat staat er in .gitignore en hoe gaan jullie om met wachtwoorden en API-keys (nooit in de repo)?
In .gitignore staan bestanden die niet in GitHub thuishoren, zoals:
- Tijdelijke bestanden.
- IDE-instellingen.
- Lokale configuratiebestanden.
- .env-bestanden.

Codeafspraken en kwaliteit
Welke codeconventies volgen jullie (naamgeving, inspringing, taal van variabelen en commentaar)?
Welke codeconventies volgen jullie?
- We gebruiken Engelse namen voor variabelen en functies.
- We gebruiken duidelijke en beschrijvende namen.
- We gebruiken overal dezelfde inspringing van vier spaties.
- We schrijven code overzichtelijk en houden functies zo klein mogelijk.
- We gebruiken dezelfde programmeerstijl binnen het project.

Gebruiken jullie een linter of formatter (bijv. ESLint, Prettier, PHP CS Fixer)?
We gebruiken indien mogelijk Prettier om de code op dezelfde manier op te maken. Iedereen zorgt ervoor dat zijn code netjes en overzichtelijk blijft.

Wanneer schrijf je commentaar of documentatie?
We schrijven commentaar wanneer code niet vanzelfsprekend is of wanneer een ingewikkelde functie extra uitleg nodig heeft. Belangrijke functies en onderdelen worden kort gedocumenteerd.

Worden er tests geschreven? Moeten tests slagen vóór een merge?
Ja, nieuwe functies en belangrijke wijzigingen worden getest. Voordat een pull request wordt samengevoegd, moeten de uitgevoerde tests slagen en mogen er geen bekende fouten zijn.

Code reviews en pull requests
Hoeveel goedkeuringen zijn nodig voordat een pull request gemerged mag worden?
Minimaal één ander teamlid moet de code controleren en goedkeuren voordat de pull request wordt samengevoegd.

Binnen hoeveel tijd review je een pull request? 
We proberen iedere pull request binnen één schooldag te controleren.

Waar let je op tijdens een review (werkt het, leesbaar, conventies, tests)?
We controleren:
- Of de code werkt.
- Of de code overzichtelijk en leesbaar is.
- Of de codeafspraken zijn gevolgd.
- Of de tests slagen.
- Of er geen onnodige of foutieve code is toegevoegd.


Hoe geef je feedback: opbouwend, specifiek, over de code en niet over de persoon?
Feedback wordt altijd opbouwend en respectvol gegeven. We benoemen specifiek wat verbeterd moet worden en richten ons op de code, niet op de persoon.

Wat gebeurt er als de reviewer afwezig is?
Dan neemt een ander beschikbaar teamlid de review over. Bij voorkeur iemand die voldoende kennis heeft van het onderdeel.

Conflicten, problemen en consequenties
Hoe spreek je een teamlid aan dat afspraken niet nakomt? Beschrijf de stappen:
We gebruiken de volgende stappen:
1. Het teamlid wordt eerst persoonlijk aangesproken.
2. Als het probleem blijft bestaan, wordt het besproken tijdens de stand-up.
3. De Scrum Master maakt samen met het team afspraken over verbetering.
4. Als er geen verbetering komt, wordt de docent ingeschakeld.

Hoe nemen jullie besluiten als je het niet eens bent (stemmen, meerderheid, Scrum Master beslist)?
We proberen eerst samen tot een oplossing te komen. Als dat niet lukt, wordt er gestemd. De meerderheid bepaalt het besluit. Bij belangrijke technische problemen kan de Scrum Master helpen om een passende oplossing te kiezen.

Hoe zorg je dat ieders bijdrage zichtbaar is (commits, issues, urenlog)?
We houden ieders bijdrage zichtbaar via:
- GitHub-commits.
- Pull requests.
- GitHub Issues en het projectbord.
- De notulen van de stand-ups en overleggen.

Hoe en wanneer evalueren jullie het contract (bijv. elke retrospective)?
We evalueren het teamcontract aan het einde van iedere sprint tijdens de retrospective. Als afspraken niet goed werken, kunnen we deze samen aanpassen. Alle wijzigingen worden vastgelegd in het Teams-groepskanaal.

Goedkeuring
Door het goedkeuren van de pull request met het bestand TEAMCONTRACT.md op GitHub geeft ieder teamlid aan akkoord te gaan met alle afspraken in dit teamcontract.
Datum: 26 november 2026
Teamleden:
1. Reinout van Schilt
2. Hubert Szamrej
3. Mohamed Derrazi
4. Naod Teklemichael


