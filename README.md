# LoggingAndErrorHandling

## Opdrachten
1. Maak in Shared een klasse product aan met de properties:
    - Id : int
    - Name :string (not null)
    - Price: decimal (null)
2. Maak in Shared een Warehouse klasse aan met de properties:
    - Id
    - Products: List<Product> (not null)
    - Methods:
        - GetAllProducts()
        - AddProduct()
        - RemoveProduct()
        - CalculateAveragePrice()
3. Maak een testproject aan en maak unit testen en implementeer de methoden in stap 2
4. Maak de functionaliteit zo dat een product niet toe kan worden gevoegd als het nog geen prijs heeft.
5. Breid de functionaliteit van 4 uit zodat een product met een negatieve prijs niet toe kan worden gevoegd.
6. Maak de functionaleit van de gemiddelde berekening kloppend voor een lege lijst.
7. Voeg eeen API controller toe voor de product resource.
8. Maak binnen de site pagina's aan voor het tonen van de lijst met producten en het toevoegen van een product
9. Binnen de controller wil ik kunnen controleren wanneeer een product toegevoegd wordt. Pas deze functionaliteit hiervoor aan.