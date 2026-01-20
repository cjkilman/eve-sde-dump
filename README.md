# EVE Online SDE - CSV Dump

This repository contains the **Static Data Export (SDE)** for EVE Online, converted into CSV format for easy use in Google Sheets, Excel, and other applications.

**Last Updated:** (Check file commit dates)

## 🚀 How to use in Google Sheets

You can import any table directly into Google Sheets using the `IMPORTDATA` function with the **Raw** URL.

**Formula Template:**
```excel
=IMPORTDATA("[https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/FILENAME.csv](https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/FILENAME.csv)")

📂 Common Files & Quick Links

Here are the formulas for the most commonly used tables. Copy these directly into cell A1 of your spreadsheet.
Table Name	Description	Formula
invTypes	Item IDs, names, volumes, and groups.	=IMPORTDATA("https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/invTypes.csv")
industryBlueprints	Blueprint IDs and production limits.	=IMPORTDATA("https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/industryBlueprints.csv")
industryActivityMaterials	Bill of Materials (What builds what).	=IMPORTDATA("https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/industryActivityMaterials.csv")
mapSolarSystems	System IDs, security status, and regions.	=IMPORTDATA("https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/mapSolarSystems.csv")
mapRegions	Region names and IDs.	=IMPORTDATA("https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/mapRegions.csv")
planetSchematics	PI Schematics and inputs/outputs.	=IMPORTDATA("https://raw.githubusercontent.com/cjkilman/eve-sde-dump/main/planetSchematics.csv")

🔄 Generation Source

These files are automatically generated using a custom Python converter that transforms the official CCP YAML SDE into relational CSVs.

    Converter Tool: eve-sde-converter (Maintained by @cjkilman)

    Original Logic: Based on the work of Steve Ronuken (Fuzzwork).

⚖️ Legal & Disclaimer

EVE Online and the EVE logo are the registered trademarks of CCP hf. All rights are reserved worldwide. All other trademarks are the property of their respective owners. EVE Online, the EVE logo, EVE and all associated logos and designs are the intellectual property of CCP hf. All artwork, screenshots, characters, vehicles, storylines, world facts or other recognizable features of the intellectual property relating to these trademarks are likewise the intellectual property of CCP hf.

CCP hf. has granted permission to use EVE Online and all associated logos and designs for promotional and information purposes on its website but does not endorse, and is not in any way affiliated with, this project.

