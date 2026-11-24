╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   ██╗   ██╗ ██████╗ ██╗  ████████╗██████╗ ███████╗███████╗  ║
║   ██║   ██║██╔═══██╗██║  ╚══██╔══╝██╔══██╗██╔════╝██╔════╝  ║
║   ██║   ██║██║   ██║██║     ██║   ██║  ██║█████╗  ███████╗  ║
║   ╚██╗ ██╔╝██║   ██║██║     ██║   ██║  ██║██╔══╝  ╚════██║  ║
║    ╚████╔╝ ╚██████╔╝███████╗██║   ██████╔╝███████╗███████║  ║
║     ╚═══╝   ╚═════╝ ╚══════╝╚═╝   ╚═════╝ ╚══════╝╚══════╝  ║
║                                                              ║
║              / / ELECTRONICS TOOLKIT / /                     ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

### 🔌 Your personal electronics laboratory. Anytime. Anywhere.

<p align="center">

**A powerful, lightweight and completely offline electronics toolkit for Windows.**

🖥️ Windows 10 / 11 · 🐍 Python · 🔓 Open Source · 🌙 Dark Mode · 📡 Offline

</p>

---

# 🚀 WHAT IS VOLTDESK?

**VoltDesk** is a desktop application designed to make electronics easier to understand, calculate and learn.

Whether you are an electronics student, an apprentice, a hobbyist or simply interested in technology, VoltDesk gives you useful tools in one simple application.

Instead of searching through different websites or calculating everything manually, you can use VoltDesk to solve common electronics calculations in seconds.

The application is designed to be:

- ⚡ Fast and lightweight
- 🌙 Modern with a dark interface
- 🔌 Completely usable offline
- 🧮 Easy to understand
- 💻 Designed for Windows
- 🔓 Free and open source

**No account. No subscription. No internet connection required.**

---

# ✨ FEATURES — WHAT CAN VOLTDESK DO?

## 1. ⚡ Ohm's Law Calculator

Calculate the four most important electrical values:

- Voltage (U) — Volt (V)
- Current (I) — Ampere (A)
- Resistance (R) — Ohm (Ω)
- Power (P) — Watt (W)

The calculator helps you understand the relationship between voltage, current and resistance.

**Important formulas:**

- U = R × I
- I = U / R
- R = U / I
- P = U × I

**Example:**

You have a 9 V battery and a 330 Ω resistor.

VoltDesk helps you calculate the current flowing through the resistor.

## 2. 🎨 Resistor Color Code Decoder

Not sure what the colors on a resistor mean?

VoltDesk can decode resistor color bands.

Supported:
- 4-band resistors
- 5-band resistors
- Resistance values
- Multipliers
- Tolerance values

Example:

🟤 Black Red Gold

Select the colors and let VoltDesk calculate the resistance.

## 3. 💡 LED Resistor Calculator

Want to calculate a suitable resistor for an LED?

Enter:

- Supply voltage
- LED forward voltage
- LED current

VoltDesk calculates the required resistance and suggests a nearby standard resistor value.

## 4. 🔗 Series & Parallel Calculator

Calculate the total resistance of multiple resistors.

**Series connection:**

R(total) = R1 + R2 + R3

**Parallel connection:**

1/R(total) = 1/R1 + 1/R2 + 1/R3

Enter your resistor values and VoltDesk calculates the result.

## 5. 🔋 Capacitor Calculator

Understand capacitor values and convert between different units.

Supported units:

- pF — Picofarad
- nF — Nanofarad
- µF — Microfarad

You can also decode common three-digit ceramic capacitor codes.

Example:

**104 = 100 nF**

## 6. 📝 Electronics Notebook

Keep your own electronics knowledge organized.

You can save:
- Formulas
- Notes
- Important information
- Learning summaries
- Technical explanations

Your notes are stored locally on your computer.

## 7. 📊 Calculation History

VoltDesk remembers your recent calculations.

You can view previous results without calculating everything again.

Your calculation history is stored locally.

---

# 🖥️ HOW TO INSTALL VOLTDESK

There are two ways to use VoltDesk.

## METHOD 1 — Run from Python

This method is useful if you want to look at the source code or modify the application.

**Step 1:** Download or clone this repository.

**Step 2:** Install Python 3.10 or newer.

Official Python website:

https://www.python.org/downloads/

**Step 3:** Open the downloaded project folder.

**Step 4:** Open a terminal in the project folder.

**Step 5:** Start VoltDesk with:

```bash
python src/voltdesk.py
```

That's it! VoltDesk should now open.

## METHOD 2 — Build a Windows application (.EXE)

Want to use VoltDesk like a normal Windows program?

You can create an executable version.

**Step 1:** Download the repository.

**Step 2:** Make sure Python is installed.

**Step 3:** Open the VoltDesk folder.

**Step 4:** Double-click:

`build_windows.bat`

**Step 5:** Wait until the build process finishes.

The executable will be created inside:

```text
dist/
   VoltDesk/
      VoltDesk.exe
```

**Step 6:** Double-click `VoltDesk.exe`.

🎉 Congratulations! VoltDesk is running as a Windows desktop application.

---

# 📂 PROJECT STRUCTURE

```text
VoltDesk/
│
├── src/
│   └── voltdesk.py
│
├── README.md
├── LICENSE
├── requirements.txt
├── build_windows.bat
└── .gitignore
```

---

# 🔒 PRIVACY & SECURITY

VoltDesk is designed with simplicity and privacy in mind.

- No user account required.
- No cloud connection required.
- No telemetry.
- No internet connection needed for calculations.
- Notes and calculation history stay on your computer.

Local application data is stored here:

```text
%USERPROFILE%\.voltdesk
```

---

# 💻 TECHNOLOGY

VoltDesk is built using:

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Tkinter | Desktop user interface |
| JSON | Local data storage |
| PyInstaller | Windows executable generation |

The application itself does not require third-party Python packages to run from source.

---

# 🎯 WHO IS VOLTDESK FOR?

VoltDesk is useful for:

- ⚡ Electronics students
- 🔧 Electrical apprentices
- 💡 Electronics hobbyists
- 🖥️ Technicians
- 📚 People learning electrical engineering
- 🧪 Anyone interested in electronics

---

# 🛠️ FUTURE DEVELOPMENT

VoltDesk is a project that can continue growing.

Possible future features:

- 🔬 Interactive circuit simulator
- 📐 Circuit diagram editor
- 🔋 Battery calculator
- ⚙️ Transistor calculator
- 💡 Diode calculator
- 📊 More advanced electrical calculations
- 📚 Integrated electronics learning section
- 🧰 Component database
- 🌐 Additional language support

---

# 🤝 CONTRIBUTIONS

Contributions, suggestions and improvements are welcome!

If you find a bug or have an idea for a new feature, feel free to open an issue or submit a pull request.

Let's make electronics easier to understand together!

---

# 📜 LICENSE

VoltDesk is released under the **MIT License**.

You are free to use, modify and distribute this project under the terms of the license.

See the `LICENSE` file for more information.

---

# ⚡ VOLTDESK — LEARN. CALCULATE. BUILD. ⚡

**Made for everyone who wants to understand electronics.**

🔌 Electricity made easier.

💡 Ideas turned into circuits.

🚀 Powered by curiosity.
