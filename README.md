Formål
--------
Dette dokument har til formål at guide dig gennem processen med at oprette et mere avanceret GitHub Actions workflow, 
som indeholder to separate jobs, der kører parallelt. Ved at følge denne øvelse lærer du, 
hvordan du bruger GitHub Actions til at automatisere dine workflows og bruge forskellige shells (som Python og PowerShell) til at udføre kommandoer på tværs af forskellige operativsystemer.

Udbytte af Øvelsen
--------------------
Ved afslutningen af øvelsen vil du have opnået følgende:

* Oprettelse af et Workflow med flere jobs:
Du vil kunne oprette en YAML-fil, der definerer et GitHub Actions workflow med flere jobs, som kan køre på forskellige operativsystemer.

* Forståelse af Shells i GitHub Actions:
Du vil lære, hvordan du specificerer og bruger forskellige shells (f.eks. Python, Bash, PowerShell) inden for dine workflows.

* Parallel udførelse af jobs:
Du vil forstå, hvordan jobs kan køre parallelt, og hvordan du kan kontrollere rækkefølgen af jobs ved at bruge needs nøgleordet.

* Forståelse af CI/CD-principper:
Du vil få en grundlæggende forståelse af, hvordan CI/CD-processer fungerer, og hvordan de implementeres ved hjælp af GitHub Actions.

Forklaring af Begreber
----------------------
* GitHub Actions:
En funktion i GitHub, der giver dig mulighed for at automatisere processer som CI/CD (Continuous Integration/Continuous Deployment) gennem workflows defineret i YAML-filer.

* Workflow:
En automatiseret proces defineret i en YAML-fil, som kan bestå af et eller flere jobs.

* Job:
En sektion inden for et workflow, som indeholder en række trin (steps).
Hvert job kan køre på et specifikt operativsystem og udfører de definerede handlinger uafhængigt af andre jobs, medmindre andet er angivet.

* Shell:
En kommandolinjegrænseflade, der bruges til at udføre kommandoer. Eksempler inkluderer Bash, PowerShell og Python shell.

* Parallel Execution:
Jobs i et workflow, der kører samtidig, uden at vente på at andre jobs afsluttes.

* needs nøgleord:
En YAML-nøgle, der bruges til at specificere, at et job skal vente på et andet job, før det kører.

* CI/CD:
Continuous Integration (CI) og Continuous Deployment (CD) er to tæt relaterede praksisser inden for softwareudvikling,
der hjælper teams med at levere kodeændringer hurtigt og sikkert.

----- Continuous Integration (CI): En praksis, hvor udviklere regelmæssigt integrerer deres kodeændringer i et fælles repository. Hver integration bliver automatisk bygget og testet, hvilket sikrer, at nye ændringer ikke bryder eksisterende funktionalitet. CI forbedrer samarbejde og kvaliteten af softwaren.

----- Continuous Deployment (CD): Udvider CI ved at automatisere udgivelsen af applikationer til produktion efter de er blevet testet. Når koden er godkendt af CI, bliver den automatisk deployeret til produktionsmiljøet. Dette reducerer tiden fra kodeudvikling til udrulning, hvilket gør det muligt for teams at levere nye funktioner hurtigere og mere konsistent.

Opsummering
-----------
Dokumentet hjælper dig med at oprette og forstå et mere komplekst GitHub Actions workflow med to jobs, der kører parallelt på forskellige operativsystemer. 
Du lærer, hvordan du bruger forskellige shells og kontrollerer jobrækkefølge ved hjælp af YAML-syntaxen, samtidig med at du får en dybere forståelse af CI/CD-principperne, 
som er afgørende for moderne softwareudvikling og automatisering.
