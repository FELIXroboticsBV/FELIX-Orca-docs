# Installatie

Op deze pagina lees je hoe je Orca Slicer kunt downloaden en starten.

## Downloaden

!!! danger "Pas op voor nepwebsites"

    De **enige** officiële website van Orca Slicer is [www.orcaslicer.com](https://www.orcaslicer.com/). Andere domeinen, zoals [www.orca-slicer.com](https://www.orca-slicer.com), zijn **niet officieel** en kunnen aangepaste, verouderde of schadelijke software verspreiden. Controleer altijd de URL voordat je iets downloadt.

    **Disclaimer:** Orca Slicer is software van derden en wordt niet ontwikkeld of ondersteund door FELIX Robotics BV. Het gebruik ervan is volledig op eigen risico. FELIX Robotics BV aanvaardt geen aansprakelijkheid voor schade aan je printer, prints, computer of gegevens als gevolg van het gebruik van Orca Slicer, de bijbehorende profielen of software die is gedownload van onofficiële bronnen.

Ga eerst naar de [officiële website van Orca](https://www.orcaslicer.com/) en download de **Stable build** voor jouw besturingssysteem. We raden aan de aanbevolen optie per systeem te kiezen: de `Microsoft Store` voor Windows en `Flatpak` voor Linux.

<figure markdown="span">
  ![Welkomstpagina's](../images/how%20to%20download.gif){ width="1000" }
<figcaption>Download het installatieprogramma voor jouw besturingssysteem</figcaption>
</figure>

## Windows

1. Klik op de downloadpagina op de knop **Microsoft Store**. Orca Slicer wordt dan geopend in de Microsoft Store-app.
2. Klik op **Downloaden** (of **Installeren**) en wacht tot de installatie is voltooid.
3. Start Orca Slicer via het **Startmenu**.

De Microsoft Store-versie wordt automatisch bijgewerkt, zodat je altijd de nieuwste stabiele versie hebt.

!!! tip "Alternatief: winget"

    Werk je liever via de opdrachtregel? Dan kun je Orca Slicer ook installeren met winget:

    ```powershell
        winget install --id=SoftFever.OrcaSlicer -e
    ```

## Linux

1. Zorg dat Flatpak is geïnstalleerd en dat de Flathub-repository is ingeschakeld op je systeem. Is dat niet het geval, volg dan de instructies voor jouw distributie op [flatpak.org/setup](https://flatpak.org/setup/).
2. Installeer Orca Slicer vanaf Flathub. Dit kan via je grafische softwarecentrum (zoals GNOME Software of KDE Discover) door te zoeken op **OrcaSlicer**, of via een terminal:

```bash
    flatpak install flathub com.orcaslicer.OrcaSlicer
```

3. Start Orca Slicer via je applicatiemenu, of voer het volgende uit:

```bash
    flatpak run com.orcaslicer.OrcaSlicer
```

Om Orca Slicer later bij te werken, gebruik je je softwarecentrum of voer je `flatpak update` uit.

!!! note "Eerste keer opstarten"

    Wanneer je Orca Slicer voor het eerst start, helpt een installatiewizard je bij het kiezen van je printer en het instellen van je voorkeuren.
