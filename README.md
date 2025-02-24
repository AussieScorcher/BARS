<img src="https://raw.githubusercontent.com/AussieScorcher/BARS/main/Assets/BARS.png" width="200" height="200">


# BARS - Stopbar Simulation

BARS revolutionize your VATSIM experience with realistic Stopbar Simulation. Fully compatible with Microsoft Flight Simulator 2024 and 2020, it integrates effortlessly with default and third-party sceneries. Our custom installer makes setup effortlessly, the pilot client launches automatically with your simulator requiring no extra steps.

Designed for easy use, BARS simulates realistic stopbar operations on VATSIM, allowing controllers and pilots to interact with lifelike stopbar procedures. With zero impact on performance, it accurately replicates stopbar usage for taxiing and ground traffic management, creating a more immersive and realistic experience on the VATSIM network.

<br>

<a href="https://ko-fi.com/stopbars">
  <img src="https://img.shields.io/badge/Donate%20to%20keep%20BARS%20alive%20and%20free!-darkgreen?style=flat&logo=ko-fi&logoColor=white" alt="Donate to keep BARS alive and free!" style="width:300px;">
</a>

<br>
<br>

<a href="https://discord.gg/7SQgbc554K">
  <img src="https://img.shields.io/badge/Join-Discord-7289da?logo=discord&logoColor=white" alt="Join the discord for important updates!" style="width:100px;">
</a>

## Documentation

- [Controller Guide](Documentation/controller-guide.md)
- [Pilot Guide](Documentation/pilot-guide.md)


## Installation

To install the addon, go to the [Github releases](https://github.com/AussieScorcher/BARS/releases) section and download the latest version. Choose the relevant installer: **"plugin" for controllers** or **"client" for pilots**. Once downloaded, simply run the installer, go through the setups, and everything will automatically be set up for you. Detailed guides for installation for both the client and plugin can be found in the documentation.

## FAQ

<details>
<summary> Why do the stopbars turn green instead of just off like the real world? </summary>
<br>
<ul> <li> In the current version, the stopbars are green to help pilots on the network who might not fully understand the signal. Our goal is to make the simulation as realistic as possible for all users. For the next update, we will be implementing a more realistic option, giving pilots the ability to select their preferred stopbar color in the client. </li> </ul>
<br>
</details>

---

<details>
<summary>What controlling clients are supported? </summary>
<br>
<ul> <li> BARS is compatible with vatSys. </li> </ul>
<br>
</details>

---

<details>
<summary> What simulators are supported? </summary>
<br>
<ul> <li> BARS supports Microsoft Flight Simulator 2024 and 2020. </li> </ul>
<br>
</details>

---

<details>
<summary> What if I have third-party scenery installed? </summary>
<br>
<ul> <li> Within the BARS client, navigate to the "Scenery Section" tab. Select the desired third-party scenery to configure the stopbar placement to match your installed payware scenery. </li> </ul>
<br>
</details>

--- 

<details>
<summary> What airports are compatible with BARS? </summary>
<br>
<ul> <li> BARS currently supports; YBBN, YSSY, YSCB, YMML, and YPPH. With plans to expand to as many airports as possible. </li> </ul>
<br>
</details>

---

<details>
<summary> How do stopbars sync between controllers and pilots? </summary>
<br>
<ul> <li> The BARS plugin communicates with the client via the backend server. It updates stopbar lighting in your simulator through SimConnect and SimObjects, functioning similarly to how popular add-ons like GSX work. </li> </ul>
<br>
</details>

---

<details>
<summary> What if the pilot is using the addon, but the controller isn't, and vice versa? </summary>
<br>
<ul> <li> If the controller isn't using the addon, they wouldn't be able to claim the airport. Without the airport claimed by a controller, BARS will think that no ATC is online actively using the plugin. Therefore, the stopbars won't be spawned. </li> </ul>
<br>
</details>

---

<details>
<summary> Does BARS impact performance? </summary>
<br>
<ul> <li> BARS has no impact on performance. The install size for both the plugin and client is extremely small, and stopbar lights are only loaded when you are within a certain distance from the holding point, or when ATC is online. </li> </ul>
<br>
</details>

---

<details>
<summary> What happens if there is no ATC online? </summary>
<br>
<ul> <li> If no ATC is online, the BARS client will not spawn any stopbars.  </li> </ul>
<br>
</details>

---

<details>
<summary> What happens if I want to fly offline the network? </summary>
<br>
<ul> <li> When flying offline, BARS does not detect your connection status as offline. As a result, stopbars may still appear in your simulator when ATC is online. To remove this issue, simply close the BARS client from your desktop taskbar tray This will remove the stopbars from your simulator, not affecting your offline experience. </li> </ul>
<br>
</details>

---

<details>
<summary> Is there any documentation available for advanced features? </summary>
<br>
<ul> <li> Comprehensive guides and documentation for both controllers and pilots are accessible via the GitHub repository, with direct links provided at the top of this README for ease of access. 

<br>

- [Controller Guide](Documentation/controller-guide.md)
- [Pilot Guide](Documentation/pilot-guide.md)

</li> </ul>
<br>
</details>

---

<details>
<summary> How do I report bugs or issues with the client or plugin? </summary>
<br>
<ul> <li> You can report issues through the GitHub repository or create a user report through the BARS Discord Server (https://discord.gg/7SQgbc554K). </li> </ul>
<br>
</details>

---

<details>
<summary> How do I uninstall BARS client or plugin if I no longer need it? </summary>
<br>
<ul> <li> Navigate to your computer’s “Add/Remove Programs” window, search for BARS, and uninstall the relevant application. </li> </ul>
<br>
</details>

---

<details>
<summary> Does BARS modify the scenery files? </summary>
<br>
<ul> <li> No, BARS does not modify any scenery files. The stopbar lights are dynamically spawned on top of the default or third-party scenery. </li> </ul>
<br>
</details>

---

### Reporting BARS Ground Issues

> [!TIP]  
>  If you encounter any issues with BARS, you can report them via the GitHub repository's "Issues" tab or by creating a user report through the BARS Discord Server. When submitting an issue, it’s essential to include as much detail as possible to help with troubleshooting. If required, you may need to provide the log file generated by BARS. These logs can be found in your `%localappdata%/BARS` directory. Save a copy of this file ASAP, as after every launch logs are deleted.
