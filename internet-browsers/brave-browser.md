### Release Notes v1.59.117 (Oct 11, 2023)

### Web3

-   Added Neon EVM preloaded chains. ([#31760](https://github.com/brave/brave-browser/issues/31760))
-   Added method to return "Swap" protocol fees. ([#32464](https://github.com/brave/brave-browser/issues/32464))
-   Added a runtime flag to use staging Ratios service. ([#32043](https://github.com/brave/brave-browser/issues/32043))
-   Enabled Brave Wallet panel V2 by default. ([#32352](https://github.com/brave/brave-browser/issues/32352))
-   Implemented NFT management V2. ([#33095](https://github.com/brave/brave-browser/issues/33095))
-   Updated "Buy" and "Swap" from panel to open in full page view. ([#33353](https://github.com/brave/brave-browser/issues/33353))
-   Updated "Learn more" link in IPFS infobar to open in a new tab. ([#32178](https://github.com/brave/brave-browser/issues/32178))
-   Updated Coinbase On-ramp description. ([#32147](https://github.com/brave/brave-browser/issues/32147))
-   Removed Fantom from preloaded chains. ([#32085](https://github.com/brave/brave-browser/issues/32085))
-   Fixed "Deposit" screen text wrapping in Brave Wallet panel. ([#33425](https://github.com/brave/brave-browser/issues/33425))
-   Fixed NFT images not being shown on the "Deposit" screen. ([#32446](https://github.com/brave/brave-browser/issues/32446))
-   Fixed POAPs not loading successfully. ([#31763](https://github.com/brave/brave-browser/issues/31763))
-   Fixed inability to interact with tooltip text. ([#32015](https://github.com/brave/brave-browser/issues/32015))
-   Fixed alignment of "Asset Group" description on the panel. ([#32504](https://github.com/brave/brave-browser/issues/32504))
-   Fixed the "Portfolio" page to use the correct fiat values for test network assets. ([#31819](https://github.com/brave/brave-browser/issues/31819))

### Rewards

-   Updated "Estimated earnings" to display "Earnings so far". ([#32653](https://github.com/brave/brave-browser/issues/32653))
-   Fixed "Earnings from Ads" on the monthly statement to display a link to the user's custodian dashboard when "Logged Out". ([#31791](https://github.com/brave/brave-browser/issues/31791))

### General

-   Added icons and streamlined the hamburger menu. ([#32089](https://github.com/brave/brave-browser/issues/32089))
-   Added rounded corners to all panels from the navigation bar. ([#32150](https://github.com/brave/brave-browser/issues/32150))
-   Added "Use WireGuard protocol in Brave VPN" setting under brave://settings/system. ([#32002](https://github.com/brave/brave-browser/issues/32002))
-   Added "Make auto-fill available in private windows" setting under brave://settings/autofill. ([#9795](https://github.com/brave/brave-browser/issues/9795))
-   Added Widevine support for Arm64 on Windows. ([#28318](https://github.com/brave/brave-browser/issues/28318))
-   [Security] Updated which origins and URLs trigger debouncing and request-OTR protections as reported on HackerOne by nishimunea. ([#32230](https://github.com/brave/brave-browser/issues/32230))
-   [Security] Block ".onion" domain subresource requests in non-Tor contexts as reported on HackerOne by xiaoyinl. ([#32108](https://github.com/brave/brave-browser/issues/32108))
-   [Security] Fixed crash when loading brave://optimization-guide-internals as reported on HackerOne by jaguilera. ([#31648](https://github.com/brave/brave-browser/issues/31648))
-   Improved password storage backend detection logic on Linux. ([#32314](https://github.com/brave/brave-browser/issues/32314))
-   Updated Brave VPN hamburger menu entries. ([#33027](https://github.com/brave/brave-browser/issues/33027))
-   Updated the Wayback Machine infobar to display a "Don't show again" checkbox. ([#32404](https://github.com/brave/brave-browser/issues/32404))
-   Removed disabled features from DevTools. ([#32187](https://github.com/brave/brave-browser/issues/32187))
-   Fixed crash when adding scriptlet injection filters with too many arguments. ([#32916](https://github.com/brave/brave-browser/issues/32916))
-   Fixed broken flag for "Enable extension network blocking" under brave://flags. ([#32569](https://github.com/brave/brave-browser/issues/32569))
-   Fixed New Tab Page background image(s) being skipped after startup in certain cases. ([#32577](https://github.com/brave/brave-browser/issues/32577))
-   Fixed missing toggle for Brave VPN on the hamburger menu. ([#32703](https://github.com/brave/brave-browser/issues/32703))
-   Fixed incorrect state being displayed for Brave VPN toolbar button in certain cases. ([#32542](https://github.com/brave/brave-browser/issues/32542))
-   Upgraded Chromium to 118.0.5993.70. ([#33556](https://github.com/brave/brave-browser/issues/33556)) ([Changelog for 118.0.5993.70](https://chromium.googlesource.com/chromium/src/+log/117.0.5938.153..118.0.5993.70?pretty=fuller&n=1000))
