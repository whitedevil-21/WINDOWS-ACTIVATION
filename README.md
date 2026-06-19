# Instant Windows 10 & 11 Activation: 40‑Second Solution

[![Readme](https://img.shields.io/badge/README_IN-ENGLISH-blue?logo=readme)](README.md)

> This repository provides ways to activate Windows 10 and 11 in under 40 seconds. Both methods are compatible with Home, Home N, Home Single Language, Home Country Specific, Professional, Education, and Enterprise editions of Windows.

---

## Method 1 (Recommended)

### Instant Windows activation using PowerShell

> [!TIP]
> There are many ways to run PowerShell in Windows 10 & 11. [^1]

One of the fastest ways is using the Start menu search. Follow these steps:

<br>

### Step 1

Hit the Start or search icon and type `PowerShell` in the search box.

> Another easy way: [^2]

<div align="left">
  <img src="https://github.com/user-attachments/assets/5a10538a-c8c2-4934-868b-fd8e910f1f9e" width="540px">
</div>

<br>

### Step 2

Click `Run as Administrator` to start PowerShell with **administrative privileges** is required here.

<div align="left">
  <img src="https://github.com/user-attachments/assets/1f25dd2a-16db-4053-a45c-aac6f8a9e470" width="540px">
</div>

<br>

### Step 3

After a brief pause, copy the following line:

```powershell
irm https://get.activated.win | iex
```

<br>

### Step 4

Paste it (with right‑click) and press Enter. In the newly opened window, a script menu will appear. Select option `1` and wait a few seconds for the process to complete.

<div align="left">
  <img src="https://github.com/user-attachments/assets/0c3689a1-1595-40b3-97e2-041dac423237" width="540px">
</div>

<br>

#### Congratulations

Your Windows has been activated. You can now press Enter to exit the console, close PowerShell, and verify activation in the Windows activation menu. [^3]

---

## Method 2

### Instant Windows activation using CMD (Command Prompt)

> [!NOTE]
> Remember to **connect to the Internet**.  
> A VPN is **not necessary**.

<br>

### Step 1

Hit the Start or search icon and type `CMD` in the search box. When the Command Prompt appears, run it as an **administrator**.

> Another easy way: [^2]

<div align="left">
  <img src="https://github.com/user-attachments/assets/88ac970a-f24b-4acc-82c0-f8e7c0b05249" width="480px">
</div>

<br>

### The following is the list of LICENSE KEYS

|            **Key**            |  **Version**   |
| :---------------------------: | :------------: |
| TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 |      Home      |
| 3KHY7-WNT83-DGQKR-F7HPR-844BM |     Home N     |
| 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH |  Home SL [^4]  |
| PVMJN-6DFY6–9CCP6–7BKTT-D3WVR |  Home CS [^5]  |
| W269N-WFGWX-YVC9B-4J6C9-T83GX |  Professional  |
| MH37W-N47XK-V7XM9-C7227-GCQG9 | Professional N |
| NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 |   Education    |
| 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ |  Education N   |
| NPPR9-FWDCX-D2C8J-H872K-2YT43 |   Enterprise   |
| DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 |  Enterprise N  |

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)

<br>

### Step 2 — Install KMS client key

Use this command:

```cmd
slmgr /ipk yourlicensekey
```

> [!NOTE]
> Choose one **license key** from the list that matches your Windows version and replace `yourlicensekey` in the command with that key.  
> [!TIP]
> How to check your Windows version: [^3]

<div align="left">
  <img src="https://github.com/user-attachments/assets/1b6401e6-7e63-4351-8a92-fa355dfc30cf" width="480px">
</div>

<div align="left">
  <img src="https://github.com/user-attachments/assets/90037069-7ea3-44a8-a9fa-e296f5e8d47b" width="340px">
</div>

<br>

### Step 3 — Set KMS machine address

Use the command:

```cmd
slmgr /skms kms8.msguides.com
```

to connect to the KMS server.

<div align="left">
  <img src="https://github.com/user-attachments/assets/9d634454-1c59-47da-874e-bfe575288fe6" width="480px">
</div>

<div align="left">
  <img src="https://github.com/user-attachments/assets/2d2e6cfb-4e85-483f-ae0a-c7157d22da36" width="340px">
</div>

<br>

### Step 4 — Activate Windows

Activate Windows using:

```cmd
slmgr /ato
```

<div align="left">
  <img src="https://github.com/user-attachments/assets/5e495d42-6ce5-4884-9de2-96a56efb4343" width="480px">
</div>

<div align="left">
  <img src="https://github.com/user-attachments/assets/aecd9cfd-8c09-4433-b410-a62205a8d692" width="240px">
</div>

<br>

### Step 5 — Check activation status

Verify the activation status again. [^6]

<div align="left">
  <img src="https://github.com/user-attachments/assets/9ca70137-8e2e-4504-a52d-22f41d959bd7" width="480px">
</div>

#### Done ✅

Your Windows is activated successfully.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

---

[^1]: [10 Ways to run PowerShell in Windows](https://www.google.com/amp/s/www.minitool.com/news/open-windows-11-powershell.html%3famp)  
[^2]: Another easy way to run PowerShell: **Right‑click** the Start button and select **Windows Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10.  
[^3]: To check your Windows version: **Right‑click** the Start button and open **System**. Your Windows edition appears under **Edition**. You can also follow the CMD steps in Method 2 by copying and pasting the commands into PowerShell or CMD and using **Right‑click** to paste.  
[^4]: Home Single Language version.  
[^5]: Home Country Specific version.  
[^6]: To see the Windows activation status, go to:  
***Settings → Update & Security → Activation***.
