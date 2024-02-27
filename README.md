# Dataset Medewerkers

Maak een toepassing waarbij je een volledige dataset maakt dat de
datatabel Medewerkers bevat.

De datatabel Medewerkers bevat de volgende kolommen:

-   **Mnr**: datatype (int)

-   **Naam**: datatype (string)

-   **Voorn**: datatype (string)

-   **Functie**: datatype (string)

-   **Chef**: datatype (string)

-   **Gbdatum**: datatype (DataTime)

-   **Maandsal**: datatype (float)

-   **Comm**: datatype (float)

-   **Afd**: datatype (int)

Voorzie voor de kolommen *Chef* en *Comm* dat deze kolommen een
null-waarden kunnen hebben. De kolom *Mnr* is de primaire sleutel van de
datatabel Medewerker.

De knop **BtnToevoegen** voegt onderstaande datatabel toe aan de
DataGrid. Gebruik hiervoor de void-methods *MaakTabellen()* en
*VulTabellen().*

![Afbeelding met tekst, schermopname, scherm, nummer Automatisch
gegenereerde
beschrijving](./media/image1.png)

![Afbeelding met tekst, schermopname, Lettertype, nummer Automatisch
gegenereerde
beschrijving](./media/image2.png)

De knop **BtnTabel** leest met behulp van een
OpenFileDialog de csv file *DatMedewerkers* en voegt DataRows toe aan de
DataTabel Medewerkers.

![Afbeelding met tekst, schermopname, nummer, Lettertype Automatisch
gegenereerde
beschrijving](./media/image3.png)
