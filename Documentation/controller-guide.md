# Controller Guide


In the real world, aerodrome controllers use stop bars, a row of illuminated lights, to prevent aircraft from entering active runways. In vatSys, this is simulated through the BARS plugin, which synchronizes the stop bar status between controllers and pilots both using the addon.

<br>

## Setup

### Installation  

Before installing the BARS Plugin, controllers are required to obtain a token through the [BARS Website](https://stopbars.com). Sign up for an account first, then inside the "Account Settings" page, click "Show Token" to obtain your token. Do not share this token with anyone.

After creating an account, BARS Plugin can be installed through the [BARS Website](https://stopbars.com). If the plugin is installed correctly, and your position is selected at a [compatible airport](#compatible-airports), there will be a "BARS Settings" option in the Window dropdown menu of vatSys. 

<br>

<figure>
    <img src="../Assets/BARS_settings.png" width="350">
    <figcaption></figcaption>
</figure>

<br>

Within the BARS Settings menu, you can paste in your token. Additionally, a togglable "SMR On Ground" option is available within the BARS Settings window. When enabled, the BARS Ground window will displays any pilots connected with the client.

<br>

<figure>
    <img src="../Assets/BARS_token.png" width="500">
    <figcaption></figcaption>
</figure>

<br>

### Connection
After launching vatSys, the BARS plugin will automatically open. To get started, click the "Claim Airport" button. Additionally, within the control bar a status message will display important information of the current state. This status message will show if the airport is claimed, and what runways, if any are claimed. 

After vatSys closes, BARS retains your airport and runway claims for 2 minutes, ensuring that in case of a vatSys crash, you won’t need to reclaim them upon reload; additionally, if you forget to manually unclaim, BARS will automatically unclaim all runways and airports after closing vatSys.

<br>

<figure>
    <img src="../Assets/BARS_connection.png" width="450">
    <figcaption></figcaption>
</figure>

<br>

### Select Runways
After claiming the airport, controllers **must** choose the active runways. Selecting a runway claims its stopbars for only you, and only those runways stopbars will appear on the BARS map. Unselected runways will have their stopbars turn green automatically. For operations with multiple ADC controllers, see [Dual ADC Positions](#dual-adc-positions).

<br>

<figure>
    <img src="../Assets/BARS_selecting_runways.gif" width="450">
    <figcaption></figcaption>
</figure>

### Control Bar

Once the control bar has been successfully configured, click just above the ground map to minimize it. This action reduces the control bar's size, freeing up additional screen space while still retaining key information at the top, such as connection status, and the current Zulu time.

<br>

<figure>
    <img src="../Assets/BARS_control_bar.gif" width="450">
    <figcaption></figcaption>
</figure>

<br>

## Stopbar Usage

Aircraft on the maneuvering area must stop and hold at all illuminated stopbars, proceeding only after receiving clearance. Once clearance to enter or cross a runway is given, click on the corresponding stopbar to allow the aircraft to proceed. After the aircraft clears the area, click on the stopbar again to reactivate it.

In the real world, the lights turn off again after a fixed period of time (approximately 45 seconds). This feature has also been implemented, if a controller forgets to reactivate the stopbar, after 45 seconds it will come back up.

<br>

<figure>
    <img src="../Assets/BARS_stopbar.gif" width="470">
    <figcaption></figcaption>
</figure>

## Dual ADC Positions

If multiple ADC controllers are present at one airport, each controller will be able to claim the runway within their respective jurisdiction through the [select runways](#select-runways) menu. Once a runway has been claimed, other controllers will no longer be able to claim it.

<br>

<figure>
    <img src="../Assets/BARS_duel_adc.png" width="330">
    <figcaption></figcaption>
</figure>

<br>

## Enroute Usage

BARS Plugin suports stopbar usage for C1/C3 Centre controllers, however it's initial setup is slightly different. When connected to the center position, within vatSys go to Windows > BARS and enter the four-letter ICAO code for the airport you want to control.

<br>

<figure>
    <img src="../Assets/BARS_enter_icao.png" width="400">
    <figcaption></figcaption>
</figure>

<br>

After entering the 4 letter ICAO code, you will be able to operate stopbars normally. The current version of BARS only supports one window at a time when connected to a Centre position, limiting you to controlling stopbars for a single airport. Future updates planned will allow multiple windows and airports to be managed at once.

<br>

## Runway Crossing

After coordination has been completed for aircraft to cross a duty runway, it is ADC's responsibility to drop the stopbar at the relevant crossing point, and then reactivate the stopbar once the crossing is complete. 

<br>

## Compatible Airports

- YBBN
- YSSY
- YSCB
- YMML
- YPPH

<br>

### Reporting BARS Issues

> [!TIP]  
>  If you encounter any issues with BARS, you can report them via the GitHub repository's "Issues" tab or by creating a user report through the BARS Discord Server. When submitting an issue, it’s essential to include as much detail as possible to help with troubleshooting. If required, you may need to provide the log file generated by BARS. These logs can be found in your `%localappdata%/BARS` directory. Save a copy of this file ASAP, as after every launch logs are deleted.
