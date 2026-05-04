# Subnautica SFX & OST Extractor

Get the ZIP containing all SFX and OST files:
[Download directly here](https://github.com/rachit9876/subnautica-all-audio/releases/latest) (for game version v83031)

Get the game files for modding:
[Free download](https://ankergames.net/game/subnautica)


---

## Manual Extraction Guide

If you prefer to extract the files manually, follow the steps below:

### 1. Locate the Audio Bank Files
Open your Subnautica installation directory and navigate to the `StreamingAssets` folder:
`Subnautica\Subnautica_Data\StreamingAssets\`

Here, you will see several `.bank` files (such as `Cyclops.bank`, `Seamoth.bank`, `Pod.bank`, and `Master Bank.bank`). These files contain the entire OST and SFX library for the game, including the PDA voice lines.

### 2. Download the Extraction Tool
To extract the audio, we will use a tool called **Fmod-Bank-Tools**.
* Download it here: [Fmod-Bank-Tools on GitHub](https://github.com/Wouldubeinta/Fmod-Bank-Tools)

### 3. Extract the Files
1. Copy the `.bank` files you found in Step 1 into the Fmod tools bank directory: `...\Fmod_Bank_Tools\bank`
2. Open the Fmod Bank Tools executable (`.exe`).
3. Click the file menu at the top-left corner and click **Extract**. 
4. *Note: This process is heavily reliant on your CPU and may take a moment.*
5. Once complete, the tool will output the extracted audio into the `...\Fmod_Bank_Tools\wav` directory.

---
File Structure here : [See](https://github.com/rachit9876/subnautica-all-audio/blob/main/dir.md)
