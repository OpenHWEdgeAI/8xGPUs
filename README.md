<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=2000&pause=500&color=11F732&background=000000&width=1450&height=100&lines=Welcome+to+our+GitHub+profile!+This+is+where+we+share+projects+and+contributions." alt="Typing SVG" /></a>
</p>
<p align="center">
  <img src="Photos/8GPU/Preparing/EE/inside-8card.jpg">
</p>

This guide introduces how to build a powerful server with 8x GPUs for AI applications. It covers the essential hardware and software steps needed to create a high-performance system for machine learning.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/OpenHWEdgeAI/8xGPUs)](https://github.com/OpenHWEdgeAI/8xGPUs/stargazers)

## 📚 [Table of Contents](#-table-of-contents)
- [Introduction](#-introduction)
- [Preparing](#-preparing)
- [Assembling](#-assembling)
- [Setup](#-setup)
- [Testing](#-testing)
- [GG Drive](#-gg-drive)
- [BOM](#bom)(update soon)
- [Author](#author)
- [License](#license)

## [I. Introduction](#-introduction) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)


<table>
    <tr>
        <td align="center" width="50%">
        <p><b><i>This tutorial is for anyone looking to build a high-performance AI server with 8 GPUs. Whether you're a researcher, developer, or enthusiast, this guide will walk you through every step—from selecting hardware and assembling components to configuring the system and running initial tests. You'll finish with a powerful platform ready for deep learning, data science, and other GPU-intensive workloads. <i><b></p>
        </td>
        <td align="center" width="50%">
        <img src="Photos/8GPU/Introduction/EdgeAI-8GPU-1.png" width=450 height=400><br>
        </td>
    </tr>
    
</table>

## [II. Preparing](#-preparing) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)
### 1. *Electronic & Electrical:*
<table>
    <tr>
        <td valign="top" align="center" width="50%">
            <b>1. Motherboard GENOA2D24G-2L+</b><br>
            <img src="Photos/8GPU/Preparing/EE/MB_GENOA2D24G-2L%2B-1(L).jpg" width="450" height="400"><br>
            <b>3. CPU AMD EPYC 9004</b><br>
            <img src="Photos/8GPU/Preparing/EE/CPU.jpg" width="450" height="400"><br>
            <b>5. SSD NVME 1TB</b><br>
            <img src="Photos/8GPU/Preparing/EE/SSD.png" width="450" height="400"><br>
            <b>7. RAM DDR5 48GB</b><br>
            <img src="Photos/8GPU/Preparing/EE/RAM_DDR5.jpg" width="450" height="400"><br>
            <b>9. MCIO Adapter</b><br>
            <img src="Photos/8GPU/Preparing/EE/MCIO_Adapter.png" width="450" height="400"><br>
            <b>11. MCIO cable</b><br>
            <img src="Photos/8GPU/Preparing/EE/MCIO_cable.jpg" width="450" height="400"><br>
            <b>13. Fan</b><br>
            <img src="Photos/8GPU/Preparing/EE/fan.jpg" width="450" height="400"><br>
        </td>
        <td valign="top" align="center" width="50%">
            <b>2. PSU board</b><br>
            <img src="Photos/8GPU/Preparing/EE/PSU_board_4.png" width="450" height="400"><br>
            <b>4. CPU heat sink</b><br>
            <img src="Photos/8GPU/Preparing/EE/CPU_heatsink.jpg" width="450" height="400"><br>
            <b>6. SSD heat sink</b><br>
            <img src="Photos/8GPU/Preparing/EE/SSD_heatsink.jpg" width="450" height="400"><br>
            <b>8. PSU</b><br>
            <img src="Photos/8GPU/Preparing/EE/PSU.jpg" width="450" height="400"><br>
            <b>10. Power cord</b><br>
            <img src="Photos/8GPU/Preparing/EE/power_cord.jpg" width="450" height="400"><br>  
            <b>12. GPU</b><br>
            <img src="Photos/8GPU/Preparing/EE/GPU.png" width="450" height="400"><br>
            <b>14. Hub fan</b><br>
            <img src="Photos/8GPU/Preparing/EE/hub_fan.jpg" width="450" height="400"><br>      
        </td>
    </tr>
</table>
<br>
<br>
<br>
<br>

### 2. *Mechanical & Housing:*
<table>
    <tr>
        <td valign="top" align="center" width=50%>
            <b>1. CNC Mill </b> <br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/1.1- CNC Mill.png" width=450 height=400><br>
            <b>3. Anodized </b> <br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/3-Anodized.png" width=450 height=400><br>
        </td>
        <td valign="top" align="center" width="50%">
            <b>2. Sand blasting </b> <br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/2-Sand blasting.png" width=450 height=400><br>
            <b>4. Anodized </b><br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/3.1-Anodized .png" width=450 height=400><br>
        </td>
    </tr>
</table>

<video src="https://github.com/user-attachments/assets/05ee937c-a871-4809-914b-d98930b31777"></video>

## [III. Assembling](#-assembling) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)


<table>
    <tr>
        <td valign="top" align="center" width="50%">
            <b>1. Preparing components  </b><br>
            <img src="Photos/8GPU/Assembling/1-Preparing all components.png" width=450 height=400><br>
            <b>3.Attaching the fan grid <b><br>
            <img src="Photos/8GPU/Assembling/3.png" width=450 height=400><br>
            <b>5. <b><br>
            <img src="Photos/8GPU/Assembling/5.png" width=450 height=400><br>
            <b>7. <b><br>
            <img src="Photos/8GPU/Assembling/7.png" width=450 height=400><br>
            <b>9. <b><br>
            <img src="Photos/8GPU/Assembling/9.png" width=450 height=400><br>
            <b>11. <b><br>
            <img src="Photos/8GPU/Assembling/11.png" width=450 height=400><br>
            <b>13.Fixing the PSU board to frame<b><br>
            <img src="Photos/8GPU/Assembling/13.png" width=450 height=400><br>
            <b>15. <b><br>
            <img src="Photos/8GPU/Assembling/15.png" width=450 height=400><br>
            <b>17. <b><br>
            <img src="Photos/8GPU/Assembling/17.png" width=450 height=400><br>
            <b>19. <b><br>
            <img src="Photos/8GPU/Assembling/19.png" width=450 height=400><br>
            <b>21. <b><br>
            <img src="Photos/8GPU/Assembling/21.png" width=450 height=400><br>
            <b>23. <b><br>
            <img src="Photos/8GPU/Assembling/23.png" width=450 height=400><br>
            <b>25. <b><br>
            <img src="Photos/8GPU/Assembling/25.png" width=450 height=400><br>
            <b>27. <b><br>
            <img src="Photos/8GPU/Assembling/27.png" width=450 height=400><br>
            <b>29. <b><br>
            <img src="Photos/8GPU/Assembling/29.png" width=450 height=400><br>
            <b>31. <b><br>
            <img src="Photos/8GPU/Assembling/31.png" width=450 height=400><br>
            <b>33. <b><br>
            <img src="Photos/8GPU/Assembling/33.png" width=450 height=400><br>
            <b>35. <b><br>
            <img src="Photos/8GPU/Assembling/35.png" width=450 height=400><br>
            <b>37. <b><br>
            <img src="Photos/8GPU/Assembling/37.png" width=450 height=400><br>
            <b>39. <b><br>
            <img src="Photos/8GPU/Assembling/39.png" width=450 height=400><br>
        </td>
        <td valign="top" align="center" width="50%">
            <b>2. </b><br>
            <img src="Photos/8GPU/Assembling/2.png" width=450 height=400><br>
            <b>4.Fixing the fan to frame <b><br>
            <img src="Photos/8GPU/Assembling/4.png" width=450 height=400><br>
            <b>6.Attaching controller for fans<b><br>
            <img src="Photos/8GPU/Assembling/6.png" width=450 height=400><br>
            <b>8.Fixing the PSU board to frame <b><br>
            <img src="Photos/8GPU/Assembling/8.png" width=450 height=400><br>
            <b>10. <b><br>
            <img src="Photos/8GPU/Assembling/10.png" width=450 height=400><br>
            <b>12. <b><br>
            <img src="Photos/8GPU/Assembling/12.png" width=450 height=400><br>
            <b>14. <b><br>
            <img src="Photos/8GPU/Assembling/14.png" width=450 height=400><br>
            <b>16. <b><br>
            <img src="Photos/8GPU/Assembling/16.png" width=450 height=400><br>
            <b>18. <b><br>
            <img src="Photos/8GPU/Assembling/18.png" width=450 height=400><br>
            <b>20. <b><br>
            <img src="Photos/8GPU/Assembling/20.png" width=450 height=400><br>
            <b>22. <b><br>
            <img src="Photos/8GPU/Assembling/22.png" width=450 height=400><br>
            <b>24. <b><br>
            <img src="Photos/8GPU/Assembling/24.png" width=450 height=400><br>
            <b>26. <b><br>
            <img src="Photos/8GPU/Assembling/26.png" width=450 height=400><br>
            <b>28. <b><br>
            <img src="Photos/8GPU/Assembling/28.png" width=450 height=400><br>
            <b>30. <b><br>
            <img src="Photos/8GPU/Assembling/30.png" width=450 height=400><br>
            <b>32. <b><br>
            <img src="Photos/8GPU/Assembling/32.png" width=450 height=400><br>
            <b>34. <b><br>
            <img src="Photos/8GPU/Assembling/34.png" width=450 height=400><br>
            <b>36. <b><br>
            <img src="Photos/8GPU/Assembling/36.png" width=450 height=400><br>
            <b>38. <b><br>
            <img src="Photos/8GPU/Assembling/38.png" width=450 height=400><br>
            <b>40. <b><br>
            <img src="Photos/8GPU/Assembling/40.png" width=450 height=400><br>
        </td>
    </tr>
</table>

## [IV. Setup](#-setup) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)
### BIOS Optimization for GPU Performance

The default BIOS settings of the motherboard may not deliver optimal performance for multi-GPU workloads. To maximize the capabilities of your AI server, it is recommended to adjust several BIOS parameters:

- **PCIe Settings:**  ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    Ensure all PCIe slots are set to the highest supported speed (e.g., Gen4 or Gen5) and configure bifurcation if required for your GPUs.<br>
    ```
     Advanced -> Chipset Configuration -> PCIE link width -> set MCIO2/1, MCIO4/3, MCIO6/5, MCIO8/7, MCIO12/11, MCIO14/13, MCIO16/15, MCIO18/17 to x16
    ```
    

- **Above 4G Decoding:**  ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    Enable "Above 4G Decoding" to allow the system to address large amounts of GPU memory.
    ```
    Maybe this one enable by default
    ```

- **Resizable BAR:** ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    Activate "Resizable BAR" (Base Address Register) for improved data transfer between CPU and GPUs.<br>
    ```
    Advanced -> PCI Subsystems Settings -> Enable Re-size BAR support
    ```
    

- **Power Management:**  
    Disable unnecessary power-saving features that may throttle GPU performance, such as C-states and ASPM.<br>
    `Optional`


- **Memory Configuration:**  
    Set RAM to its rated speed and enable XMP/DOCP profiles if available for maximum bandwidth.<br>
    `Optional`

- **Fan and Thermal Controls:**  
    Adjust fan curves and thermal limits to ensure adequate cooling for all components.<br>
    `Optional`

After making these changes, save and reboot the system. Monitor GPU performance and stability during initial tests to confirm improvements.

<video src="https://github.com/user-attachments/assets/41cd6d5d-9acd-41d6-b9c2-4da4666f3870"></video><br>

## [V. Testing](#-testing) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)
Start by booting with WinPE from a USB drive to quickly verify all hardware components are functioning correctly. Once the hardware is confirmed, you can proceed with installing your desired OS to begin working on your AI application.

<video src="https://github.com/user-attachments/assets/71afbc5c-ae69-410e-868a-a52b915b1e7a"></video><br>

## [VI. GG Drive](#-gg-drive) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)

[3D Step Models](https://drive.google.com/drive/folders/1CPBjhxc8X349RCH8z7i7xvXVxy29Kzuq)

## [VII. Author](#author) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)
![We are EdgeAI](https://img.shields.io/badge/We%20are%20Edge%20AI-%23007EC6)

## [VIII. License](#license) &ensp; &ensp; &ensp; &ensp;[🔝](#-table-of-contents)
This project is open source and available under the [MIT License](https://github.com/OpenHWEdgeAI/8xGPUs/blob/main/LICENSE)


<p align="center">
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&duration=2000&pause=500&color=11F732&background=000000&width=700&height=100&lines=Thank+you+for+visiting+me.+Goodbye!" alt="Typing SVG" /></a>
</p>