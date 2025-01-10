<img src="https://raw.githubusercontent.com/AussieScorcher/BARS/dev/Assets/BARS.png" width="200" height="200">


# BARS Ground - Stopbar Simulation

BARS Ground revolutionizes your VATSIM experience with realistic Stopbar Simulation. Fully compatible with Microsoft Flight Simulator 2024 and 2020, it integrates effortlessly with both default and third-party sceneries. Our custom installer makes setup effortlessly, the pilot client launches automatically with your simulator requiring no extra steps.

Designed for easy use, BARS Ground simulates realistic stopbar operations on VATSIM, allowing controllers and pilots to interact with lifelike stopbar procedures. With zero impact on performance, it accurately replicates stopbar usage for taxiing and ground traffic management, creating a more immersive and realistic experience on the VATSIM network.

## Documentation

- [Controller Guide](Documentation/controller-guide.md)
- [Pilot Guide](Documentation/pilot-guide.md)


## Installation [![GitHub latest release version](https://img.shields.io/github/v/release/AussieScorcher/BARS.svg?style=flat)](https://github.com/AussieScorcher/BARS/releases/latest) [![Flightsim.to](https://img.shields.io/badge/Flightsim.to-View%20Plugin-blue?logo=flightsim)](https://flightsim.to/)

To install the addon, go to the GitHub releases section and download the latest version. Choose the relevant installer: **"plugin" for controllers** or **"client" for pilots**. Once downloaded, simply run the installer, go through the setups, and everything will automatically be set up for you. Detailed guides for installation for both the client and plugin can be found in  documentation.

## FAQ

<details>
<summary>What controlling clients are supported? </summary>
<br>
<ul> <li> BARS Ground is compatible with vatSys, specifically within VATPAC’s jurisdiction. </li> </ul>
<br>
</details>

---

<details>
<summary> What simulators are supported? </summary>
<br>
<ul> <li> BARS Ground supports Microsoft Flight Simulator 2024 and 2020. </li> </ul>
<br>
</details>

---

<details>
<summary> What if I have third party scenery installed? </summary>
<br>
<ul> <li> Within the BARS Ground client, navigate to the "Third-Party Scenery" tab. Select the airport ICAO and configure the stopbar placement to match your installed payware scenery under the dropdown. </li> </ul>
<br>
</details>

---

<details>
<summary> What airports are compatible with BARS Ground? </summary>
<br>
<ul> <li> BARS Ground currently supports; YBBN, YSSY, YSCB, YMML, and YPPH. </li> </ul>
<br>
</details>

---

<details>
<summary> How do stopbars sync between controllers and pilots? </summary>
<br>
<ul> <li> The BARS Ground plugin communicates with the client via a backend server. It updates stopbar lighting in your simulator through SimConnect and SimObjects, functioning similarly to how popular add-ons like GSX work. </li> </ul>
<br>
</details>

---

<details>
<summary> Does BARS Ground impact performance? </summary>
<br>
<ul> <li> BARS Ground has no impact on performance. The install size for both the plugin and client is minimal, and stopbar lights are only loaded when you are within a certain distance from the holding point, or when ATC is online. </li> </ul>
<br>
</details>

---

<details>
<summary> What happens if there is no ATC online? </summary>
<br>
<ul> <li> If no ATC is online, the BARS Ground client will not spawn any stopbars, further optimizing performance. </li> </ul>
<br>
</details>

---

<details>
<summary> What happens I want to fly offline the network? </summary>
<br>
<ul> <li> When flying offline, BARS Ground does not detect your connection status as offline. As a result, stopbars may still appear in your simulator when ATC is online. To remove this issue, simply close the BARS Ground client from your desktop taskbar try. This will remove the stopbars from your simulator, not affecting your offline experience. </li> </ul>
<br>
</details>

---

<details>
<summary> Is there any documentation available for advanced features? </summary>
<br>
<ul> <li> Comprehensive guides and documentation for both controllers and pilots are accessible via the GitHub repository, with direct links provided at the top of this README for ease of access. </li> </ul>
<br>
</details>

---

<details>
<summary> How do I report bugs or issues with the client or plugin? </summary>
<br>
<ul> <li> You can report issues through the GitHub repository or contact the maintainers via Discord. </li> </ul>
<br>
</details>

---

<details>
<summary> How do I uninstall BARS Ground if I no longer need it? </summary>
<br>
<ul> <li> Navigate to your computer’s “Add/Remove Programs” window, search for BARS, and uninstall the relevant components. </li> </ul>
<br>
</details>

<!----
## Gallery
![App Screenshot](Assets/)
-->


