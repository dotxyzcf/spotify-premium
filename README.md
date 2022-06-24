<center>
    <h1 align="center">Spotify-Premium</h1>
    <h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Windows</strong> Spotify desktop application.</h4>
    <h5 align="center">Please support Spotify by purchasing premium</h5>
    <p align="center">
        <strong>Last updated:</strong> 24.06.2022<br>
        <strong>Last tested version:</strong> 1.1.88.612.gcc529952
    </p> 
</center>

### Features:
* Blocks all banner/video/audio ads within the app
* Retains friend, vertical video and radio functionality
* Unlocks the skip function for any track
* Now supports the new Alpha version (New UI)

:warning: This mod is for the [**Desktop Application**](https://www.spotify.com/download/windows/) of Spotify on Windows only and **not the Microsoft Store version**. If you dont know, which version you have just run the installer and answer everything with **Y (Yes)**. It would check it automatically and change the version, if needed.

### Installation/Update:
* Just download and run [Spotify-Premium.bat](https://github.com/dotxyzcf/spotify-premium/releases/latest/download/Spotify-Premium.bat)  

or

* Run The following command in PowerShell:
```ps1
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/dotxyzcf/spotify-premium/main/src/install.ps1' | Invoke-Expression
```

#### Automated installation via PowerShell

```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/dotxyzcf/spotify-premium/main/src/install.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify -RemoveAdPlaceholder"
```

### Uninstall:
* Just run [uninstall.bat](https://github.com/dotxyzcf/spotify-premium/releases/latest/download/uninstall.bat)
or
* Reinstall Spotify 

### Known Issues:  
N/A

### Additional Notes:
N/A
