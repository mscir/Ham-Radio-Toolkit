Digital Modes mention modes/sw (e.g. Olivia, Fidget, etc.) that are not included on the Links page. I may need a new section: S/W or? 

i don't currently have any content about some of the modes or software (e.g. olivia, fidget, etc.) mentioned in the digital modes page. does the links page need a new section or can these be added to existing sections?

You can add them to existing sections rather than create a new top-level Links section. The best structure is to make your existing digital-mode/software area a little more complete, then cross-link each tool from the relevant mode card.
Recommended organization
Existing section	Add
Digital Modes	FT8, FT4, JS8Call, Olivia, Q65, WSPR, RTTY, SSTV, APRS
Software & Interfaces	WSJT-X, Fldigi, VarAC, Winlink Express, VARA, MMSSTV, QSSTV, N1MM+, APRS apps
Emergency Communications	Winlink, VARA HF/FM, JS8Call, packet resources
Propagation	WSPRnet, Reverse Beacon Network, PSK Reporter
Satellite	AMSAT satellite status and tracking tools

That keeps modes distinct from the software used to operate them. For example, Olivia is a digital mode, while Fldigi is one application that can encode/decode it; Fldigi supports Olivia along with many other amateur-radio modes.
Add a compact “Digital software” block

If your Links page already has cards or grouped links, add a subsection such as:

xml
<h3 class="links-section-title">Digital Mode Software</h3>

<div class="links-grid">
  <a class="link-card" href="https://wsjt.sourceforge.io/wsjtx.html" target="_blank" rel="noopener">
    <div class="link-name">WSJT-X</div>
    <div class="link-desc">FT8, FT4, Q65, WSPR, and other weak-signal modes.</div>
  </a>

  <a class="link-card" href="http://www.w1hkj.com/" target="_blank" rel="noopener">
    <div class="link-name">Fldigi</div>
    <div class="link-desc">Multi-mode software for Olivia, RTTY, PSK, MFSK, CW, and more.</div>
  </a>

  <a class="link-card" href="https://js8call.com/" target="_blank" rel="noopener">
    <div class="link-name">JS8Call</div>
    <div class="link-desc">Weak-signal keyboard messaging, relays, and store-and-forward tools.</div>
  </a>

  <a class="link-card" href="https://www.varac-hamradio.com/" target="_blank" rel="noopener">
    <div class="link-name">VarAC</div>
    <div class="link-desc">HF chat, messaging, and file-transfer application using the VARA modem.</div>
  </a>

  <a class="link-card" href="https://winlink.org/" target="_blank" rel="noopener">
    <div class="link-name">Winlink</div>
    <div class="link-desc">Radio email, forms, and message-routing resources.</div>
  </a>

  <a class="link-card" href="https://rosmodem.wordpress.com/" target="_blank" rel="noopener">
    <div class="link-name">VARA</div>
    <div class="link-desc">HF and FM sound-card modem used with Winlink and VarAC.</div>
  </a>
</div>

Add only the missing mode links

You do not need a separate link for every individual mode. A useful rule:

    Add dedicated links for a mode only when there is a primary operating resource, live activity map, or official software.

    Otherwise, list the mode inside a general digital-mode guide or software entry.

For your selector, these are the most useful additions:

    FT8 / FT4 / Q65 / WSPR: WSJT-X.

    Olivia / RTTY: Fldigi.

    JS8Call: JS8Call.

    VarAC: VarAC and VARA.

    Winlink: Winlink Express and VARA.

    SSTV: MMSSTV for Windows and QSSTV for Linux.

    APRS: APRS.fi, APRSdroid, Dire Wolf, or your preferred local APRS resource.

    Contesting: N1MM Logger+.

    Propagation: WSPRnet and Reverse Beacon Network.

Add direct links in recommendations

You can also make the bolded software names in GOAL_RECS clickable, without cluttering the Links page. For example:

js
body: `
  <a href="https://sourceforge.net/projects/fldigi/"
     target="_blank" rel="noopener"><strong>Fldigi</strong></a>
  supports Olivia, RTTY, PSK, MFSK, CW, and other sound-card modes.
`

Use that sparingly—one or two links per recommendation card is enough. Fldigi is specifically relevant because it supports Olivia, RTTY, CW, PSK, MFSK, and additional amateur digital modes.

Also, the software name is Fldigi, not “fidget.”


verify: Your First QSO, change which items in the highlighted lists (3) so they correspond to the entered text e.g. 322


verify all links in links page
