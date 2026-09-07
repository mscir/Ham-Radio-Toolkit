# Ham Radio Toolkit 📻

An all-in-one, responsive web dashboard designed for amateur radio operators. The toolkit provides real-time solar data, operating guides, reference tables, calculators, and localized utilities to enhance your shack experience.

🚀 **Live Toolkit:** [https://mscir.github.io/Ham-Radio-Toolkit/](https://mscir.github.io/Ham-Radio-Toolkit/)

---

## 🪪 Start Here: Select Your License Class & Enter Your Location

When you first open the toolkit, choose your current U.S. amateur-radio license class:

1. Open **Frequency Privileges** from the bottom of the left menu.
2. Select **Technician**, **General**, or **Amateur Extra**.
3. Your selection is saved automatically in your browser for up to five years.
4. Open **Grid Square Calc** using the menu.
5. Enter your latitude and longitude, grid square, or if you don't know them, use the link to the page that will allow you to find your location on a map, and display your location data.
6. Enter your location data into the Grid Square Calculator page and it will be stored for up to five years. 

The toolkit uses your selected license class to personalize the Frequency Privileges reference, frequency checker, operating profile, and other license-aware guidance. Also your location will be used if you use the DXCC Prefix Lookup page or the Repeater Finder page. 

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

## 🔎 Frequency Privileges Data Methodology

The **Frequency Privileges** reference and authorization checker are designed as a practical U.S. amateur-radio operating aid. Their displayed frequency ranges, license-class access, operating-mode guidance, power limits, and special-condition notes are derived from and cross-checked against the current FCC Amateur Radio Service rules in **47 CFR Part 97**, with the ARRL’s U.S. amateur-band allocation material used as a readability and presentation cross-reference.

### Primary regulatory sources

The FCC’s electronic Code of Federal Regulations (eCFR) is the controlling source used for rule interpretation. The toolkit’s privilege data is reviewed against the following Part 97 provisions:

- **§97.301 — Authorized frequency bands:** License-class frequency privileges, amateur allocations, and applicable ITU Region 2 limitations.
- **§97.303 — Frequency sharing requirements:** Secondary allocations, geographic restrictions, protection requirements, and other shared-use conditions.
- **§97.305 — Authorized emission types:** Permitted emission categories and band-specific limitations.
- **§97.307 — Emission standards:** Occupied-bandwidth and technical emission requirements, including applicable RTTY/data limitations.
- **§97.309 — RTTY and data emission codes:** Digital-code requirements relevant to RTTY/data operation.
- **§97.313 — Transmitter power standards:** General maximum power limits and exceptions, including band- or license-specific power restrictions.

The project also cross-references the ARRL’s current U.S. amateur-band allocation resources. ARRL material is used to help present the FCC rules in an operator-friendly format; where a simplified chart or explanatory material differs from the FCC rule text, the FCC rule text controls.

### How the data is checked

For each displayed band or frequency segment, the review process is intended to verify the following fields independently:

1. **Frequency boundaries** — Confirm lower and upper limits against the appropriate Part 97 table, rule paragraph, or channel specification.
2. **License-class eligibility** — Confirm whether Technician, General, and/or Amateur Extra operators may transmit in that segment.
3. **Mode or emission guidance** — Compare the displayed CW, phone, RTTY/data, image, or other emission guidance with §97.305 and related requirements.
4. **Power limits** — Check the normal maximum power rule and every applicable exception, such as lower limits, ERP/EIRP limits, PEP limits, or license-class-specific limits.
5. **Special conditions** — Identify restrictions that deserve an on-screen warning, including secondary status, geographic limitations, coordination requirements, notification requirements, bandwidth limits, channelized operation, or protection of primary users.
6. **Checker behavior** — Test representative authorized and unauthorized inputs for each license class and operating mode to confirm that the interactive checker returns a result consistent with the same underlying reference data.
7. **Reader-facing wording** — Review labels and notes so that the interface distinguishes FCC authorization from voluntary band-plan practice, local coordination requirements, and operator judgment.

### Scope and limitations

The toolkit is not an official FCC publication, legal advice, or a substitute for the control operator’s responsibility under Part 97. A frequency appearing in an amateur allocation does not, by itself, guarantee that every emission, bandwidth, power level, operating location, or operating purpose is permitted.

Before transmitting, operators should verify the current FCC text, applicable regional or geographic restrictions, band-specific conditions, station control requirements, and any local repeater or coordination rules. The Frequency Checker is intended to highlight common authorization questions and conditions—not to provide a final legal determination.

### Accuracy and maintenance commitment

The project aims to maintain a high-confidence, operator-useful representation of the FCC rules through source-based review, field-by-field cross-checking, and regression testing of the displayed tables and checker results. The full Frequency Privileges audit is documented as an ongoing maintenance process: reported discrepancies, FCC rule changes, and credible source updates should be reviewed and corrected promptly.

Users who identify a possible discrepancy are encouraged to open a GitHub Issue with the frequency, selected license class, operating mode, displayed result, and the relevant FCC or ARRL source citation.

---

## 📝 Compliance Disclaimer

*Frequency Privileges data is reviewed against current FCC Part 97 requirements and cross-referenced with ARRL U.S. amateur-band allocation material. The FCC’s current eCFR text controls. Operators remain responsible for verifying current frequency, emission, bandwidth, power, location, sharing, and other applicable requirements before transmitting.*
