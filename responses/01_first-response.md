# Pull Requests

Zoals we eerder besproken hebben, voer je een `commit` niet direct op de `master`-branch door, maar doe je dit in een zogenaamde *feature branch*. Vervolgens vraag je aan je team of jouw wijzigingen doorgevoerd mogen worden in de *collaboration branch* (`master`). Dit doorvoeren gebeurt met behulp van een *Pull Request*.

### Pull Requests

Een Pull Request (vaak afgekort als PR) is feitelijk een vraag aan je team. Het is alsof je zegt: "Hier zijn mijn wijzigingen. Mogen die geïntegreerd worden in onze master-branch?". Andere mensen in je team kunnen hier dan op reageren. Op basis van de opmerkingen en reviews van anderen kun je dan in je branch nog nieuwe wijzigingen aanbrengen. Wanneer eventuele issues zijn opgelost en reviewers positief zijn over je Pull Request, kun je een *merge* doorvoeren waarmee de wijzigingen worden doorgezet naar de `master`-branch. Vaak verwijder je na de *merge* direct de *feature branch*.

Hoewel Pull Requests heel veel gebruikt worden om een *merge* door te voeren naar `master`, is de inzet niet beperkt tot `master`. Een PR kan tussen elke twee branches gedaan worden.

## Stap 1: Wijziging in een *feature branch* doen

Als Data Warehouse-beheerders en -ontwikkelaars lopen we al een tijdje tegen het feit aan dat we allerhande vertalingskolommen hebben toegevoegd in onze dimensie-tabellen. Die kosten relatief veel onderhoud, en worden eigenlijk nauwelijks gebruikt. We hebben daarom afgesproken dat in de tabel `dbo.DimProduct` de regels 26-33 (`FrenchDescription` tot `TurkishDescription`) verwijderd worden.

### :keyboard: Doorvoeren van de wijziging in een feature branch.

1. Bewerk - binnen GitHub - het bestand [edit/master/02-git-branching/src/Tables/DimProduct.sql](https://github.com/vstrien/git-github-workshop/edit/master/02-git-branching/src/Tables/DimProduct.sql)
2. *Commit* de wijzigingen naar een nieuwe branch met de naam `verwijderen-vertalingen`

<hr>
<h3 align="center">Watch below this comment for my response</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
