# 🖥️ ComputerArchitectureLab – Proteus Labs & Reports

A collection of **Computer Architecture lab sessions and exercises** implemented in **Proteus**.  
The repository pairs **written lab reports** (in numbered folders) with the **Proteus project and model files** used to build and simulate the circuits.

> **Repository description:** *“computer architecture lab sessions & exercises. implemented in Proteus”* [reference:0]

---

## 📖 Overview

The repository is organised into two complementary parts:

- **Numbered folders (`2`–`12`)** — each contains a Microsoft Word report (`LabReportN.docx`) documenting one lab session.
- **`Proteus/` folder** — contains the actual **Proteus design files** (`.pdsprj`) and custom **model files** (`.MOD`) used across the labs.

Together they let you read what each lab required (report) and open/reuse the corresponding Proteus circuit (project file).

---

## 🗂️ Repository Structure

```text
ComputerArchitectureLab/
├── 2/     → LabReport2.docx
├── 3/     → LabReport3.docx
├── 4/     → LabReport4.docx
├── 5/     → LabReport5.docx
├── 6/     → LabReport6.docx
├── 7/     → LabReport7.docx
├── 8/     → LabReport8.docx
├── 9/     → LabReport9.docx
├── 10/    → LabReport10.docx
├── 11/    → LabReport11.docx
├── 12/    → LabReport12.docx
└── Proteus/
    ├── *.pdsprj          # Proteus project files
    ├── *.MOD             # Custom Proteus model files
    └── DATA.bin          # Data file used by some designs
```

### Lab report folders (`2`–`12`)

Each folder contains exactly one report file, e.g. `2/LabReport2.docx`, `12/LabReport12.docx` .[](https://github.com/alisepehrnia/ComputerArchitectureLab/tree/main/2)[](https://github.com/alisepehrnia/ComputerArchitectureLab/tree/main/12)  
Some folders (e.g. `10`, `12`) also contain Word temporary/lock files (`~$bReport6.docx`, `~WRL3286.tmp`) — these are **artefacts** and can be ignored .[](https://github.com/alisepehrnia/ComputerArchitectureLab/tree/main/10)

### `Proteus/` folder

This folder holds the **Proteus 8+** project files and custom models. Notable files include:

|Category|Files|
|---|---|
|**ALU / arithmetic**|`ALU.pdsprj`, `4BITALU.MOD`, `ALU16.MOD`, `ARTIMETH.MOD`, `CalcUnit.pdsprj`|
|**Basic computer**|`BasicComputer.pdsprj`, `BasicComputer2.pdsprj` … `BasicComputer5.pdsprj`|
|**Control / logic / shift**|`ControlUnit.pdsprj`, `LogicUnit.pdsprj`, `ShiftUnit.pdsprj`|
|**Lab-specific projects**|`Lab5-1.pdsprj`, `Lab5-2.pdsprj`, `Lab6-1.pdsprj`, `Lab6-2.pdsprj`, `Lab6-3.pdsprj`, `Lab7-1.pdsprj`, `7-2.pdsprj`, `7-3.pdsprj`, `7-4.pdsprj`, `8.pdsprj`, `8-2.pdsprj`, `8-3.pdsprj`, `8-4.pdsprj`, `9-1.pdsprj`, `9-q.pdsprj`, `10-q.pdsprj`, `11-0.pdsprj`, `11-q.pdsprj`, `12-q.pdsprj`|
|**Misc / exam**|`Excercise.pdsprj`, `New Project.pdsprj`, `temp.pdsprj`|
|**Custom models**|`ALI001.MOD`, `BUFFER_1.MOD`, `CCT001.MOD`, `CCT002.MOD`, `MYNOT001.MOD`|
|**Data**|`DATA.bin`|

A full listing is visible in the `Proteus/` directory .[](https://github.com/alisepehrnia/ComputerArchitectureLab/tree/main/Proteus)

---
## 🛠️ Tools & Technologies

| Item              | Details                                    |
| ----------------- | ------------------------------------------ |
| Simulation        | **Proteus** (project format `.pdsprj`)     |
| Custom components | Proteus **model files** (`.MOD`)           |
| Reports           | Microsoft Word (`.docx`)                   |
| Domain            | Computer Architecture laboratory exercises |

---
## 🚀 How to Use

### Reading the reports

Open any `LabReportN.docx` in **Microsoft Word**, **LibreOffice Writer**, or **Google Docs**.  
Each report typically contains the circuit schematic, simulation setup, observed results, and analysis for that lab.

### Opening the Proteus projects

1. Install **Proteus** (version 8 or later recommended).
2. Open the `.pdsprj` file for the lab you want — e.g. `Proteus/Lab6-1.pdsprj` or `Proteus/ALU.pdsprj`.
3. If the project references a custom model (e.g. `4BITALU.MOD`), make sure the corresponding `.MOD` file is available in the same directory or in Proteus’s model library.
### Matching reports to Proteus files
The report numbering and the Proteus filenames are **not perfectly aligned** (e.g. `Lab6-1.pdsprj` sits in `Proteus/`, while the report is in `6/LabReport6.docx`).  
Use the report content to identify which Proteus project belongs to which lab — the report usually names or shows the circuit that the corresponding `.pdsprj` implements.

---
## 📝 Notes & Caveats

- **No Lab 1 report.** Numbered folders start at `2`; there is no folder for Lab 1 .[](https://github.com/alisepehrnia/ComputerArchitectureLab)
- **Reports and projects are separated.** Unlike some lab repositories, the `.pdsprj` files are **not** inside the numbered folders — they are all collected in `Proteus/`. 
- **Temporary files.** Folders such as `10` and `12` contain `~$…` and `~WRL….tmp` files created by Word; they are not part of the content .[](https://github.com/alisepehrnia/ComputerArchitectureLab/tree/main/10)
- **Language.** The reports are assumed to be in the language used by the course
- **Version sensitivity.** Older Proteus projects may not open cleanly in the newest Proteus versions; if that happens, try a version closer to the project’s original release.
---
## 🤝 Contributing

This is a personal coursework archive.  
If you spot a missing report, want to add a mapping table between labs and Proteus files, or can supply a missing project, feel free to open an issue or submit a pull request.

---
## 📄 License

Feel free to use :)
