# BMS FPL Trade Ledger

A searchable ledger of player, pick, and conditional trades from the league workbook.

<section class="trades-page" data-trades-page>
<div class="trade-stat-grid">
<div class="trade-stat"><span>Total trades</span><strong>48</strong></div>
<div class="trade-stat"><span>Most active trader</span><strong>Levi</strong><em>33 trades</em></div>
<div class="trade-stat"><span>Pick/condition trades</span><strong>40</strong></div>
<div class="trade-stat"><span>Biggest trade</span><strong>13 assets</strong><em>Levi &lt;-&gt; Chabo</em></div>
</div>
<div class="trade-controls">
<div class="trade-season-tabs" aria-label="Trade seasons">
<button type="button" class="trade-tab-button is-active" data-trade-season-button="2025-26" aria-pressed="true">2025-26 <span>14</span></button>
<button type="button" class="trade-tab-button" data-trade-season-button="2024-25" aria-pressed="false">2024-25 <span>34</span></button>
</div>
<label class="trade-filter-label" for="trade-manager">Manager</label>
<select id="trade-manager" class="trade-manager-select" data-trade-manager>
<option value="all">All managers</option>
<option value="chabo">Chabo</option>
<option value="donny">Donny</option>
<option value="drake">Drake</option>
<option value="dylan">Dylan</option>
<option value="ethan">Ethan</option>
<option value="julius">Julius</option>
<option value="justin">Justin</option>
<option value="levi">Levi</option>
<option value="luke">Luke</option>
<option value="ryan houseman">Ryan Houseman</option>
</select>
<label class="trade-filter-label" for="trade-search">Search trades</label>
<input id="trade-search" class="trade-search-input" type="search" placeholder="Search player, manager, pick, condition..." autocomplete="off" data-trade-search>
<div class="trade-count" data-trade-count></div>
</div>
<div class="trade-list" data-trade-list>
<article class="trade-card" data-season="2025-26" data-managers="donny|dylan" data-search="2025-26 draft day draft day donny, dylan donny sent 2026 10th-round pick (via donny), 2026 12th-round pick (via donny); dylan sent 9th-round pick (1st)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | Draft Day | Draft Day</span>
<span class="trade-title">Donny &lt;-&gt; Dylan</span>
<span class="trade-description">Donny sent 2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny); Dylan sent 9th-round pick (1st)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>2026 10th-round pick (via Donny), 2026 12th-round pick (via Donny)</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>9th-round pick (1st)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="donny|ethan" data-search="2025-26 preseason preseason donny, ethan donny sent mamardashvili (liv); ethan sent 10th-round pick (via ethan), vicario (tot)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | Preseason | Preseason</span>
<span class="trade-title">Donny &lt;-&gt; Ethan</span>
<span class="trade-description">Donny sent Mamardashvili (LIV); Ethan sent 10th-round pick (via Ethan), Vicario (TOT)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Mamardashvili (LIV)</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>10th-round pick (via Ethan), Vicario (TOT)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|julius" data-search="2025-26 preseason preseason levi, julius levi sent sesko (mu), gyokeres (ars), wirtz (liv); julius sent salah (liv), isak (new)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | Preseason | Preseason</span>
<span class="trade-title">Levi &lt;-&gt; Julius</span>
<span class="trade-description">Levi sent Sesko (MU), Gyokeres (ARS), Wirtz (LIV); Julius sent Salah (LIV), Isak (NEW)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">5 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Sesko (MU), Gyokeres (ARS), Wirtz (LIV)</p></div>
<div class="trade-side"><strong>Julius sent</strong><p>Salah (LIV), Isak (NEW)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|justin" data-search="2025-26 preseason preseason levi, justin levi sent isak (new), flemming (bur); justin sent watkins (avl), wissa (bre)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | Preseason | Preseason</span>
<span class="trade-title">Levi &lt;-&gt; Justin</span>
<span class="trade-description">Levi sent Isak (NEW), Flemming (BUR); Justin sent Watkins (AVL), Wissa (BRE)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Isak (NEW), Flemming (BUR)</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>Watkins (AVL), Wissa (BRE)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|luke" data-search="2025-26 gw 10 in-season levi, luke levi sent simons (tot); luke sent cullen (bur), 12th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 10 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Luke</span>
<span class="trade-description">Levi sent Simons (TOT); Luke sent Cullen (BUR), 12th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Simons (TOT)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>Cullen (BUR), 12th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="donny|ethan" data-search="2025-26 gw 22 in-season donny, ethan donny sent kushannov (mci), 6th-round pick; ethan sent timber (ars)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 22 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Ethan</span>
<span class="trade-description">Donny sent Kushannov (MCI), 6th-round pick; Ethan sent Timber (ARS)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Kushannov (MCI), 6th-round pick</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Timber (ARS)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|ethan" data-search="2025-26 gw 24 in-season levi, ethan levi sent damsgaard (bre), 4th-round pick; ethan sent mbuemo (mu)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 24 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Ethan</span>
<span class="trade-description">Levi sent Damsgaard (BRE), 4th-round pick; Ethan sent Mbuemo (MU)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Damsgaard (BRE), 4th-round pick</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Mbuemo (MU)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|justin" data-search="2025-26 gw 26 in-season levi, justin levi sent wissa (new); justin sent pablo (whu), 2026 7th-round pick, 2027 6th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 26 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Justin</span>
<span class="trade-description">Levi sent Wissa (NEW); Justin sent Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Wissa (NEW)</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>Pablo (WHU), 2026 7th-round pick, 2027 6th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|justin" data-search="2025-26 gw 31 in-season levi, justin levi sent havertz (ars), watkins (avl); justin sent 2027 5th-round pick, matching players to be dropped">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 31 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Justin</span>
<span class="trade-description">Levi sent Havertz (ARS), Watkins (AVL); Justin sent 2027 5th-round pick, matching players to be dropped</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Havertz (ARS), Watkins (AVL)</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>2027 5th-round pick, matching players to be dropped</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|luke" data-search="2025-26 gw 31 in-season levi, luke levi sent konate (liv), salah (liv), summerville (whu), armstrong (wol); luke sent 2026 7th-round pick, matching players to be dropped">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 31 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Luke</span>
<span class="trade-description">Levi sent Konate (LIV), Salah (LIV), Summerville (WHU), Armstrong (WOL); Luke sent 2026 7th-round pick, matching players to be dropped</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">6 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Konate (LIV), Salah (LIV), Summerville (WHU), Armstrong (WOL)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>2026 7th-round pick, matching players to be dropped</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|luke" data-search="2025-26 gw 31 in-season levi, luke levi sent mbuemo (mu); luke sent 2026 3rd-round pick, matching players to be dropped">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 31 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Luke</span>
<span class="trade-description">Levi sent Mbuemo (MU); Luke sent 2026 3rd-round pick, matching players to be dropped</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Mbuemo (MU)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>2026 3rd-round pick, matching players to be dropped</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="levi|justin" data-search="2025-26 gw 31 in-season levi, justin levi sent o&#x27;reilly (mc); justin sent 2026 8th-round pick, matching players to be dropped">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 31 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Justin</span>
<span class="trade-description">Levi sent O&#x27;Reilly (MC); Justin sent 2026 8th-round pick, matching players to be dropped</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>O&#x27;Reilly (MC)</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>2026 8th-round pick, matching players to be dropped</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="julius|justin" data-search="2025-26 gw 31 in-season julius, justin julius sent garner (eve); justin sent 2026 6th-round pick, joão gomes (wol)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 31 | In-season</span>
<span class="trade-title">Julius &lt;-&gt; Justin</span>
<span class="trade-description">Julius sent Garner (EVE); Justin sent 2026 6th-round pick, João Gomes (WOL)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Julius sent</strong><p>Garner (EVE)</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>2026 6th-round pick, João Gomes (WOL)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2025-26" data-managers="julius|donny" data-search="2025-26 gw 32 in-season julius, donny julius sent calvert-lewin (lee); donny sent 2026 9th-round pick, muniz (ful)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2025-26 | GW 32 | In-season</span>
<span class="trade-title">Julius &lt;-&gt; Donny</span>
<span class="trade-description">Julius sent Calvert-Lewin (LEE); Donny sent 2026 9th-round pick, Muniz (FUL)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Julius sent</strong><p>Calvert-Lewin (LEE)</p></div>
<div class="trade-side"><strong>Donny sent</strong><p>2026 9th-round pick, Muniz (FUL)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|julius" data-search="2024-25 gw 1 in-season levi, julius levi sent onana (mun), estupinan (bha), wissa (bre); julius sent raya (ars), gabriel (ars), welbeck (bha)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 1 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Julius</span>
<span class="trade-description">Levi sent Onana (MUN), Estupinan (BHA), Wissa (BRE); Julius sent Raya (ARS), Gabriel (ARS), Welbeck (BHA)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">6 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Onana (MUN), Estupinan (BHA), Wissa (BRE)</p></div>
<div class="trade-side"><strong>Julius sent</strong><p>Raya (ARS), Gabriel (ARS), Welbeck (BHA)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|chabo" data-search="2024-25 gw 1 in-season levi, chabo levi sent pope (new), romero (tot), quansah (liv), van de ven (tot), semenyo (bou), welbeck (bha); chabo sent ortega moreno (mci), white (ars), munoz (cry), cancelo (mci), sterling (che), j. alvarez (mci), 2024 4th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 1 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Chabo</span>
<span class="trade-description">Levi sent Pope (NEW), Romero (TOT), Quansah (LIV), Van de Ven (TOT), Semenyo (BOU), Welbeck (BHA); Chabo sent Ortega Moreno (MCI), White (ARS), Munoz (CRY), Cancelo (MCI), Sterling (CHE), J. Alvarez (MCI), 2024 4th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">13 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Pope (NEW), Romero (TOT), Quansah (LIV), Van de Ven (TOT), Semenyo (BOU), Welbeck (BHA)</p></div>
<div class="trade-side"><strong>Chabo sent</strong><p>Ortega Moreno (MCI), White (ARS), Munoz (CRY), Cancelo (MCI), Sterling (CHE), J. Alvarez (MCI), 2024 4th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ethan" data-search="2024-25 gw 3 in-season levi, ethan levi sent kudus (whu); ethan sent rashford (mun), 2024 4th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 3 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Ethan</span>
<span class="trade-description">Levi sent Kudus (WHU); Ethan sent Rashford (MUN), 2024 4th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Kudus (WHU)</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Rashford (MUN), 2024 4th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|justin" data-search="2024-25 gw 4 in-season levi, justin levi sent nketiah (cp), barnes (new), bowen (whu), lewis (mc); justin sent havertz (ars), gundogan (mc), andreas (ful), zabarnyi (bou), 2024 5th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 4 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Justin</span>
<span class="trade-description">Levi sent Nketiah (CP), Barnes (NEW), Bowen (WHU), Lewis (MC); Justin sent Havertz (ARS), Gundogan (MC), Andreas (FUL), Zabarnyi (BOU), 2024 5th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">9 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Nketiah (CP), Barnes (NEW), Bowen (WHU), Lewis (MC)</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>Havertz (ARS), Gundogan (MC), Andreas (FUL), Zabarnyi (BOU), 2024 5th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|luke" data-search="2024-25 gw 4 in-season levi, luke levi sent armstrong (sou), ramsdale (sou), gundogan (mc); luke sent toney (n/a), dubravka (new), onana (avl)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 4 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Luke</span>
<span class="trade-description">Levi sent Armstrong (SOU), Ramsdale (SOU), Gundogan (MC); Luke sent Toney (N/A), Dubravka (NEW), Onana (AVL)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">6 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Armstrong (SOU), Ramsdale (SOU), Gundogan (MC)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>Toney (N/A), Dubravka (NEW), Onana (AVL)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ryan houseman" data-search="2024-25 gw 4 in-season levi, ryan houseman levi sent tavernier (bou), livramento (new); ryan houseman sent trossard (ars), veltman (bha)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 4 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Ryan Houseman</span>
<span class="trade-description">Levi sent Tavernier (BOU), Livramento (NEW); Ryan Houseman sent Trossard (ARS), Veltman (BHA)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Tavernier (BOU), Livramento (NEW)</p></div>
<div class="trade-side"><strong>Ryan Houseman sent</strong><p>Trossard (ARS), Veltman (BHA)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|drake" data-search="2024-25 gw 5 in-season levi, drake levi sent johnstone (wol), munoz (cp), andeas (ful), onana (avl); drake sent sa (wol), trippier (new), rice (ars), mainoo (mu), 2024 4th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 5 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Drake</span>
<span class="trade-description">Levi sent Johnstone (WOL), Munoz (CP), Andeas (FUL), Onana (AVL); Drake sent Sa (WOL), Trippier (NEW), Rice (ARS), Mainoo (MU), 2024 4th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">9 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Johnstone (WOL), Munoz (CP), Andeas (FUL), Onana (AVL)</p></div>
<div class="trade-side"><strong>Drake sent</strong><p>Sa (WOL), Trippier (NEW), Rice (ARS), Mainoo (MU), 2024 4th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|chabo" data-search="2024-25 gw 10 in-season donny, chabo donny sent flekken (bre), udogie (tot); chabo sent pope (new), maatsen (avl)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 10 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Chabo</span>
<span class="trade-description">Donny sent Flekken (BRE), Udogie (TOT); Chabo sent Pope (NEW), Maatsen (AVL)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Flekken (BRE), Udogie (TOT)</p></div>
<div class="trade-side"><strong>Chabo sent</strong><p>Pope (NEW), Maatsen (AVL)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|luke" data-search="2024-25 gw 13 in-season levi, luke levi sent raya (ars), gabriel (ars), hudson-odoi (not), mcneil (eve), damsgaard (bre), havertz (ars), 3rd-5th-round picks for 2025 (3rd conditional, converys to 6th if no trophies won for levi); luke sent sels (not), bassey (ful), janelt (bre), savio (mc), palmer (che), archer (sou)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 13 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Luke</span>
<span class="trade-description">Levi sent Raya (ARS), Gabriel (ARS), Hudson-Odoi (NOT), McNeil (EVE), Damsgaard (BRE), Havertz (ARS), 3rd-5th-round picks for 2025 (3rd conditional, converys to 6th if no trophies won for Levi); Luke sent Sels (NOT), Bassey (FUL), Janelt (BRE), Savio (MC), Palmer (CHE), Archer (SOU)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">13 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Raya (ARS), Gabriel (ARS), Hudson-Odoi (NOT), McNeil (EVE), Damsgaard (BRE), Havertz (ARS), 3rd-5th-round picks for 2025 (3rd conditional, converys to 6th if no trophies won for Levi)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>Sels (NOT), Bassey (FUL), Janelt (BRE), Savio (MC), Palmer (CHE), Archer (SOU)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|julius" data-search="2024-25 gw 14 in-season levi, julius levi sent hojlund (mu), paqueta (whu), davis (ips); julius sent antonio (whu), newcastle (new), estupinan (bha) - 2025 5th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 14 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Julius</span>
<span class="trade-description">Levi sent Hojlund (MU), Paqueta (WHU), Davis (IPS); Julius sent Antonio (WHU), Newcastle (NEW), Estupinan (BHA) - 2025 5th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">6 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Hojlund (MU), Paqueta (WHU), Davis (IPS)</p></div>
<div class="trade-side"><strong>Julius sent</strong><p>Antonio (WHU), Newcastle (NEW), Estupinan (BHA) - 2025 5th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|dylan" data-search="2024-25 gw 14 in-season levi, dylan levi sent enzo (che), fullkrug (whu); dylan sent doku (mc), muniz (ful), 2025 5th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 14 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Dylan</span>
<span class="trade-description">Levi sent Enzo (CHE), Fullkrug (WHU); Dylan sent Doku (MC), Muniz (FUL), 2025 5th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">5 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Enzo (CHE), Fullkrug (WHU)</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>Doku (MC), Muniz (FUL), 2025 5th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|dylan" data-search="2024-25 gw 16 in-season donny, dylan donny sent smith rowe (ful), pope (new), 4th-round pick; dylan sent son (tot), kelleher (liv)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 16 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Dylan</span>
<span class="trade-description">Donny sent Smith Rowe (FUL), Pope (NEW), 4th-round pick; Dylan sent Son (TOT), Kelleher (LIV)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">5 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Smith Rowe (FUL), Pope (NEW), 4th-round pick</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>Son (TOT), Kelleher (LIV)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|luke" data-search="2024-25 gw 16 in-season donny, luke donny sent hermansen (lei), mitoma (bha); luke sent becker (liv), mcneil (eve)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 16 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Luke</span>
<span class="trade-description">Donny sent Hermansen (LEI), Mitoma (BHA); Luke sent Becker (LIV), McNeil (EVE)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Hermansen (LEI), Mitoma (BHA)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>Becker (LIV), McNeil (EVE)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ethan" data-search="2024-25 gw 18 in-season levi, ethan levi sent ortega moreno (mc), hall (new), sarr (cp), 8th-round pick; ethan sent vicario (tot), de ligt (mu), jones (liv), 3rd-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 18 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Ethan</span>
<span class="trade-description">Levi sent Ortega Moreno (MC), Hall (NEW), Sarr (CP), 8th-round pick; Ethan sent Vicario (TOT), de Ligt (MU), Jones (LIV), 3rd-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">8 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Ortega Moreno (MC), Hall (NEW), Sarr (CP), 8th-round pick</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Vicario (TOT), de Ligt (MU), Jones (LIV), 3rd-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|justin" data-search="2024-25 gw 18 in-season levi, justin levi sent sels (not), livramento (new), colwill (che), kluivert (bou), 7th-round pick, remove restrictions on previously traded nketiah pick; justin sent fabianksi (whu), tsimikas (liv), castangne (ful), barnes (new), 4th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 18 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Justin</span>
<span class="trade-description">Levi sent Sels (NOT), Livramento (NEW), Colwill (CHE), Kluivert (BOU), 7th-round pick, remove restrictions on previously traded Nketiah pick; Justin sent Fabianksi (WHU), Tsimikas (LIV), Castangne (FUL), Barnes (NEW), 4th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">11 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Sels (NOT), Livramento (NEW), Colwill (CHE), Kluivert (BOU), 7th-round pick, remove restrictions on previously traded Nketiah pick</p></div>
<div class="trade-side"><strong>Justin sent</strong><p>Fabianksi (WHU), Tsimikas (LIV), Castangne (FUL), Barnes (NEW), 4th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|chabo" data-search="2024-25 gw 23 in-season donny, chabo donny sent ake (mci), 5th-round pick; chabo sent aina (nfo)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 23 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Chabo</span>
<span class="trade-description">Donny sent Ake (MCI), 5th-round pick; Chabo sent Aina (NFO)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Ake (MCI), 5th-round pick</p></div>
<div class="trade-side"><strong>Chabo sent</strong><p>Aina (NFO)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ryan houseman" data-search="2024-25 gw 24 in-season levi, ryan houseman levi sent williams (not), dango (bou), ndiaye (eve), 9th-round pick; ryan houseman sent young (eve), wilson (ful), archer (sou), 3rd-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 24 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Ryan Houseman</span>
<span class="trade-description">Levi sent Williams (NOT), Dango (BOU), Ndiaye (EVE), 9th-round pick; Ryan Houseman sent Young (EVE), Wilson (FUL), Archer (SOU), 3rd-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">8 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Williams (NOT), Dango (BOU), Ndiaye (EVE), 9th-round pick</p></div>
<div class="trade-side"><strong>Ryan Houseman sent</strong><p>Young (EVE), Wilson (FUL), Archer (SOU), 3rd-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="justin|julius" data-search="2024-25 gw 24 in-season justin, julius justin sent maddison (tot), 3rd-round pick; julius sent salah (liv) julius gets keeper swap option at end of season (he picks one of justin&#x27;s keepers and justin picks one of his). optional, but up to julius to exercise option.">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 24 | In-season</span>
<span class="trade-title">Justin &lt;-&gt; Julius</span>
<span class="trade-description">Justin sent Maddison (TOT), 3rd-round pick; Julius sent Salah (LIV)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Justin sent</strong><p>Maddison (TOT), 3rd-round pick</p></div>
<div class="trade-side"><strong>Julius sent</strong><p>Salah (LIV)</p></div>
</div>
<p class="trade-note"><strong>Note:</strong> Julius gets keeper swap option at end of season (he picks one of Justin&#x27;s keepers and Justin picks one of his). Optional, but up to Julius to exercise option.</p>
</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|levi" data-search="2024-25 gw 27 in-season donny, levi donny sent mbuemo (bre), son (tot), taa (liv), 7th-round pick; levi sent white (ars), merino (ars), rice (ars), 3rd-round pick, 4th-round pick, 4th-round pick, 5th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 27 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Levi</span>
<span class="trade-description">Donny sent Mbuemo (BRE), Son (TOT), TAA (LIV), 7th-round pick; Levi sent White (ARS), Merino (ARS), Rice (ARS), 3rd-round pick, 4th-round pick, 4th-round pick, 5th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">11 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Mbuemo (BRE), Son (TOT), TAA (LIV), 7th-round pick</p></div>
<div class="trade-side"><strong>Levi sent</strong><p>White (ARS), Merino (ARS), Rice (ARS), 3rd-round pick, 4th-round pick, 4th-round pick, 5th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|drake" data-search="2024-25 gw 27 in-season levi, drake levi sent rashford (avl), de ligt (mu), 4th-round pick; drake sent diaz (liv), konsa (avl)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 27 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Drake</span>
<span class="trade-description">Levi sent Rashford (AVL), de Ligt (MU), 4th-round pick; Drake sent Diaz (LIV), Konsa (AVL)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">5 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Rashford (AVL), de Ligt (MU), 4th-round pick</p></div>
<div class="trade-side"><strong>Drake sent</strong><p>Diaz (LIV), Konsa (AVL)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|dylan" data-search="2024-25 gw 28 in-season donny, dylan donny sent merino (ars), white (ars), 6th-round pick, 9th-round pick; dylan sent neto (che), porro (tot)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 28 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Dylan</span>
<span class="trade-description">Donny sent Merino (ARS), White (ARS), 6th-round pick, 9th-round pick; Dylan sent Neto (CHE), Porro (TOT)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">6 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Merino (ARS), White (ARS), 6th-round pick, 9th-round pick</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>Neto (CHE), Porro (TOT)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ethan" data-search="2024-25 gw 28 in-season levi, ethan levi sent armstrong (sou), 7th-round pick; ethan sent pedro (bha)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 28 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Ethan</span>
<span class="trade-description">Levi sent Armstrong (SOU), 7th-round pick; Ethan sent Pedro (BHA)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Armstrong (SOU), 7th-round pick</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Pedro (BHA)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|chabo" data-search="2024-25 gw 30 in-season levi, chabo levi sent son (tot); chabo sent minteh (bha), 6th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 30 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Chabo</span>
<span class="trade-description">Levi sent Son (TOT); Chabo sent Minteh (BHA), 6th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Son (TOT)</p></div>
<div class="trade-side"><strong>Chabo sent</strong><p>Minteh (BHA), 6th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|dylan" data-search="2024-25 gw 30 in-season levi, dylan levi sent minteh (bha), 6th-round pick; dylan sent merino (ars)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 30 | In-season</span>
<span class="trade-title">Levi &lt;-&gt; Dylan</span>
<span class="trade-description">Levi sent Minteh (BHA), 6th-round pick; Dylan sent Merino (ARS)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Minteh (BHA), 6th-round pick</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>Merino (ARS)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="donny|ethan" data-search="2024-25 gw 30 in-season donny, ethan donny sent daka (lei), 4th-round pick (5th if doesn&#x27;t donny win league); ethan sent evanilson (bou)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | GW 30 | In-season</span>
<span class="trade-title">Donny &lt;-&gt; Ethan</span>
<span class="trade-description">Donny sent Daka (LEI), 4th-round pick (5th if doesn&#x27;t Donny win league); Ethan sent Evanilson (BOU)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Donny sent</strong><p>Daka (LEI), 4th-round pick (5th if doesn&#x27;t Donny win league)</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Evanilson (BOU)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|luke" data-search="2024-25 postseason postseason levi, luke levi sent diaz (liv), amad (mu), conditional 5th-round picks (3) if diaz leaves the prem before draft; luke sent marmoush (mc), 8th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Levi &lt;-&gt; Luke</span>
<span class="trade-description">Levi sent Diaz (LIV), Amad (MU), Conditional 5th-round picks (3) if Diaz leaves the Prem before draft; Luke sent Marmoush (MC), 8th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">5 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Diaz (LIV), Amad (MU), Conditional 5th-round picks (3) if Diaz leaves the Prem before draft</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>Marmoush (MC), 8th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ethan" data-search="2024-25 postseason postseason levi, ethan levi sent mbeumo (bre), marmoush (mc); ethan sent isak (new)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Levi &lt;-&gt; Ethan</span>
<span class="trade-description">Levi sent Mbeumo (BRE), Marmoush (MC); Ethan sent Isak (NEW)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>Mbeumo (BRE), Marmoush (MC)</p></div>
<div class="trade-side"><strong>Ethan sent</strong><p>Isak (NEW)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|julius" data-search="2024-25 postseason postseason levi, julius levi sent 3rd-round pick (5th), 3rd-round pick (9th); julius sent isak (new)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Levi &lt;-&gt; Julius</span>
<span class="trade-description">Levi sent 3rd-round pick (5th), 3rd-round pick (9th); Julius sent Isak (NEW)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>3rd-round pick (5th), 3rd-round pick (9th)</p></div>
<div class="trade-side"><strong>Julius sent</strong><p>Isak (NEW)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="justin|dylan" data-search="2024-25 postseason postseason justin, dylan justin sent bowen (whu); dylan sent 6th-round pick (1st)">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Justin &lt;-&gt; Dylan</span>
<span class="trade-description">Justin sent Bowen (WHU); Dylan sent 6th-round pick (1st)</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">2 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Justin sent</strong><p>Bowen (WHU)</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>6th-round pick (1st)</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|luke|ryan houseman" data-search="2024-25 postseason postseason levi, luke, ryan houseman levi sent 5th-round pick (1st), 10th-round pick (7th), 11th-round pick (7th); luke sent 7th-round pick (5th); ryan houseman sent wood (nf), 2026 5th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Levi &lt;-&gt; Luke &lt;-&gt; Ryan Houseman</span>
<span class="trade-description">Levi sent 5th-round pick (1st), 10th-round pick (7th), 11th-round pick (7th); Luke sent 7th-round pick (5th); Ryan Houseman sent Wood (NF), 2026 5th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">3 teams</span><span class="trade-badge">6 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>5th-round pick (1st), 10th-round pick (7th), 11th-round pick (7th)</p></div>
<div class="trade-side"><strong>Luke sent</strong><p>7th-round pick (5th)</p></div>
<div class="trade-side"><strong>Ryan Houseman sent</strong><p>Wood (NF), 2026 5th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|dylan" data-search="2024-25 postseason postseason levi, dylan levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; dylan sent 3rd-round pick (1st), 11th-round pick, 12th-round pick, 13th-round pick, 14th-round pick, 15th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Levi &lt;-&gt; Dylan</span>
<span class="trade-description">Levi sent 3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick; Dylan sent 3rd-round pick (1st), 11th-round pick, 12th-round pick, 13th-round pick, 14th-round pick, 15th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">12 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>3rd-round pick (5th), 3rd-round pick (9th), 5th-round pick (5th), 5th-round pick (9th), 2026 3rd-round pick, 2026 5th-round pick</p></div>
<div class="trade-side"><strong>Dylan sent</strong><p>3rd-round pick (1st), 11th-round pick, 12th-round pick, 13th-round pick, 14th-round pick, 15th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="drake|donny" data-search="2024-25 postseason postseason drake, donny drake sent 4th-round pick (2nd); donny sent 2026 4th-round pick, 2026 8th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Drake &lt;-&gt; Donny</span>
<span class="trade-description">Drake sent 4th-round pick (2nd); Donny sent 2026 4th-round pick, 2026 8th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">3 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Drake sent</strong><p>4th-round pick (2nd)</p></div>
<div class="trade-side"><strong>Donny sent</strong><p>2026 4th-round pick, 2026 8th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="justin|chabo" data-search="2024-25 postseason postseason justin, chabo justin sent rogers (avl); chabo sent 8th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Justin &lt;-&gt; Chabo</span>
<span class="trade-description">Justin sent Rogers (AVL); Chabo sent 8th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">2 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Justin sent</strong><p>Rogers (AVL)</p></div>
<div class="trade-side"><strong>Chabo sent</strong><p>8th-round pick</p></div>
</div>

</div>
</details>
</article>
<article class="trade-card" data-season="2024-25" data-managers="levi|ryan houseman" data-search="2024-25 postseason postseason levi, ryan houseman levi sent 2026 10th-round pick; ryan houseman sent 2025 12th-round pick, 13th-round pick, 14th-round pick">
<details>
<summary>
<span class="trade-summary-main">
<span class="trade-kicker">2024-25 | Postseason | Postseason</span>
<span class="trade-title">Levi &lt;-&gt; Ryan Houseman</span>
<span class="trade-description">Levi sent 2026 10th-round pick; Ryan Houseman sent 2025 12th-round pick, 13th-round pick, 14th-round pick</span>
</span>
<span class="trade-summary-meta"><span class="trade-badge">2 teams</span><span class="trade-badge">4 assets</span><span class="trade-badge trade-badge-pick">Picks/conditions</span></span>
</summary>
<div class="trade-body">
<div class="trade-side-list">
<div class="trade-side"><strong>Levi sent</strong><p>2026 10th-round pick</p></div>
<div class="trade-side"><strong>Ryan Houseman sent</strong><p>2025 12th-round pick, 13th-round pick, 14th-round pick</p></div>
</div>

</div>
</details>
</article>
</div>
</section>

<details>
<summary><h2>Trade Activity Summary</h2></summary>

| Season | Trades | Managers | In-Season | Postseason | Preseason/Draft | Multi-Team | Pick/Condition Trades |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2025-26 | 14 | 7 | 10 | 0 | 4 | 0 | 12 |
| 2024-25 | 34 | 10 | 25 | 9 | 0 | 1 | 28 |

</details>

<details>
<summary><h2>Manager Trade Summary</h2></summary>

| Manager | Trades | Assets Sent | Pick/Condition Trades | Most Common Partner |
| --- | --- | --- | --- | --- |
| Levi | 33 | 98 | 27 | Luke (7) |
| Donny | 12 | 28 | 10 | Dylan (3) |
| Justin | 10 | 25 | 9 | Levi (6) |
| Ethan | 8 | 13 | 7 | Levi (5) |
| Luke | 8 | 20 | 6 | Levi (7) |
| Dylan | 7 | 16 | 7 | Donny (3) |
| Julius | 7 | 12 | 5 | Levi (4) |
| Chabo | 5 | 13 | 4 | Levi (2) |
| Ryan Houseman | 4 | 11 | 3 | Levi (4) |
| Drake | 3 | 8 | 3 | Levi (2) |

</details>

<details>
<summary><h2>Most Common Trade Partners</h2></summary>

| Manager 1 | Manager 2 | Trades |
| --- | --- | --- |
| Levi | Luke | 7 |
| Justin | Levi | 6 |
| Ethan | Levi | 5 |
| Julius | Levi | 4 |
| Levi | Ryan Houseman | 4 |
| Donny | Dylan | 3 |
| Donny | Ethan | 3 |
| Dylan | Levi | 3 |
| Chabo | Donny | 2 |
| Chabo | Levi | 2 |
| Drake | Levi | 2 |
| Julius | Justin | 2 |
| Chabo | Justin | 1 |
| Donny | Drake | 1 |
| Donny | Julius | 1 |
| Donny | Levi | 1 |
| Donny | Luke | 1 |
| Dylan | Justin | 1 |
| Luke | Ryan Houseman | 1 |

</details>

<details>
<summary><h2>Source Notes</h2></summary>

- Trade ledger source: `BPL Fantasy.xlsx` / `Trade History`.
- `Assets Sent` are read from the workbook as the assets each listed manager gave up.
- Draft-pick wording is standardized for display as `7th-round pick`, regardless of whether the workbook says `7th`, `7th Rd.`, `7th rounder`, or `7th Round Pick`.
- Pick and condition trades are flagged when the assets or notes mention picks, rounds, rounders, or conditions.
- The postseason rows before the 2025/26 divider remain grouped under `2024-25`, because that is how the workbook separates them.

</details>