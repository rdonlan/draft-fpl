# BMS FPL Future Pick Tracker

A draft-pick ownership page built from the workbook's `Drafting Order` tab and reconciled against the trade ledger.

<details open>
<summary><h2>Manager Pick Lookup</h2></summary>

Choose a year and manager to see exactly which future picks they hold and which of their own picks they no longer control.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- The lookup counts rounds `3rd` through `15th`; the `1st` and `2nd` rounds are keeper slots.
- **Picks They Have** includes both their own picks and picks acquired from other managers.
- **Own Picks They Do Not Have** shows original picks that are currently owed away.
- **Incoming Picks From Other Managers** is the acquired-pick subset of the picks they hold.
- **Trade Recap** stays compact on the page; hover the pill to see the condensed trade context behind that pick movement.

</details>

<div class="pick-lookup" data-pick-lookup>
<div class="pick-controls">
<label class="pick-control"><span>Year</span><select data-pick-year>
<option value="2026" selected>2026</option>
<option value="2027">2027</option>
</select></label>
<label class="pick-control"><span>Manager</span><select data-pick-manager>
<option value="Donny" selected>Donny</option>
<option value="Justin">Justin</option>
<option value="House">House</option>
<option value="Levi">Levi</option>
<option value="Luke">Luke</option>
<option value="Julius">Julius</option>
<option value="Drake">Drake</option>
<option value="Chabo">Chabo</option>
<option value="Ethan">Ethan</option>
<option value="Dylan">Dylan</option>
</select></label>
<div class="pick-lookup-status" data-pick-lookup-status></div>
</div>
<div class="pick-profile-list">
<section class="pick-profile is-active" data-pick-profile data-year="2026" data-manager="Donny">
<div class="pick-profile-heading">
<div><h3>Donny - 2026</h3><p>8 picks, -5 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>8</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-5</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>1</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>6</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Ethan</td><td>From Ethan</td></tr>
<tr><td>11th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Donny</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Drake</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Donny sent 2026 4th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick" aria-label="2024-25 Postseason: Donny sent 2026 4th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick">via Donny to Drake</span></td></tr>
<tr><td>6th</td><td>Ethan</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 22: Donny sent 6th-round pick to Ethan. Trade: Donny sent Kushannov (MCI), 6th-round pick; Ethan sent Timber (ARS)" aria-label="2025-26 GW 22: Donny sent 6th-round pick to Ethan. Trade: Donny sent Kushannov (MCI), 6th-round pick; Ethan sent Timber (ARS)">via Donny to Ethan</span></td></tr>
<tr><td>8th</td><td>Drake</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Donny sent 2026 8th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick" aria-label="2024-25 Postseason: Donny sent 2026 8th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick">via Donny to Drake</span></td></tr>
<tr><td>9th</td><td>Julius</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 32: Donny sent 2026 9th-round pick to Julius. Trade: Julius sent Calvert-Lewin (LEE); Donny sent 2026 9th-round pick, Muniz (FUL)" aria-label="2025-26 GW 32: Donny sent 2026 9th-round pick to Julius. Trade: Julius sent Calvert-Lewin (LEE); Donny sent 2026 9th-round pick, Muniz (FUL)">via Donny to Julius</span></td></tr>
<tr><td>10th</td><td>Dylan</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 Draft Day: Donny sent 2026 10th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)" aria-label="2025-26 Draft Day: Donny sent 2026 10th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)">via Donny to Dylan</span></td></tr>
<tr><td>12th</td><td>Dylan</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 Draft Day: Donny sent 2026 12th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)" aria-label="2025-26 Draft Day: Donny sent 2026 12th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)">via Donny to Dylan</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>10th</td><td>Ethan</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 Preseason: Ethan sent 10th-round pick (via Ethan) to Donny. Trade: Donny sent Mamardashvili (LIV); Ethan sent 10th-round pick (via Ethan), Vicario (TOT)" aria-label="2025-26 Preseason: Ethan sent 10th-round pick (via Ethan) to Donny. Trade: Donny sent Mamardashvili (LIV); Ethan sent 10th-round pick (via Ethan), Vicario (TOT)">via Ethan to Donny</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Justin" hidden>
<div class="pick-profile-heading">
<div><h3>Justin - 2026</h3><p>9 picks, -4 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>9</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-4</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>4</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Justin</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Dylan</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Levi sent 2026 3rd-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 3rd-round picks." aria-label="2024-25 Postseason: Levi sent 2026 3rd-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 3rd-round picks.">via Levi to Dylan</span></td></tr>
<tr><td>6th</td><td>Julius</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Justin sent 2026 6th-round pick to Julius. Trade: Julius sent Garner (EVE); Justin sent 2026 6th-round pick, João Gomes (WOL)" aria-label="2025-26 GW 31: Justin sent 2026 6th-round pick to Julius. Trade: Julius sent Garner (EVE); Justin sent 2026 6th-round pick, João Gomes (WOL)">via Justin to Julius</span></td></tr>
<tr><td>7th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 26: Justin sent 2026 7th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick" aria-label="2025-26 GW 26: Justin sent 2026 7th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick">via Justin to Levi</span></td></tr>
<tr><td>8th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Justin sent 2026 8th-round pick to Levi. Trade: Levi sent O&#x27;Reilly (MC); Justin sent 2026 8th-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Justin sent 2026 8th-round pick to Levi. Trade: Levi sent O&#x27;Reilly (MC); Justin sent 2026 8th-round pick, matching players to be dropped">via Justin to Levi</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="House" hidden>
<div class="pick-profile-heading">
<div><h3>House - 2026</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>1</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>1</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>House</td><td>Own pick</td></tr>
<tr><td>4th</td><td>House</td><td>Own pick</td></tr>
<tr><td>6th</td><td>House</td><td>Own pick</td></tr>
<tr><td>7th</td><td>House</td><td>Own pick</td></tr>
<tr><td>8th</td><td>House</td><td>Own pick</td></tr>
<tr><td>9th</td><td>House</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Levi</td><td>From Levi</td></tr>
<tr><td>10th</td><td>House</td><td>Own pick</td></tr>
<tr><td>11th</td><td>House</td><td>Own pick</td></tr>
<tr><td>12th</td><td>House</td><td>Own pick</td></tr>
<tr><td>13th</td><td>House</td><td>Own pick</td></tr>
<tr><td>14th</td><td>House</td><td>Own pick</td></tr>
<tr><td>15th</td><td>House</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>5th</td><td>Dylan</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Levi sent 2026 5th-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks." aria-label="2024-25 Postseason: Levi sent 2026 5th-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks.">via Levi to Dylan</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>10th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Levi sent 2026 10th-round pick to House. Trade: Levi sent 2026 10th-round pick; House sent 2025 12th-round pick, 13th-round pick, 14th-round pick" aria-label="2024-25 Postseason: Levi sent 2026 10th-round pick to House. Trade: Levi sent 2026 10th-round pick; House sent 2025 12th-round pick, 13th-round pick, 14th-round pick">via Levi to House</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Levi" hidden>
<div class="pick-profile-heading">
<div><h3>Levi - 2026</h3><p>16 picks, +3 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>16</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+3</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>5</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>2</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>3rd</td><td>Luke</td><td>From Luke</td></tr>
<tr><td>5th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>7th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Luke</td><td>From Luke</td></tr>
<tr><td>8th</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>8th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Luke</td><td>From Luke</td></tr>
<tr><td>13th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Levi</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Ethan</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 24: Levi sent 4th-round pick to Ethan. Trade: Levi sent Damsgaard (BRE), 4th-round pick; Ethan sent Mbuemo (MU)" aria-label="2025-26 GW 24: Levi sent 4th-round pick to Ethan. Trade: Levi sent Damsgaard (BRE), 4th-round pick; Ethan sent Mbuemo (MU)">via Levi to Ethan</span></td></tr>
<tr><td>10th</td><td>House</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Levi sent 2026 10th-round pick to House. Trade: Levi sent 2026 10th-round pick; House sent 2025 12th-round pick, 13th-round pick, 14th-round pick" aria-label="2024-25 Postseason: Levi sent 2026 10th-round pick to House. Trade: Levi sent 2026 10th-round pick; House sent 2025 12th-round pick, 13th-round pick, 14th-round pick">via Levi to House</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Luke</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Luke sent 2026 3rd-round pick to Levi. Trade: Levi sent Mbuemo (MU); Luke sent 2026 3rd-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Luke sent 2026 3rd-round pick to Levi. Trade: Levi sent Mbuemo (MU); Luke sent 2026 3rd-round pick, matching players to be dropped">via Luke to Levi</span></td></tr>
<tr><td>7th</td><td>Justin</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 26: Justin sent 2026 7th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick" aria-label="2025-26 GW 26: Justin sent 2026 7th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick">via Justin to Levi</span></td></tr>
<tr><td>7th</td><td>Luke</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Luke sent 2026 7th-round pick to Levi. Trade: Levi sent Konate (LIV), Salah (LIV), Summerville (WHU), Armstrong (WOL); Luke sent 2026 7th-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Luke sent 2026 7th-round pick to Levi. Trade: Levi sent Konate (LIV), Salah (LIV), Summerville (WHU), Armstrong (WOL); Luke sent 2026 7th-round pick, matching players to be dropped">via Luke to Levi</span></td></tr>
<tr><td>8th</td><td>Justin</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Justin sent 2026 8th-round pick to Levi. Trade: Levi sent O&#x27;Reilly (MC); Justin sent 2026 8th-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Justin sent 2026 8th-round pick to Levi. Trade: Levi sent O&#x27;Reilly (MC); Justin sent 2026 8th-round pick, matching players to be dropped">via Justin to Levi</span></td></tr>
<tr><td>12th</td><td>Luke</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 10: Luke sent 12th-round pick to Levi. Trade: Levi sent Simons (TOT); Luke sent Cullen (BUR), 12th-round pick" aria-label="2025-26 GW 10: Luke sent 12th-round pick to Levi. Trade: Levi sent Simons (TOT); Luke sent Cullen (BUR), 12th-round pick">via Luke to Levi</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Luke" hidden>
<div class="pick-profile-heading">
<div><h3>Luke - 2026</h3><p>10 picks, -3 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>10</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-3</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>3</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Luke</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Luke sent 2026 3rd-round pick to Levi. Trade: Levi sent Mbuemo (MU); Luke sent 2026 3rd-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Luke sent 2026 3rd-round pick to Levi. Trade: Levi sent Mbuemo (MU); Luke sent 2026 3rd-round pick, matching players to be dropped">via Luke to Levi</span></td></tr>
<tr><td>7th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Luke sent 2026 7th-round pick to Levi. Trade: Levi sent Konate (LIV), Salah (LIV), Summerville (WHU), Armstrong (WOL); Luke sent 2026 7th-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Luke sent 2026 7th-round pick to Levi. Trade: Levi sent Konate (LIV), Salah (LIV), Summerville (WHU), Armstrong (WOL); Luke sent 2026 7th-round pick, matching players to be dropped">via Luke to Levi</span></td></tr>
<tr><td>12th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 10: Luke sent 12th-round pick to Levi. Trade: Levi sent Simons (TOT); Luke sent Cullen (BUR), 12th-round pick" aria-label="2025-26 GW 10: Luke sent 12th-round pick to Levi. Trade: Levi sent Simons (TOT); Luke sent Cullen (BUR), 12th-round pick">via Luke to Levi</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Julius" hidden>
<div class="pick-profile-heading">
<div><h3>Julius - 2026</h3><p>15 picks, +2 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>15</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+2</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>2</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>7th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Donny</td><td>From Donny</td></tr>
<tr><td>9th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Julius</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>6th</td><td>Justin</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Justin sent 2026 6th-round pick to Julius. Trade: Julius sent Garner (EVE); Justin sent 2026 6th-round pick, João Gomes (WOL)" aria-label="2025-26 GW 31: Justin sent 2026 6th-round pick to Julius. Trade: Julius sent Garner (EVE); Justin sent 2026 6th-round pick, João Gomes (WOL)">via Justin to Julius</span></td></tr>
<tr><td>9th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 32: Donny sent 2026 9th-round pick to Julius. Trade: Julius sent Calvert-Lewin (LEE); Donny sent 2026 9th-round pick, Muniz (FUL)" aria-label="2025-26 GW 32: Donny sent 2026 9th-round pick to Julius. Trade: Julius sent Calvert-Lewin (LEE); Donny sent 2026 9th-round pick, Muniz (FUL)">via Donny to Julius</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Drake" hidden>
<div class="pick-profile-heading">
<div><h3>Drake - 2026</h3><p>15 picks, +2 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>15</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+2</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>2</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Donny</td><td>From Donny</td></tr>
<tr><td>4th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Donny</td><td>From Donny</td></tr>
<tr><td>8th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Drake</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Donny sent 2026 4th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick" aria-label="2024-25 Postseason: Donny sent 2026 4th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick">via Donny to Drake</span></td></tr>
<tr><td>8th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Donny sent 2026 8th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick" aria-label="2024-25 Postseason: Donny sent 2026 8th-round pick to Drake. Trade: Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick">via Donny to Drake</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Chabo" hidden>
<div class="pick-profile-heading">
<div><h3>Chabo - 2026</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Chabo</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Ethan" hidden>
<div class="pick-profile-heading">
<div><h3>Ethan - 2026</h3><p>14 picks, +1 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>14</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+1</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>2</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>1</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Levi</td><td>From Levi</td></tr>
<tr><td>5th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Donny</td><td>From Donny</td></tr>
<tr><td>6th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Ethan</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>10th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 Preseason: Ethan sent 10th-round pick (via Ethan) to Donny. Trade: Donny sent Mamardashvili (LIV); Ethan sent 10th-round pick (via Ethan), Vicario (TOT)" aria-label="2025-26 Preseason: Ethan sent 10th-round pick (via Ethan) to Donny. Trade: Donny sent Mamardashvili (LIV); Ethan sent 10th-round pick (via Ethan), Vicario (TOT)">via Ethan to Donny</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 24: Levi sent 4th-round pick to Ethan. Trade: Levi sent Damsgaard (BRE), 4th-round pick; Ethan sent Mbuemo (MU)" aria-label="2025-26 GW 24: Levi sent 4th-round pick to Ethan. Trade: Levi sent Damsgaard (BRE), 4th-round pick; Ethan sent Mbuemo (MU)">via Levi to Ethan</span></td></tr>
<tr><td>6th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 22: Donny sent 6th-round pick to Ethan. Trade: Donny sent Kushannov (MCI), 6th-round pick; Ethan sent Timber (ARS)" aria-label="2025-26 GW 22: Donny sent 6th-round pick to Ethan. Trade: Donny sent Kushannov (MCI), 6th-round pick; Ethan sent Timber (ARS)">via Donny to Ethan</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Dylan" hidden>
<div class="pick-profile-heading">
<div><h3>Dylan - 2026</h3><p>17 picks, +4 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>17</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+4</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>4</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>3rd</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>4th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>5th</td><td>House</td><td>From House</td></tr>
<tr><td>6th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Donny</td><td>From Donny</td></tr>
<tr><td>10th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Donny</td><td>From Donny</td></tr>
<tr><td>12th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Dylan</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Justin</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Levi sent 2026 3rd-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 3rd-round picks." aria-label="2024-25 Postseason: Levi sent 2026 3rd-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 3rd-round picks.">via Levi to Dylan</span></td></tr>
<tr><td>5th</td><td>House</td><td><span class="trade-recap-pill" tabindex="0" title="2024-25 Postseason: Levi sent 2026 5th-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks." aria-label="2024-25 Postseason: Levi sent 2026 5th-round pick to Dylan. Trade: Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-r... Note: original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks.">via Levi to Dylan</span></td></tr>
<tr><td>10th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 Draft Day: Donny sent 2026 10th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)" aria-label="2025-26 Draft Day: Donny sent 2026 10th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)">via Donny to Dylan</span></td></tr>
<tr><td>12th</td><td>Donny</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 Draft Day: Donny sent 2026 12th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)" aria-label="2025-26 Draft Day: Donny sent 2026 12th-round pick (via Donny) to Dylan. Trade: Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)">via Donny to Dylan</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Donny" hidden>
<div class="pick-profile-heading">
<div><h3>Donny - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Donny</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Justin" hidden>
<div class="pick-profile-heading">
<div><h3>Justin - 2027</h3><p>11 picks, -2 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>11</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-2</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>2</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Justin</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>5th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Justin sent 2027 5th-round pick to Levi. Trade: Levi sent Havertz (ARS), Watkins (AVL); Justin sent 2027 5th-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Justin sent 2027 5th-round pick to Levi. Trade: Levi sent Havertz (ARS), Watkins (AVL); Justin sent 2027 5th-round pick, matching players to be dropped">via Justin to Levi</span></td></tr>
<tr><td>6th</td><td>Levi</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 26: Justin sent 2027 6th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick" aria-label="2025-26 GW 26: Justin sent 2027 6th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick">via Justin to Levi</span></td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="House" hidden>
<div class="pick-profile-heading">
<div><h3>House - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>House</td><td>Own pick</td></tr>
<tr><td>4th</td><td>House</td><td>Own pick</td></tr>
<tr><td>5th</td><td>House</td><td>Own pick</td></tr>
<tr><td>6th</td><td>House</td><td>Own pick</td></tr>
<tr><td>7th</td><td>House</td><td>Own pick</td></tr>
<tr><td>8th</td><td>House</td><td>Own pick</td></tr>
<tr><td>9th</td><td>House</td><td>Own pick</td></tr>
<tr><td>10th</td><td>House</td><td>Own pick</td></tr>
<tr><td>11th</td><td>House</td><td>Own pick</td></tr>
<tr><td>12th</td><td>House</td><td>Own pick</td></tr>
<tr><td>13th</td><td>House</td><td>Own pick</td></tr>
<tr><td>14th</td><td>House</td><td>Own pick</td></tr>
<tr><td>15th</td><td>House</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Levi" hidden>
<div class="pick-profile-heading">
<div><h3>Levi - 2027</h3><p>15 picks, +2 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>15</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+2</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>2</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>5th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>6th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Levi</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Levi</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td>5th</td><td>Justin</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 31: Justin sent 2027 5th-round pick to Levi. Trade: Levi sent Havertz (ARS), Watkins (AVL); Justin sent 2027 5th-round pick, matching players to be dropped" aria-label="2025-26 GW 31: Justin sent 2027 5th-round pick to Levi. Trade: Levi sent Havertz (ARS), Watkins (AVL); Justin sent 2027 5th-round pick, matching players to be dropped">via Justin to Levi</span></td></tr>
<tr><td>6th</td><td>Justin</td><td><span class="trade-recap-pill" tabindex="0" title="2025-26 GW 26: Justin sent 2027 6th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick" aria-label="2025-26 GW 26: Justin sent 2027 6th-round pick to Levi. Trade: Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick">via Justin to Levi</span></td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Luke" hidden>
<div class="pick-profile-heading">
<div><h3>Luke - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Luke</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Luke</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Julius" hidden>
<div class="pick-profile-heading">
<div><h3>Julius - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Julius</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Julius</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Drake" hidden>
<div class="pick-profile-heading">
<div><h3>Drake - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Drake</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Drake</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Chabo" hidden>
<div class="pick-profile-heading">
<div><h3>Chabo - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Chabo</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Chabo</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Ethan" hidden>
<div class="pick-profile-heading">
<div><h3>Ethan - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Ethan</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Ethan</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Dylan" hidden>
<div class="pick-profile-heading">
<div><h3>Dylan - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel pick-panel-have"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Dylan</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Trade Recap</th></tr></thead>
<tbody>
<tr><td colspan="3">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
</div>
</div>
</details>

<details>
<summary><h2>2026 Draft Board</h2></summary>

A draft-board view ordered by reverse 25/26 standings. Each box shows the current owner of that pick.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- Columns are the original pick slots, ordered worst-to-first from the 25/26 league standings.
- The number at the top of each column is the draft slot in that round.
- Every box is colored by the manager who currently owns that pick.
- Grey boxes are surplus picks: each manager can use at most 15 total picks, so after two keeper slots only their first 13 picks shown here are usable. Any 14th+ shown pick is pick 16+ overall and will not be used unless the pick situation changes.
- Rounds `1st` and `2nd` are omitted because those are keeper slots.

</details>

<div class="draft-board-wrap">
<table class="draft-board-table">
<thead><tr>
<th>Round</th>
<th><span>1</span><strong>Julius</strong></th>
<th><span>2</span><strong>Ethan</strong></th>
<th><span>3</span><strong>Chabo</strong></th>
<th><span>4</span><strong>Levi</strong></th>
<th><span>5</span><strong>Dylan</strong></th>
<th><span>6</span><strong>House</strong></th>
<th><span>7</span><strong>Drake</strong></th>
<th><span>8</span><strong>Luke</strong></th>
<th><span>9</span><strong>Justin</strong></th>
<th><span>10</span><strong>Donny</strong></th>
</tr></thead>
<tbody>
<tr>
<td class="draft-round-cell">3rd</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">3.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">3.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">3.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">3.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">3.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">3.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">3.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Luke"><span class="draft-pick-slot">3.08</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Justin"><span class="draft-pick-slot">3.09</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">3.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">4th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">4.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">4.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">4.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Levi"><span class="draft-pick-slot">4.04</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">4.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">4.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">4.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">4.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">4.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Donny"><span class="draft-pick-slot">4.10</span><span class="draft-pick-holder">Drake</span></td>
</tr>
<tr>
<td class="draft-round-cell">5th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">5.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">5.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">5.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">5.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">5.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="House"><span class="draft-pick-slot">5.06</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">5.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">5.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">5.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">5.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">6th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">6.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">6.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">6.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">6.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">6.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">6.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">6.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">6.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Justin"><span class="draft-pick-slot">6.09</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Donny"><span class="draft-pick-slot">6.10</span><span class="draft-pick-holder">Ethan</span></td>
</tr>
<tr>
<td class="draft-round-cell">7th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">7.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">7.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">7.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">7.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">7.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">7.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">7.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Luke"><span class="draft-pick-slot">7.08</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Justin"><span class="draft-pick-slot">7.09</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">7.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">8th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">8.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">8.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">8.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">8.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">8.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">8.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">8.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">8.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Justin"><span class="draft-pick-slot">8.09</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Donny"><span class="draft-pick-slot">8.10</span><span class="draft-pick-holder">Drake</span></td>
</tr>
<tr>
<td class="draft-round-cell">9th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">9.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">9.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">9.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">9.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">9.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">9.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">9.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">9.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">9.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Donny"><span class="draft-pick-slot">9.10</span><span class="draft-pick-holder">Julius</span></td>
</tr>
<tr>
<td class="draft-round-cell">10th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">10.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Ethan"><span class="draft-pick-slot">10.02</span><span class="draft-pick-holder">Donny</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">10.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="Levi"><span class="draft-pick-slot">10.04</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">10.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">10.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">10.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">10.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">10.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Donny"><span class="draft-pick-slot">10.10</span><span class="draft-pick-holder">Dylan</span></td>
</tr>
<tr>
<td class="draft-round-cell">11th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">11.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">11.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">11.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">11.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">11.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">11.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">11.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">11.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">11.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">11.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">12th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">12.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">12.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">12.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">12.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">12.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">12.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">12.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Luke"><span class="draft-pick-slot">12.08</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">12.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-traded is-unused" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" title="Dylan owns this as pick 16 overall, which is beyond the 15-pick cap and will not be used." data-holder="Dylan" data-original-owner="Donny"><span class="draft-pick-slot">12.10</span><span class="draft-pick-holder">Dylan</span><span class="draft-pick-unused">Unused: pick 16 overall</span></td>
</tr>
<tr>
<td class="draft-round-cell">13th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">13.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">13.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">13.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" title="Levi owns this as pick 16 overall, which is beyond the 15-pick cap and will not be used." data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">13.04</span><span class="draft-pick-holder">Levi</span><span class="draft-pick-unused">Unused: pick 16 overall</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" title="Dylan owns this as pick 17 overall, which is beyond the 15-pick cap and will not be used." data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">13.05</span><span class="draft-pick-holder">Dylan</span><span class="draft-pick-unused">Unused: pick 17 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">13.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">13.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">13.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">13.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">13.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">14th</td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" title="Julius owns this as pick 16 overall, which is beyond the 15-pick cap and will not be used." data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">14.01</span><span class="draft-pick-holder">Julius</span><span class="draft-pick-unused">Unused: pick 16 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">14.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">14.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" title="Levi owns this as pick 17 overall, which is beyond the 15-pick cap and will not be used." data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">14.04</span><span class="draft-pick-holder">Levi</span><span class="draft-pick-unused">Unused: pick 17 overall</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" title="Dylan owns this as pick 18 overall, which is beyond the 15-pick cap and will not be used." data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">14.05</span><span class="draft-pick-holder">Dylan</span><span class="draft-pick-unused">Unused: pick 18 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">14.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" title="Drake owns this as pick 16 overall, which is beyond the 15-pick cap and will not be used." data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">14.07</span><span class="draft-pick-holder">Drake</span><span class="draft-pick-unused">Unused: pick 16 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">14.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">14.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">14.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">15th</td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" title="Julius owns this as pick 17 overall, which is beyond the 15-pick cap and will not be used." data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">15.01</span><span class="draft-pick-holder">Julius</span><span class="draft-pick-unused">Unused: pick 17 overall</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" title="Ethan owns this as pick 16 overall, which is beyond the 15-pick cap and will not be used." data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">15.02</span><span class="draft-pick-holder">Ethan</span><span class="draft-pick-unused">Unused: pick 16 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">15.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" title="Levi owns this as pick 18 overall, which is beyond the 15-pick cap and will not be used." data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">15.04</span><span class="draft-pick-holder">Levi</span><span class="draft-pick-unused">Unused: pick 18 overall</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" title="Dylan owns this as pick 19 overall, which is beyond the 15-pick cap and will not be used." data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">15.05</span><span class="draft-pick-holder">Dylan</span><span class="draft-pick-unused">Unused: pick 19 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">15.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" title="Drake owns this as pick 17 overall, which is beyond the 15-pick cap and will not be used." data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">15.07</span><span class="draft-pick-holder">Drake</span><span class="draft-pick-unused">Unused: pick 17 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">15.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">15.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">15.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
</tbody>
</table>
</div>
</details>

<details>
<summary><h2>2027 Draft Board</h2></summary>

A draft-board view ordered by reverse 25/26 standings. Each box shows the current owner of that pick.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- Columns are the original pick slots, ordered worst-to-first from the 25/26 league standings.
- The number at the top of each column is the draft slot in that round.
- Every box is colored by the manager who currently owns that pick.
- Grey boxes are surplus picks: each manager can use at most 15 total picks, so after two keeper slots only their first 13 picks shown here are usable. Any 14th+ shown pick is pick 16+ overall and will not be used unless the pick situation changes.
- Rounds `1st` and `2nd` are omitted because those are keeper slots.

</details>

<div class="draft-board-wrap">
<table class="draft-board-table">
<thead><tr>
<th>Round</th>
<th><span>1</span><strong>Julius</strong></th>
<th><span>2</span><strong>Ethan</strong></th>
<th><span>3</span><strong>Chabo</strong></th>
<th><span>4</span><strong>Levi</strong></th>
<th><span>5</span><strong>Dylan</strong></th>
<th><span>6</span><strong>House</strong></th>
<th><span>7</span><strong>Drake</strong></th>
<th><span>8</span><strong>Luke</strong></th>
<th><span>9</span><strong>Justin</strong></th>
<th><span>10</span><strong>Donny</strong></th>
</tr></thead>
<tbody>
<tr>
<td class="draft-round-cell">3rd</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">3.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">3.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">3.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">3.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">3.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">3.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">3.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">3.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">3.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">3.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">4th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">4.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">4.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">4.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">4.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">4.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">4.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">4.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">4.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">4.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">4.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">5th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">5.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">5.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">5.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">5.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">5.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">5.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">5.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">5.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Justin"><span class="draft-pick-slot">5.09</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">5.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">6th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">6.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">6.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">6.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">6.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">6.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">6.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">6.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">6.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Justin"><span class="draft-pick-slot">6.09</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">6.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">7th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">7.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">7.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">7.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">7.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">7.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">7.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">7.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">7.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">7.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">7.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">8th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">8.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">8.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">8.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">8.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">8.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">8.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">8.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">8.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">8.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">8.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">9th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">9.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">9.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">9.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">9.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">9.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">9.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">9.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">9.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">9.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">9.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">10th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">10.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">10.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">10.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">10.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">10.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">10.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">10.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">10.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">10.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">10.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">11th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">11.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">11.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">11.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">11.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">11.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">11.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">11.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">11.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">11.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">11.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">12th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">12.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">12.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">12.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">12.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">12.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">12.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">12.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">12.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">12.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">12.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">13th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">13.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">13.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">13.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">13.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">13.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">13.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">13.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">13.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">13.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">13.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">14th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">14.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">14.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">14.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" title="Levi owns this as pick 16 overall, which is beyond the 15-pick cap and will not be used." data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">14.04</span><span class="draft-pick-holder">Levi</span><span class="draft-pick-unused">Unused: pick 16 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">14.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">14.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">14.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">14.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">14.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">14.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
<tr>
<td class="draft-round-cell">15th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">15.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">15.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">15.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own is-unused" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" title="Levi owns this as pick 17 overall, which is beyond the 15-pick cap and will not be used." data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">15.04</span><span class="draft-pick-holder">Levi</span><span class="draft-pick-unused">Unused: pick 17 overall</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">15.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="House" data-original-owner="House"><span class="draft-pick-slot">15.06</span><span class="draft-pick-holder">House</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">15.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">15.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">15.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">15.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
</tbody>
</table>
</div>
</details>
