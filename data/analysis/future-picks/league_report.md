# BMS FPL Future Pick Tracker

A draft-pick ownership page built from the workbook's `Drafting Order` tab, with a reconciliation pass against the trade ledger.

## Best Quick Hits

- **2026 traded picks on the tracker**: 16.
- **2027 traded picks on the tracker**: 2.
- **Most 2026 picks**: Levi with 17 picks.
- **Most 2027 picks**: Levi with 15 picks.
- **Reconciliation flags**: 5 pick-owner mismatches between the Excel tracker and the parsed trade ledger.
- **Workbook count-table flags**: 9 count mismatches between the 2026 count table and the 2026 ownership board.

<details open>
<summary><h2>Manager Pick Lookup</h2></summary>

Choose a year and manager to see exactly which future picks they hold and which of their own picks they no longer control.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- The lookup counts rounds `3rd` through `15th`; the `1st` and `2nd` rounds are keeper slots.
- **Picks They Have** includes both their own picks and picks acquired from other managers.
- **Own Picks They Do Not Have** shows original picks that are currently owed away.
- **Incoming Picks From Other Managers** is the acquired-pick subset of the picks they hold.

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
<option value="House/Haydo">House/Haydo</option>
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
<div><h3>Donny - 2026</h3><p>9 picks, -4 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>9</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-4</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>1</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>5</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Donny</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Ethan</td><td>From Ethan</td></tr>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Drake</td></tr>
<tr><td>6th</td><td>Ethan</td></tr>
<tr><td>8th</td><td>Drake</td></tr>
<tr><td>9th</td><td>Julius</td></tr>
<tr><td>10th</td><td>Dylan</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>10th</td><td>Ethan</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Justin" hidden>
<div class="pick-profile-heading">
<div><h3>Justin - 2026</h3><p>8 picks, -5 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>8</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-5</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>5</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Justin</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Justin</td><td>Own pick</td></tr>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Dylan</td></tr>
<tr><td>6th</td><td>Julius</td></tr>
<tr><td>7th</td><td>Levi</td></tr>
<tr><td>8th</td><td>Levi</td></tr>
<tr><td>10th</td><td>House/Haydo</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="House/Haydo" hidden>
<div class="pick-profile-heading">
<div><h3>House/Haydo - 2026</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>1</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>1</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>4th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>6th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>7th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>8th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>9th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>10th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>11th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>12th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>13th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>14th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>15th</td><td>House/Haydo</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>5th</td><td>Dylan</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>10th</td><td>Justin</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Levi" hidden>
<div class="pick-profile-heading">
<div><h3>Levi - 2026</h3><p>17 picks, +4 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>17</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+4</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>5</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>1</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<tr><td>10th</td><td>Levi</td><td>Own pick</td></tr>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Ethan</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Luke</td></tr>
<tr><td>7th</td><td>Justin</td></tr>
<tr><td>7th</td><td>Luke</td></tr>
<tr><td>8th</td><td>Justin</td></tr>
<tr><td>12th</td><td>Luke</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Levi</td></tr>
<tr><td>7th</td><td>Levi</td></tr>
<tr><td>12th</td><td>Levi</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>6th</td><td>Justin</td></tr>
<tr><td>9th</td><td>Donny</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Donny</td></tr>
<tr><td>8th</td><td>Donny</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>10th</td><td>Donny</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Levi</td></tr>
<tr><td>6th</td><td>Donny</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Dylan" hidden>
<div class="pick-profile-heading">
<div><h3>Dylan - 2026</h3><p>16 picks, +3 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>16</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+3</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>3</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>3rd</td><td>Justin</td><td>From Justin</td></tr>
<tr><td>4th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>5th</td><td>House/Haydo</td><td>From House/Haydo</td></tr>
<tr><td>6th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Dylan</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Donny</td><td>From Donny</td></tr>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Justin</td></tr>
<tr><td>5th</td><td>House/Haydo</td></tr>
<tr><td>10th</td><td>Donny</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>5th</td><td>Levi</td></tr>
<tr><td>6th</td><td>Levi</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="House/Haydo" hidden>
<div class="pick-profile-heading">
<div><h3>House/Haydo - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>13</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+0</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>0</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>4th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>5th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>6th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>7th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>8th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>9th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>10th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>11th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>12th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>13th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>14th</td><td>House/Haydo</td><td>Own pick</td></tr>
<tr><td>15th</td><td>House/Haydo</td><td>Own pick</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Own Picks They Do Not Have</div>
<table>
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td>5th</td><td>Justin</td></tr>
<tr><td>6th</td><td>Justin</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
<div class="pick-panel"><div class="pick-panel-title">Incoming Picks From Other Managers</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th></tr></thead>
<tbody>
<tr><td colspan="2">None</td></tr>
</tbody>
</table>
</div>
</div>
</section>
</div>
</div>
</details>

<details>
<summary><h2>2026 Pick Board</h2></summary>

Workbook-style board for 2026: each column is the original owner of the pick, and the cell shows whether that pick is still own or owed to another manager.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- `Own` means the original owner still controls that pick.
- `-> Manager` means that original pick is currently owed to the named manager.
- `Keeper` appears for rounds 1 and 2 because those slots are not part of the traded-pick count.

</details>

| Round | Donny | Justin | House/Haydo | Levi | Luke | Julius | Drake | Chabo | Ethan | Dylan |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1st | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 2nd | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 3rd | Own | ->Dylan | Own | Own | ->Levi | Own | Own | Own | Own | Own |
| 4th | ->Drake | Own | Own | ->Ethan | Own | Own | Own | Own | Own | Own |
| 5th | Own | Own | ->Dylan | Own | Own | Own | Own | Own | Own | Own |
| 6th | ->Ethan | ->Julius | Own | Own | Own | Own | Own | Own | Own | Own |
| 7th | Own | ->Levi | Own | Own | ->Levi | Own | Own | Own | Own | Own |
| 8th | ->Drake | ->Levi | Own | Own | Own | Own | Own | Own | Own | Own |
| 9th | ->Julius | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 10th | ->Dylan | ->House/Haydo | Own | Own | Own | Own | Own | Own | ->Donny | Own |
| 11th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 12th | Own | Own | Own | Own | ->Levi | Own | Own | Own | Own | Own |
| 13th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 14th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 15th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |

</details>

<details>
<summary><h2>2027 Pick Board</h2></summary>

Workbook-style board for 2027: each column is the original owner of the pick, and the cell shows whether that pick is still own or owed to another manager.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- `Own` means the original owner still controls that pick.
- `-> Manager` means that original pick is currently owed to the named manager.
- `Keeper` appears for rounds 1 and 2 because those slots are not part of the traded-pick count.

</details>

| Round | Donny | Justin | House/Haydo | Levi | Luke | Julius | Drake | Chabo | Ethan | Dylan |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1st | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 2nd | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 3rd | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 4th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 5th | Own | ->Levi | Own | Own | Own | Own | Own | Own | Own | Own |
| 6th | Own | ->Levi | Own | Own | Own | Own | Own | Own | Own | Own |
| 7th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 8th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 9th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 10th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 11th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 12th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 13th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 14th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 15th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |

</details>

<details>
<summary><h2>Traded Pick Detail</h2></summary>

A compact list of every future pick currently marked as owed to someone other than its original owner.

| Year | Round | Original Owner | Current Holder | Workbook Cell |
|---|---:|---:|---:|---:|
| 2026 | 3rd | Justin | Dylan | OWED TO DYLAN |
| 2026 | 3rd | Luke | Levi | OWED TO LEVI |
| 2026 | 4th | Donny | Drake | OWED TO DRAKE |
| 2026 | 4th | Levi | Ethan | OWED TO ETHAN |
| 2026 | 5th | House/Haydo | Dylan | OWED TO DYLAN |
| 2026 | 6th | Donny | Ethan | OWED TO ETHAN |
| 2026 | 6th | Justin | Julius | OWED TO JULIUS |
| 2026 | 7th | Justin | Levi | OWED TO LEVI |
| 2026 | 7th | Luke | Levi | OWED TO LEVI |
| 2026 | 8th | Donny | Drake | OWED TO DRAKE |
| 2026 | 8th | Justin | Levi | OWED TO LEVI |
| 2026 | 9th | Donny | Julius | OWED TO JULIUS |
| 2026 | 10th | Donny | Dylan | OWED TO DYLAN |
| 2026 | 10th | Ethan | Donny | OWED TO DONNY |
| 2026 | 10th | Justin | House/Haydo | OWED TO HOUSE/HAYDO |
| 2026 | 12th | Luke | Levi | OWED TO LEVI |
| 2027 | 5th | Justin | Levi | OWED TO LEVI |
| 2027 | 6th | Justin | Levi | OWED TO LEVI |

</details>

<details>
<summary><h2>Trade Ledger Reconciliation</h2></summary>

This checks the workbook tracker against future-pick movements parsed from the trade ledger and calls out anything that does not line up.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- For 2024-25 trade rows, only explicitly labeled `2026` or `2027` picks are treated as future picks; unlabeled picks are assumed to belong to the already-completed 2025 draft.
- For 2025-26 rows after Draft Day, unlabeled pick assets are treated as 2026 future picks unless the asset explicitly says 2027.
- In pass-through cases where a manager held more than one pick in the same round, the parser tries to use the non-own pick first and records that assumption below.
- Multi-team trade rows do not state exactly which counterparty receives each asset, so those recipient assumptions are listed separately.

</details>

| Issue | Year | Round | Original Owner | Tracker Holder | Ledger Holder | Ledger Evidence | Notes |
|---|---:|---:|---:|---:|---:|---:|---:|
| Tracker-only move | 2026 | 3rd | Justin | Dylan | Justin | No future-pick movement found in parsed trade ledger | - |
| Ledger-only move | 2026 | 3rd | Levi | Levi | Dylan | Postseason: Levi -> Dylan | - |
| Tracker-only move | 2026 | 10th | Justin | House/Haydo | Justin | No future-pick movement found in parsed trade ledger | - |
| Ledger-only move | 2026 | 10th | Levi | Levi | House/Haydo | Postseason: Levi -> House/Haydo | - |
| Ledger-only move | 2026 | 12th | Donny | Donny | Dylan | Draft Day: Donny -> Dylan | - |

</details>

<details>
<summary><h2>Reconciliation Assumptions</h2></summary>

These are not necessarily errors; they are the trade-ledger rows where the parser had to infer pass-through ownership or a recipient.

| Year | Round | Original Owner | Sender | Recipient | Timing | Assumption | Asset |
|---|---:|---:|---:|---:|---:|---:|---:|
| 2026 | 5th | House/Haydo | House/Haydo | Levi | Postseason | multi-team trade; recipient inferred as Levi | 2026 5th-round pick |
| 2026 | 5th | House/Haydo | Levi | Dylan | Postseason | original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks | 2026 5th-round pick |

</details>

<details>
<summary><h2>Workbook Count Check</h2></summary>

This verifies the workbook's 2026 count table against the ownership board above.

| Year | Round | Manager | Workbook Count | Calculated Count | Workbook Row |
|---|---:|---:|---:|---:|---:|
| 2026 | 3 | Levi | 1 | 2 | 23 |
| 2026 | 3 | Luke | 1 | 0 | 23 |
| 2026 | 4 | Ethan | 1 | 2 | 24 |
| 2026 | 7 | Luke | 1 | 0 | 27 |
| 2026 | 10 | Dylan | 1 | 2 | 30 |
| 2026 | 12 | Ethan | 2 | 1 | 32 |
| 2026 | Total | Levi | 15 | 17 | 36 |
| 2026 | Total | Luke | 13 | 10 | 36 |
| 2026 | Total | Dylan | 15 | 16 | 36 |

</details>

<details>
<summary><h2>Output Files</h2></summary>

- `future_pick_portfolio.csv`
- `future_pick_matrix.csv`
- `future_pick_traded_detail.csv`
- `future_pick_reconciliation.csv`
- `future_pick_count_audit.csv`
- `future_pick_movements.csv`
</details>
