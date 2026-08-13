# Ham Radio Toolkit 📻

An all-in-one, responsive web dashboard designed for amateur radio operators. The toolkit provides real-time solar data, operating guides, reference tables, calculators, and localized utilities to enhance your shack experience.

🚀 **Live Toolkit:** [https://mscir.github.io/Ham-Radio-Toolkit/](https://mscir.github.io/Ham-Radio-Toolkit/)

---

## 🪪 Start Here: Select Your License Class

When you first open the toolkit, choose your current U.S. amateur-radio license class:

1. Open **Frequency Privileges** from the bottom of the left menu.
2. Select **Technician**, **General**, or **Amateur Extra**.
3. Your selection is saved automatically in your browser for up to five years.

The toolkit uses your selected license class to personalize the Frequency Privileges reference, frequency checker, operating profile, and other license-aware guidance.

**Important:** The toolkit is designed for U.S. amateur radio operators and uses FCC Part 97 / ARRL reference material. Always verify your current privileges, regional restrictions, band allocations, and local operating rules before transmitting.

---

## ⚙️ Fully Customizable Workspace

The dashboard features a **Customizable Menu Layout**. Operators can tailor the interface to their operating style:
*   Click the **Gear Icon (⚙️)** in the top menu bar to open the customization drawer.
*   Toggle individual widgets or entire sections (**Live Data**, **Operating**, **Reference**, **Tools & Calculators**) to show or hide them.
*   Your layout choices save automatically in your browser's cookies and persist for up to 5 years, keeping your workspace uncluttered.
*   Your selected **U.S. license class** is also remembered and shown in the sidebar as your current operating profile. Click the profile card at any time to return to the Frequency Privileges panel and change it.

---

## 🛠️ Feature Summary

### 1. Live Space Weather & Propagation
*   **Dynamic NOAA SWPC Integration:** Feeds live data streams straight from the NOAA Space Weather Prediction Center.
*   **Real-Time Solar Indices:** Tracks Solar Flux (F10.7), Sunspot Numbers (SSN), Kp/K-Index, A-Index, X-Ray Flux levels, IMF Bz, and Solar Wind speeds.
*   **Calculated Band Conditions:** Locally computes HF band condition estimates for daytime/nighttime paths alongside an Aurora Activity/Latitude predictor.
*   **Propagation Path Tool:** Evaluates point-to-point path opportunities across standard HF bands using live metrics.

### 2. Operating & Station Tools
*   **Band Activity Guide:** Highlights conventional on-air frequencies by mode (CW, Data, SSB, AM) to find where operators congregate.
*   **First QSO Step-by-Step:** Quick-reference operating scripts and checklists for SSB Phone, FM Repeaters, Simplex, and FT8 modes.
*   **Interactive QSO Log:** Log contacts locally right from the dashboard. Data persists across browser reloads and features an instantaneous **ADIF Export** for compatibility with major logging suites (Log4OM, HRD, WSJT-X).
*   **Repeater & Net Finder:** Search tools integrated with external directory frameworks to locate local systems, offsets, and CTCSS/DCS subaudible tones.
*   **Digital Mode Selector:** Guidance path recommendations for digital operations like Winlink, JS8Call, or FT8 based on your goals.

### 3. On-Air Language, Reference, & CW Practice
*   **🔊 Interactive CW Practice Module:** Learn Morse code by ear and sight. Features full audio playback for individual characters, dynamic words, a live speed slider (WPM), and an interactive **Drill Mode** with statistics tracking to test your proficiency.
*   **💬 Common Q-Codes Lookup:** A comprehensive reference table of marine and amateur radio shorthand codes (e.g., QRM, QRN, QRP, QTH, QRZ) complete with precise operational meanings.
*   **📶 Radio Signal Codes (RST System):** A built-in guide outlining the standard 3-digit signal reporting framework for Readability (1–5), Strength (1–9), and Tone (1–9). Includes an interactive text-to-phonetic spelling translator tool.
*   **📋 License Profile & Privilege Checker:** Select Technician, General, or Amateur Extra to personalize the dashboard's operating profile. Includes an interactive frequency checker and class-specific U.S. privilege reference.
*   **🌍 DXCC Prefix & CQ Zone Lookup:** Identify entity countries, great circle bearings, distance, and CQ/ITU zones directly via grid locator criteria.

### 4. Technical Calculators
*   **Maidenhead Grid Square Calculator:** Rapid conversions between standard Decimal Coordinates and 4-to-6 character grid locators.
*   **Antenna Dimension Engine:** Length element outputs for Half-Wave Dipoles, Quarter-Wave Verticals, 3-Element Yagis, and Small Transmitting Magnetic Loops based on target frequency.
*   **RF Unit Converter:** Bidirectional unit conversions for Watts, milliwatts, dBm, S-Units, and antenna gain variables (dBd ↔ dBi).
*   **RF Exposure Estimator:** Simplified compliance workspace mapping power, gain, distance, and duty cycle against FCC safety parameters.
*   **Shack Grounding Guide:** Structured overview detailing rules for combining electrical code safety ground structures with proper low-impedance RF earth connections.

---

## ⚡ Technical Highlights

*   **100% Static & Fast:** Built entirely with native HTML, CSS, and modern JavaScript. Requires zero backend database overhead or installation extensions.
*   **CORS Clean Data Pipelines:** Leverages secure, real-time JSON web queries straight to authoritative server feeds without routing proxies.
*   **Client-Side Persistence:** Remembers your selected license class, menu layout, logged contacts, and coordinate defaults using browser cookies and local storage. No account or server database is required.
*   **Responsive Framework:** Layout smoothly shifts between horizontal desktop multi-panels and stacked mobile views for tablet or portable on-the-go operation.

---

## 🐛 Reporting Issues & Contributing

Feedback, bug reports, and suggestions are highly encouraged to help keep this toolkit accurate and helpful for the ham community! 

If you spot a calculation error, a broken tool feed, a typo, or have a feature idea:
1. Navigate to the **[Issues](https://github.com/mscir/Ham-Radio-Toolkit/issues)** tab.
2. Click the green **New Issue** button.
3. Provide a brief description of the issue or your suggestion, and submit it.

*You will automatically be notified via email whenever there are updates or responses regarding your submission.*

---

## 📝 Compliance Disclaimer
*Data parsed across regulatory panels is synchronized against ARRL and FCC Part 97 rule structures. Operators must always verify explicit regional operating privileges against current regulatory guidelines before transmitting.*
