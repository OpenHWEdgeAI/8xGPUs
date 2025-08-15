<p align="center">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=1800&pause=600&color=11F732&background=000000&width=1000&height=110&lines=Welcome+-+where+8%C3%974090Ds+become+your+new+roommate." alt="Typing SVG" />
    </a>
</p>

<p align="center">
    <img src="Photos/8GPU/Preparing/EE/inside-8card.jpg" width="700" style="border-radius: 12px; box-shadow: 0 4px 16px #11F73255;">
</p>

<div align="center">

<img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
<img src="https://img.shields.io/github/stars/OpenHWEdgeAI/8xGPUs" alt="GitHub stars">
<img src="https://img.shields.io/badge/Status-In%20Development-blue" alt="Status">
<img src="https://img.shields.io/github/downloads/OpenHWEdgeAI/8xGPUs/total" alt="Downloads">
<img src="https://img.shields.io/github/v/release/OpenHWEdgeAI/8xGPUs" alt="Version">
<img src="https://img.shields.io/github/repo-size/OpenHWEdgeAI/8xGPUs" alt="Repo Size">
<img src="https://img.shields.io/github/issues/OpenHWEdgeAI/8xGPUs" alt="Open Issues">
<img src="https://img.shields.io/github/issues-pr/OpenHWEdgeAI/8xGPUs" alt="Open Pull Requests">

</div>

---

<div align="center">
    <b><i>
        This guide shows you how to build a cutting-edge AI server with 8x GPUs. From hardware selection to software setup, follow each step to create a high-performance platform for deep learning, data science, and GPU-intensive workloads.
    </i></b>
</div>

---

## 📚 Table of Contents
- [Introduction](#-introduction)
- [Preparation](#-preparing)
- [Assembly](#-assembling)
- [Setup](#-setup)
- [Testing](#-testing)
- [GG Drive](#-gg-drive)
- [BOM](#bom) *(update soon)*
- [Author](#author)
- [License](#license)

---

## [I. Introduction 🙋🏻‍♂️🙋🏻‍♀️🙋‍♀️🙋🏻🙋🏽‍♂️🙋🏼‍♂️🙋🏽‍♀️💁‍♂️🙋🏼🙍‍♂️🙋🏾‍♂️✋✋✋✋✋✋✋✋](#-introduction) &ensp; [🔝](#-table-of-contents)

<table>
    <tr>
        <td align="center" width="55%">
            <b><i>
                This tutorial is for anyone aiming to build a high-performance AI server with 8 GPUs. Whether you're a researcher, developer, or enthusiast, you'll learn everything from hardware selection and assembly to system configuration and initial testing. Finish with a robust platform ready for demanding AI workloads.
            </i></b>
        </td>
        <td align="center" width="45%">
            <img src="Photos/8GPU/Introduction/EdgeAI-8GPU-1.png" width="420" height="370" style="border-radius: 8px;">
        </td>
    </tr>
</table>

---

## [II. Preparation 🧑🏽‍🔧](#-preparing) &ensp; [🔝](#-table-of-contents)

### 1. **Electronic & Electrical**

<table>
    <tr>
        <td valign="top" align="center" width="50%">
            <b>1. Motherboard GENOA2D24G-2L+</b><br>
            <img src="Photos/8GPU/Preparing/EE/MB_GENOA2D24G-2L%2B-1(L).jpg" width="400"><br>
            <b>3. CPU AMD EPYC 9004</b><br>
            <img src="Photos/8GPU/Preparing/EE/CPU.jpg" width="400"><br>
            <b>5. SSD NVME 1TB</b><br>
            <img src="Photos/8GPU/Preparing/EE/SSD.png" width="400"><br>
            <b>7. RAM DDR5 48GB</b><br>
            <img src="Photos/8GPU/Preparing/EE/RAM_DDR5.jpg" width="400"><br>
            <b>9. MCIO Adapter</b><br>
            <img src="Photos/8GPU/Preparing/EE/MCIO_Adapter.png" width="400"><br>
            <b>11. MCIO cable</b><br>
            <img src="Photos/8GPU/Preparing/EE/MCIO_cable.jpg" width="400"><br>
            <b>13. Fan</b><br>
            <img src="Photos/8GPU/Preparing/EE/fan.jpg" width="400"><br>
        </td>
        <td valign="top" align="center" width="50%">
            <b>2. PSU board</b><br>
            <img src="Photos/8GPU/Preparing/EE/PSU_board_4.png" width="400"><br>
            <b>4. CPU heat sink</b><br>
            <img src="Photos/8GPU/Preparing/EE/CPU_heatsink.jpg" width="400"><br>
            <b>6. SSD heat sink</b><br>
            <img src="Photos/8GPU/Preparing/EE/SSD_heatsink.jpg" width="400"><br>
            <b>8. PSU</b><br>
            <img src="Photos/8GPU/Preparing/EE/PSU.jpg" width="400"><br>
            <b>10. Power cord</b><br>
            <img src="Photos/8GPU/Preparing/EE/power_cord.jpg" width="400"><br>
            <b>12. GPU</b><br>
            <img src="Photos/8GPU/Preparing/EE/GPU.png" width="400"><br>
            <b>14. Hub fan</b><br>
            <img src="Photos/8GPU/Preparing/EE/hub_fan.jpg" width="400"><br>
        </td>
    </tr>
</table>

---

### 2. **Mechanical & Housing**

<table>
    <tr>
        <td valign="top" align="center" width="50%">
            <b>1. CNC Mill</b><br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/1.1- CNC Mill.png" width="400"><br>
            <b>3. Anodized</b><br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/3-Anodized.png" width="400"><br>
        </td>
        <td valign="top" align="center" width="50%">
            <b>2. Sand blasting</b><br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/2-Sand blasting.png" width="400"><br>
            <b>4. Anodized</b><br>
            <img src="Photos/8GPU/Preparing/CNC_Mill_Aluminum_Housing/3.1-Anodized .png" width="400"><br>
        </td>
    </tr>
</table>

<p align="center">
    <video src="https://github.com/user-attachments/assets/05ee937c-a871-4809-914b-d98930b31777"></video>
</p>

---

## [III. Assembly 🦾](#-assembling) &ensp; [🔝](#-table-of-contents)

| Step | Description | Image |
|------|-------------|-------|
| 1 | Prepare all components. | ![](Photos/8GPU/Assembling/1-Preparing%20all%20components.png) |
| 2 | Assemble “Part 7 – Side” and “Part 8 – Side Cover” together. Repeat for the other side. | ![](Photos/8GPU/Assembling/2.png) |
| 3 | Install the dust filter. | ![](Photos/8GPU/Assembling/3.png) |
| 4 | Assemble the 120 mm × 120 mm fan. | ![](Photos/8GPU/Assembling/4.png) |
| 5 | Install the remaining fans. | ![](Photos/8GPU/Assembling/5.png) |
| 6 | Connect all fans to the control board. | ![](Photos/8GPU/Assembling/6.png) |
| 7 | Place plastic spacers in position on “Part 2 – CPU Plate”. | ![](Photos/8GPU/Assembling/7.png) |
| 8 | Fix the PSU board to “Part 2 – CPU Plate”. | ![](Photos/8GPU/Assembling/8.png) |
| 9 | Insert all screws, but do not tighten them yet. | ![](Photos/8GPU/Assembling/9.png) |
| 10 | Assemble the Ethernet board into “Part 10 – PSU Mount”. | ![](Photos/8GPU/Assembling/10.png) |
| 11 | Place “Part 10 – PSU Mount” into position. | ![](Photos/8GPU/Assembling/11.png) |
| 12 | Place “Part 1 – GPU Plate” on top. | ![](Photos/8GPU/Assembling/12.png) |
| 13 | Place all middle parts onto “Part 5 – Bottom”. | ![](Photos/8GPU/Assembling/13.png) |
| 14 | Place all support mounts into position. | ![](Photos/8GPU/Assembling/14.png) |
| 15 | Secure with M4 × 8 mm screws. | ![](Photos/8GPU/Assembling/15.png) |
| 16 | Place “Part 4 – Back” into position and secure it with M4 screws. | ![](Photos/8GPU/Assembling/16.png) |
| 17 | Install all four PSUs into position and connect them to the PSU board. | ![](Photos/8GPU/Assembling/17.png) |
| 18 | Tighten all screws on the PSU board. | ![](Photos/8GPU/Assembling/18.png) |
| 19 | Install M4 × 15 mm copper spacers into the M4 holes on the other side. | ![](Photos/8GPU/Assembling/19.png) |
| 20 | Place the “Motherboard GENOA2D24G-2L+” into position. | ![](Photos/8GPU/Assembling/20.png) |
| 21 | Secure the motherboard to “Part 2 – CPU Plate” using M3 screws. | ![](Photos/8GPU/Assembling/21.png) |
| 22 | Place 20 mm plastic spacers under the PCI board and secure them with M4 screws. | ![](Photos/8GPU/Assembling/22.png) |
| 23 | Install the remaining components. | ![](Photos/8GPU/Assembling/23.png) |
| 24 | Just a photo  | ![](Photos/8GPU/Assembling/24.png) |
| 25 | Just a photo  | ![](Photos/8GPU/Assembling/25.png) |
| 26 | Place the assembled parts upright. | ![](Photos/8GPU/Assembling/26.png) |
| 27 | Connect the PCI board cable to the motherboard. | ![](Photos/8GPU/Assembling/27.png) |
| 28 | Use zip ties to organize cables. | ![](Photos/8GPU/Assembling/28.png) |
| 29 | Connect the power cable to the motherboard. | ![](Photos/8GPU/Assembling/29.png) |
| 30 | Connect MCIO cable to MCIO adapter | ![](Photos/8GPU/Assembling/30.png) |
| 31 | Place “Part 6 – Top” into position and secure it with M4 screws and the support plate. | ![](Photos/8GPU/Assembling/31.png) |
| 32 | Install 8 GPUs. | ![](Photos/8GPU/Assembling/32.png) |
| 33 | Secure the GPUs to the support rail. | ![](Photos/8GPU/Assembling/33.png) |
| 34 | Organize the power supply cables. | ![](Photos/8GPU/Assembling/34.png) |
| 35 | Connect the power supply cables. | ![](Photos/8GPU/Assembling/35.png) |
| 36 | Connect the fan board cable, then place the fan board into position. | ![](Photos/8GPU/Assembling/36.png) |
| 37 | Secure “Part 7 – Side”. | ![](Photos/8GPU/Assembling/37.png) |
| 38 | Repeat for the other side. | ![](Photos/8GPU/Assembling/38.png) |
| 39 | Connect the main power supply. | ![](Photos/8GPU/Assembling/39.png) |


---

## [IV. Setup 🛠️](#-setup) &ensp; [🔝](#-table-of-contents)

### BIOS Optimization for GPU Performance

> **Tip:** The default BIOS settings may not deliver optimal performance for multi-GPU workloads. Adjust these parameters for best results:

- **PCIe Settings** ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    🚨📢🔔⚠️
    Set all PCIe slots to the highest supported speed (Gen4/Gen5) and configure bifurcation for your GPUs.<br>
    ```
    Advanced -> Chipset Configuration -> PCIE link width -> set MCIO2/1, MCIO4/3, MCIO6/5, MCIO8/7, MCIO12/11, MCIO14/13, MCIO16/15, MCIO18/17 to x16
    ```

- **Above 4G Decoding** ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    🚨📢🔔⚠️
    Enable "Above 4G Decoding" to address large GPU memory.<br>
    ```
    May be enabled by default
    ```

- **Resizable BAR** ![Static Badge](https://img.shields.io/badge/Important-8A2BE2)<br>
    🚨📢🔔⚠️
    Activate "Resizable BAR" for improved CPU-GPU data transfer.<br>
    ```
    Advanced -> PCI Subsystems Settings -> Enable Re-size BAR support
    ```

- **Power Management**  
    Disable unnecessary power-saving features (C-states, ASPM) that may throttle GPU performance.<br>
    `Optional`

- **Memory Configuration**  
    Set RAM to rated speed and enable XMP/DOCP profiles for max bandwidth.<br>
    `Optional`

- **Fan and Thermal Controls**  
    Adjust fan curves and thermal limits for optimal cooling.<br>
    `Optional`

After saving changes, reboot and monitor GPU performance and stability.

**References:**  
- [Motherboard User Manual 💻🖱️](https://download.asrock.com/Manual/GENOA2D24G-2L%2b.pdf)  
- [BMC Documents 🤖](https://download.asrock.com/Manual/BMC/GENOA2D24G-2L%2b.pdf)

<p align="center">
    <video src="https://github.com/user-attachments/assets/41cd6d5d-9acd-41d6-b9c2-4da4666f3870"></video>
</p>

---

## [V. Testing 🕵🏻](#-testing) &ensp; [🔝](#-table-of-contents)

Boot with WinPE from USB to verify hardware, or install Linux, NVIDIA drivers, and check with `nvtop`. Once confirmed, install your OS and start your AI work.

<table>
    <tr>
        <td align="center">
            <img src="Photos/8GPU/Testing/Nvtop.png" width="700"><br>
        </td>
        <td align="center">
            <img src="Photos/8GPU/Assembling/40.png" width="400"><br>
        </td>
    </tr>
</table>

<p align="center">
    <video src="https://github.com/user-attachments/assets/71afbc5c-ae69-410e-868a-a52b915b1e7a"></video>
</p>

---

## [VI. GG Drive 🗂️](#-gg-drive) &ensp; [🔝](#-table-of-contents)

[📦 3D Step Models](https://drive.google.com/drive/folders/1CPBjhxc8X349RCH8z7i7xvXVxy29Kzuq)

---

## [VII. Author ✍️](#author) &ensp; [🔝](#-table-of-contents)

![We are EdgeAI](https://img.shields.io/badge/We%20are%20EdgeAI-%23007EC6)

---

## [VIII. License📝](#license) &ensp; [🔝](#-table-of-contents)

This project is open source under the [MIT License](https://github.com/OpenHWEdgeAI/8xGPUs/blob/main/LICENSE).

---

<p align="center">
    <a href="https://git.io/typing-svg">
        <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=1800&pause=600&color=11F732&background=000000&width=1450&height=110&lines=If+this+helped%2C+toss+us+a+%E2%AD%90+%E2%80%94+and+stay+tuned%2C+the+next+2%C3%97GPUs+drop+next+Thurs.+" alt="Typing SVG" />
    </a>
</p>