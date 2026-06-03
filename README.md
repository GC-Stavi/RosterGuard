# RosterGuard / RosterCheck

Independent roster analysis and EBA compliance checker for Alliance Airlines crew.

## What it does
- Checks pilot and cabin crew rosters against Enterprise Agreement provisions
- Flags potential rule deviations: early starts, minimum RDOs, consecutive duty limits, rest periods
- Exports roster to calendar (ICS format)
- Used by 1,000+ crew members at Alliance Airlines

## Background
Built by Craig Abela, an E190 Line Captain at Alliance Airlines with 31 years of aviation experience.  
Developed independently to give crew an accessible, plain-language tool for understanding their EA entitlements.

## Tech stack
HTML / JavaScript — browser-based, no install required

## Live tool
https://rostercheck.netlify.app

## Project status
The original pay calculation tool (PremiumRosterCheck) has been sidelined due to privacy considerations — roster data contains sensitive personal information and the tool required server-side processing. The core compliance checker (RosterCheck) remains fully functional and is actively maintained. All roster analysis runs entirely in the browser; no data is ever transmitted or stored.

## Note
This tool is not affiliated with Alliance Airlines or any union body.  
It provides general guidance only. Always refer to your official EA document for definitive interpretation.
