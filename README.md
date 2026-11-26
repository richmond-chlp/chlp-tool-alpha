# CHLP Program Estimator and Funder's Ledger (open beta)

An open tool from the Climate Health Ledger Project. An organization enters what a climate program delivers and what it costs. The tool returns the health gained, in disability-adjusted life years (DALYs) averted a year, and a cost per DALY as a best, a central and a worst case. Where the program cuts emissions, it also gives a cost for each metric ton of CO2e cut, on its own measure. Every result shows its inputs, sources and factors, so whoever reads it can check it.

## Use it

Open the Program Estimator at https://tool.climatehealthledger.org/, or download `index.html` and open it in a browser. The earlier address, richmond-chlp.github.io/chlp-tool-alpha, forwards there. An entry takes about 30 minutes.

The page first asks what the implementer's funders measure: health, climate or both. The answer sets which result leads and which causal chain opens; the other ledger still shows beside it. In the implementer's view, the page then goes one step at a time, from what the program delivers to its costs, adjustments and emissions, and each step folds to a summary once done. "Show every step" opens them all, and a bar at the foot of the screen keeps the result in view. Two examples show how it works: solar-powered oxygen in one hospital, and, when climate leads, ten electric school buses.

An organization that has filled in the CHLP spreadsheet can open it on the page, and the page fills in its own fields. After finishing on the page, it can save the entry as the spreadsheet, filled in, for a funder who wants a traditional submission.

The same estimate reads at three depths. The implementer's view gives the result. The program officer's view adds the detailed metrics. The researcher's view shows the whole calculation as a sheet, with each figure's source and the passage behind it.

## The three ledgers

Each result is read on three ledgers, each in its own unit: health in DALYs, climate in metric tons of CO2e, and animal welfare. Health and climate are the work today. The animal welfare ledger is shown and marked "Not yet assessed", with no figure.

The climate figure comes after the share that would have happened anyway, as the health figure does. Its cost for each metric ton of CO2e cut is read against CHLP's climate bar of $332, what buyers pay to remove carbon. That bar measures no damage, and it is never added to the health measure.

## The causal chain

Under each result, the page draws the causal chain: from what the money pays for, link by link, to the health it buys. Each link says what supports it: a study, the user's own records, an assumption, or a figure worked out from others. Links that could move the result across the line it is read against are marked. A user can add a note or a study to any link, and the chain travels with the entry. The climate chain can be shown below it, and is hidden at first.

Health and climate can also be read together, through a rate that converts tons of CO2e to DALYs. The page opens at CHLP's default of about 3,060 metric tons for each DALY, and the reader can change it. The evidence supports about 500 to about 8,200, so this reading never replaces the two ledgers or the headline result. Animal welfare enters no combined figure.

## The Funder's Ledger

`chlp-funder-ledger.html`, the Funder's Ledger, is a first form of a page for funders. It reads several shared entries side by side and compares peers in one portfolio. It stores nothing; entries reach it as copied text or as files the implementer sends. The funder's copy of an entry names this page's address. Placeholder entries show how it reads; every name and figure on them is invented.

## What happens to what you enter

- The page runs in your browser. It loads nothing from another address, and it stores and sends nothing unless you choose "Send to CHLP".
- Sharing is optional. To share an entry with CHLP, tick "To CHLP" under "Your entry", answer the three questions on consent, read what CHLP stores, and press "Send to CHLP". You can instead copy the entry, or save it as a file, and send it to richmond@climatehealthledger.org.
- When you send it, CHLP keeps the entry in a private spreadsheet that it shares with no one. If you answered "Yes if anonymized", the page removes your program's name, organization, place, written descriptions, notes and tracker before sending. If you answered "No", only your feedback on the tool is sent. Your contact, if you give one, is kept apart from the entry and never published. The page shows a receipt, and CHLP deletes the entry on request.
- An entry that reaches CHLP without the three answers on consent, by any route, is read as feedback only, and CHLP keeps no copy of it.
- Every result carries a label: "Your own modeled estimate. CHLP has not checked it."
- CHLP checks shared entries against the implementer's records, only where the implementer agrees.

## Browsers

Each page is about 1.3 MB and carries its own PDF reader for the studies behind the figures, and its own reader and writer for spreadsheets. Both need a recent browser: Safari 16.4 or later, Firefox 113 or later, or a current Chrome or Edge. In an older browser the rest of the page works, and the study reader and the spreadsheet buttons say they cannot open.

## Status

Beta 0.1, November 23, 2026, built from the CHLP spreadsheet, version 0.28, November 25, 2026. The tool is in open beta: anyone who wants to test it can, on any intervention, and give feedback. Its factors follow CHLP's assessments as issued on November 25, 2026, and every source names its assessment's current version. Version 0.28 asks which ledger leads, shows the co-benefit for each $1 million spent with health read against the $100 reference point and climate against its bar, goes one step at a time for implementers, reads and writes the CHLP spreadsheet, and lets an implementer send an entry to CHLP after consent. No cost per DALY has changed. For programs in the United States, the result is also set beside the US national bar of about $760,000 for a healthy year, the federal value at September 2026 prices. On November 26, 2026, the pages took CHLP's logo, one header and footer, results to three significant figures, and CHLP's assessments named in words; they are served from tool.climatehealthledger.org. A test version: figures and wording may change.

## License

- **Code** (the page's markup, styles and script): the MIT License, in `LICENSE`.
- **Text, factors and figures:** Creative Commons Attribution 4.0 International, in `LICENSE-CONTENT`. Reuse them with credit to the Climate Health Ledger Project, a link to the license, and a note of any changes.

## Contact

Richmond Chua, Climate Health Ledger Project: richmond@climatehealthledger.org. Corrections to an entry or a factor go to the same address, and each one is logged.
