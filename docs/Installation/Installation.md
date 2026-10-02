# Installation

This page will show you how you can download and run Orca slicer.

## Downloading
!!! danger "Beware of fake websites"

    The **only** official website for Orca Slicer is [www.orcaslicer.com](https://www.orcaslicer.com/). Other domains, such as [www.orca-slicer.com](https://www.orca-slicer.com), are **not official** and may distribute modified, outdated, or malicious software. Always verify the URL before downloading anything.

    **Disclaimer:** Orca Slicer is third-party software and is not developed or supported by FELIX Robotics BV. You use it entirely at your own risk. FELIX Robotics BV accepts no liability for any damage to your printer, prints, computer, or data resulting from the use of Orca Slicer, its profiles, or software downloaded from unofficial sources.

That being said, first, visit [Orca's official website](https://www.orcaslicer.com/) and download **Stable build** for your operating system. We recommend to follow the recommended options for each. That is: `Miscrosoft Store` for windows and `Flatpack` for Linux

<figure markdown="span">
  ![Welcome pages](../images/how%20to%20download.gif){ width="1000" }
  
<figcaption>Download the installer for your operating system</figcaption>
</figure>

## Windows

1. On the download page, click the **Microsoft Store** button. This opens Orca Slicer in the Microsoft Store app.
2. Click **Get** (or **Install**) and wait for the installation to finish.
3. Launch Orca Slicer from the **Start menu**.

The Microsoft Store version updates automatically, so you will always have the latest stable release.

!!! tip "Alternative: winget"

    If you prefer the command line, you can also install Orca Slicer with winget:
    ```powershell
        winget install --id=SoftFever.OrcaSlicer -e
    ```

## Linux

1. Make sure Flatpak is installed and the Flathub repository is enabled on your system. If it is not, follow the instructions for your distribution at [flatpak.org/setup](https://flatpak.org/setup/).
2. Install Orca Slicer from Flathub. You can do this through your graphical software center (such as GNOME Software or KDE Discover) by searching for **OrcaSlicer**, or from a terminal:

```bash
    flatpak install flathub com.orcaslicer.OrcaSlicer
```

3. Launch Orca Slicer from your application menu, or run:

```bash
    flatpak run com.orcaslicer.OrcaSlicer
```

To update Orca Slicer later, use your software center or run `flatpak update`.

!!! note "First launch"

    When you start Orca Slicer for the first time, a setup wizard will guide you through selecting your printer and initial preferences.
