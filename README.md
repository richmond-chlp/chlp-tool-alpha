# The CHLP tool (beta)

An open tool from the Climate Health Ledger Project. An organization enters what a climate program delivers and what it costs. The tool returns the health gained, in disability-adjusted life years (DALYs) averted a year, and a cost per DALY as a best, a central and a worst case. Every result shows its inputs, sources and factors, so whoever reads it can check it.

## Use it

Open the published page at https://richmond-chlp.github.io/chlp-tool-alpha/, or download `index.html` and open it in a browser. An entry takes about 30 minutes.

The same estimate reads at three depths. The implementer's view gives the result. The program officer's view adds the detailed metrics. The researcher's view shows the whole calculation as a sheet, with each figure's source and the passage behind it.

## The three ledgers

Each result is read on three ledgers, each in its own unit: health in DALYs, climate in metric tons of CO2e, and animal welfare. Health and climate are the work today. The animal welfare ledger is shown and marked "Not yet assessed", with no figure.

The climate figure comes after the share that would have happened anyway, as the health figure does. Its cost for each metric ton of CO2e cut is read against CHLP's climate bar of $332, what buyers pay to remove carbon. That bar measures no damage, and it is never added to the health bar.

## The causal chain

Under each result, the page draws the causal chain: from what the money pays for, link by link, to the health it buys. Each link says what supports it: a study, the user's own records, an assumption, or a figure worked out from others. Links that could move the result across the bar are marked. A user can add a note or a study to any link, and the chain travels with the entry. The climate chain can be shown below it, and is hidden at first.

Health and climate can also be read together, through a rate that converts tons of CO2e to DALYs. The page opens at CHLP's default of about 3,060 metric tons for each DALY, and the reader can change it. The evidence supports about 500 to about 8,200, so this reading never replaces the two ledgers or the headline result. Animal welfare enters no combined figure.

## The funder's ledger

`chlp-funder-ledger.html` is a first form of a page for funders. It reads several shared entries side by side and compares peers in one portfolio. It stores nothing; entries reach it as copied text or as files the implementer sends. Placeholder entries show how it reads; every name and figure on them is invented.

## What happens to what you enter

- The page runs in your browser. It stores nothing, sends nothing and loads nothing from another address.
- Sharing is optional. To share an entry, copy it from the foot of the page and send it to richmond@climatehealthledger.org, with your answers to the three questions on consent.
- Every result carries a label: "Your own modeled estimate. CHLP has not checked it."
- CHLP checks shared entries against the implementer's records, only where the implementer agrees.

## Browsers

Each page is about 1 MB and carries its own PDF reader for the studies behind the figures. The reader needs a recent browser: Safari 16.4 or later, Firefox 113 or later, or a current Chrome or Edge. In an older browser the rest of the page works and the study reader says it cannot open.

## Status

Beta 0.1, November 23, 2026, built from the CHLP spreadsheet, version 0.27, November 25, 2026. The tool is in open beta: anyone who wants to test it can, on any intervention, and give feedback. Its factors follow CHLP's assessments as issued on November 25, 2026, and every source names its assessment's current version. Version 0.27 takes the share that would have happened anyway off the climate figure and reads a cost for each metric ton of CO2e cut against $332. Coal mine methane destroyed now counts 27.0 metric tons of CO2e a metric ton, net of the CO2 the burning forms. The page warns, and only warns, when a cost for each unit is more than five times above or below its assessment's own. The cookstove credits entry's worst case now takes the published rates of adoption and use, from screen N1. No other cost per DALY has changed. For programs in the United States, the result is also set beside the US yardstick of $759,819 for a healthy year, the federal value at September 2026 prices. A test version: figures and wording may change.

## License

- **Code** (the page's markup, styles and script): the MIT License, in `LICENSE`.
- **Text, factors and figures:** Creative Commons Attribution 4.0 International, in `LICENSE-CONTENT`. Reuse them with credit to the Climate Health Ledger Project, a link to the license, and a note of any changes.

## Contact

Richmond Chua, Climate Health Ledger Project: richmond@climatehealthledger.org. Corrections to an entry or a factor go to the same address, and each one is logged.
