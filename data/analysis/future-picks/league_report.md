# BMS FPL Future Pick Tracker

A draft-pick ownership page built from the workbook's `Drafting Order` tab, with ledger-backed corrections applied where the tracker is known to be less accurate.

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
<option value="Ryan Houseman">Ryan Houseman</option>
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
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>4th</td><td>Drake</td></tr>
<tr><td>6th</td><td>Ethan</td></tr>
<tr><td>8th</td><td>Drake</td></tr>
<tr><td>9th</td><td>Julius</td></tr>
<tr><td>10th</td><td>Dylan</td></tr>
<tr><td>12th</td><td>Dylan</td></tr>
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
<div><h3>Justin - 2026</h3><p>9 picks, -4 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>9</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>-4</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>0</strong></div>
<div class="pick-stat"><span>Own Picks Missing</span><strong>4</strong></div>
</div>
<div class="pick-profile-grid">
<div class="pick-panel"><div class="pick-panel-title">Picks They Have</div>
<table>
<thead><tr><th>Round</th><th>Original Owner</th><th>Type</th></tr></thead>
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
<thead><tr><th>Round</th><th>Current Holder</th></tr></thead>
<tbody>
<tr><td>3rd</td><td>Dylan</td></tr>
<tr><td>6th</td><td>Julius</td></tr>
<tr><td>7th</td><td>Levi</td></tr>
<tr><td>8th</td><td>Levi</td></tr>
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
<section class="pick-profile" data-pick-profile data-year="2026" data-manager="Ryan Houseman" hidden>
<div class="pick-profile-heading">
<div><h3>Ryan Houseman - 2026</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
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
<tr><td>3rd</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Levi</td><td>From Levi</td></tr>
<tr><td>10th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
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
<tr><td>10th</td><td>Levi</td></tr>
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
<tr><td>10th</td><td>Ryan Houseman</td></tr>
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
<div><h3>Dylan - 2026</h3><p>17 picks, +4 versus a standard 13-pick draft.</p></div>
</div>
<div class="pick-profile-stats">
<div class="pick-stat"><span>Total Picks</span><strong>17</strong></div>
<div class="pick-stat"><span>Net vs 13</span><strong>+4</strong></div>
<div class="pick-stat"><span>Incoming Picks</span><strong>4</strong></div>
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
<tr><td>5th</td><td>Ryan Houseman</td><td>From Ryan Houseman</td></tr>
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
<tr><td>5th</td><td>Ryan Houseman</td></tr>
<tr><td>10th</td><td>Donny</td></tr>
<tr><td>12th</td><td>Donny</td></tr>
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
<section class="pick-profile" data-pick-profile data-year="2027" data-manager="Ryan Houseman" hidden>
<div class="pick-profile-heading">
<div><h3>Ryan Houseman - 2027</h3><p>13 picks, +0 versus a standard 13-pick draft.</p></div>
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
<tr><td>3rd</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>4th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>5th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>6th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>7th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>8th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>9th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>10th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>11th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>12th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>13th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>14th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
<tr><td>15th</td><td>Ryan Houseman</td><td>Own pick</td></tr>
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
<summary><h2>2026 Draft Board</h2></summary>

A draft-board view ordered by reverse 25/26 standings. Each box shows the current owner of that pick.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- Columns are the original pick slots, ordered worst-to-first from the 25/26 league standings.
- The number at the top of each column is the draft slot in that round.
- Every box is colored by the manager who currently owns that pick.
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
<th><span>6</span><strong>Ryan Houseman</strong></th>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">3.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">4.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-traded" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">5.06</span><span class="draft-pick-holder">Dylan</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">6.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">7.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">8.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">9.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-traded" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Levi"><span class="draft-pick-slot">10.04</span><span class="draft-pick-holder">Ryan Houseman</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">10.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">10.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">11.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">12.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">12.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Luke"><span class="draft-pick-slot">12.08</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">12.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-traded" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Donny"><span class="draft-pick-slot">12.10</span><span class="draft-pick-holder">Dylan</span></td>
</tr>
<tr>
<td class="draft-round-cell">13th</td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fee2e2; --pick-ink: #7f1d1d; --pick-border: #f87171" data-holder="Julius" data-original-owner="Julius"><span class="draft-pick-slot">13.01</span><span class="draft-pick-holder">Julius</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ccfbf1; --pick-ink: #134e4a; --pick-border: #2dd4bf" data-holder="Ethan" data-original-owner="Ethan"><span class="draft-pick-slot">13.02</span><span class="draft-pick-holder">Ethan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fce7f3; --pick-ink: #831843; --pick-border: #f472b6" data-holder="Chabo" data-original-owner="Chabo"><span class="draft-pick-slot">13.03</span><span class="draft-pick-holder">Chabo</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">13.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">13.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">13.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">14.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">14.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">14.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
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
<td class="pick-owner-cell is-own" style="--pick-bg: #ede9fe; --pick-ink: #4c1d95; --pick-border: #a78bfa" data-holder="Levi" data-original-owner="Levi"><span class="draft-pick-slot">15.04</span><span class="draft-pick-holder">Levi</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #ffedd5; --pick-ink: #7c2d12; --pick-border: #fb923c" data-holder="Dylan" data-original-owner="Dylan"><span class="draft-pick-slot">15.05</span><span class="draft-pick-holder">Dylan</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #fef3c7; --pick-ink: #78350f; --pick-border: #f59e0b" data-holder="Ryan Houseman" data-original-owner="Ryan Houseman"><span class="draft-pick-slot">15.06</span><span class="draft-pick-holder">Ryan Houseman</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #e0e7ff; --pick-ink: #312e81; --pick-border: #818cf8" data-holder="Drake" data-original-owner="Drake"><span class="draft-pick-slot">15.07</span><span class="draft-pick-holder">Drake</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #cffafe; --pick-ink: #164e63; --pick-border: #22d3ee" data-holder="Luke" data-original-owner="Luke"><span class="draft-pick-slot">15.08</span><span class="draft-pick-holder">Luke</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dcfce7; --pick-ink: #14532d; --pick-border: #4ade80" data-holder="Justin" data-original-owner="Justin"><span class="draft-pick-slot">15.09</span><span class="draft-pick-holder">Justin</span></td>
<td class="pick-owner-cell is-own" style="--pick-bg: #dbeafe; --pick-ink: #1e3a8a; --pick-border: #60a5fa" data-holder="Donny" data-original-owner="Donny"><span class="draft-pick-slot">15.10</span><span class="draft-pick-holder">Donny</span></td>
</tr>
</tbody>
</table>
</div>
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

| Round | Donny | Justin | Ryan Houseman | Levi | Luke | Julius | Drake | Chabo | Ethan | Dylan |
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

A compact list of every future pick currently marked as owed to someone other than its original owner after ledger corrections.

| Year | Round | Original Owner | Current Holder | Displayed Status |
|---|---:|---:|---:|---:|
| 2026 | 3rd | Justin | Dylan | Owed to Dylan |
| 2026 | 3rd | Luke | Levi | Owed to Levi |
| 2026 | 4th | Donny | Drake | Owed to Drake |
| 2026 | 4th | Levi | Ethan | Owed to Ethan |
| 2026 | 5th | Ryan Houseman | Dylan | Owed to Dylan |
| 2026 | 6th | Donny | Ethan | Owed to Ethan |
| 2026 | 6th | Justin | Julius | Owed to Julius |
| 2026 | 7th | Justin | Levi | Owed to Levi |
| 2026 | 7th | Luke | Levi | Owed to Levi |
| 2026 | 8th | Donny | Drake | Owed to Drake |
| 2026 | 8th | Justin | Levi | Owed to Levi |
| 2026 | 9th | Donny | Julius | Owed to Julius |
| 2026 | 10th | Donny | Dylan | Owed to Dylan |
| 2026 | 10th | Ethan | Donny | Owed to Donny |
| 2026 | 10th | Levi | Ryan Houseman | Owed to Ryan Houseman |
| 2026 | 12th | Donny | Dylan | Owed to Dylan |
| 2026 | 12th | Luke | Levi | Owed to Levi |
| 2027 | 5th | Justin | Levi | Owed to Levi |
| 2027 | 6th | Justin | Levi | Owed to Levi |

</details>

<details>
<summary><h2>Ledger Corrections Applied</h2></summary>

These rows show where the page overrides the workbook tracker because the trade ledger or a manual ruling is more accurate.

| Year | Round | Original Owner | Tracker Holder | Displayed Holder | Reason |
|---|---:|---:|---:|---:|---:|
| 2026 | 10th | Justin | Ryan Houseman | Justin | Ledger decision: Levi sent his own 2026 10th-round pick to Ryan Houseman, so Justin keeps his own 10th. |
| 2026 | 10th | Levi | Levi | Ryan Houseman | Ledger decision: Levi sent his own 2026 10th-round pick to Ryan Houseman. |
| 2026 | 12th | Donny | Donny | Dylan | Ledger decision: source row 37 says Donny sent his 2026 12th-round pick to Dylan. |

</details>

<details>
<summary><h2>Trade Ledger Reconciliation</h2></summary>

This checks the workbook tracker against future-pick movements parsed from the trade ledger and calls out anything that does not line up.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- A pick without a full draft year is assigned to the next draft after that trade season: 2024-25 trade rows default to the 2025 draft, and 2025-26 trade rows default to the 2026 draft.
- Draft Day is the exception: unlabeled Draft Day picks are treated as current-draft picks that can be used immediately, so they are not stored as future picks.
- If a pick asset clearly names a full draft year, like `2026 3rd-round pick` or `2027 6th-round pick`, that explicit draft year overrides the season default.
- In pass-through cases where a manager held more than one pick in the same round, the parser tries to use the non-own pick first and records that assumption below.
- Multi-team trade rows do not state exactly which counterparty receives each asset, so those recipient assumptions are listed separately.

</details>

No pick-owner mismatches found.

</details>

<details>
<summary><h2>Reconciliation Assumptions</h2></summary>

These are not necessarily errors; they are the trade-ledger rows where the parser had to infer pass-through ownership or a recipient.

| Year | Round | Original Owner | Sender | Recipient | Timing | Assumption | Asset |
|---|---:|---:|---:|---:|---:|---:|---:|
| 2026 | 5th | Ryan Houseman | Ryan Houseman | Levi | Postseason | multi-team trade; recipient inferred as Levi | 2026 5th-round pick |
| 2026 | 3rd | Justin | Justin | Levi | Before 2024-25 postseason row 32 | Manual clarification: Justin had already traded this pick to Levi before Levi sent it to Dylan; the trade ledger does not clearly mark that pass-through. | 2026 3rd-round pick |
| 2026 | 3rd | Justin | Levi | Dylan | Postseason | original owner inferred from a pass-through pick currently held by sender; sender held 2 3rd-round picks | 2026 3rd-round pick |
| 2026 | 5th | Ryan Houseman | Levi | Dylan | Postseason | original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks | 2026 5th-round pick |

</details>

<details>
<summary><h2>Workbook Count Check</h2></summary>

This verifies the workbook's 2026 count table against the ledger-adjusted ownership board above.

| Year | Round | Manager | Workbook Count | Calculated Count | Workbook Row |
|---|---:|---:|---:|---:|---:|
| 2026 | 3 | Levi | 1 | 2 | 23 |
| 2026 | 3 | Luke | 1 | 0 | 23 |
| 2026 | 4 | Ethan | 1 | 2 | 24 |
| 2026 | 7 | Luke | 1 | 0 | 27 |
| 2026 | 10 | Justin | 0 | 1 | 30 |
| 2026 | 10 | Levi | 1 | 0 | 30 |
| 2026 | 10 | Dylan | 1 | 2 | 30 |
| 2026 | 12 | Donny | 1 | 0 | 32 |
| 2026 | 12 | Ethan | 2 | 1 | 32 |
| 2026 | 12 | Dylan | 1 | 2 | 32 |
| 2026 | Total | Donny | 9 | 8 | 36 |
| 2026 | Total | Justin | 8 | 9 | 36 |
| 2026 | Total | Levi | 15 | 16 | 36 |
| 2026 | Total | Luke | 13 | 10 | 36 |
| 2026 | Total | Dylan | 15 | 17 | 36 |

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
