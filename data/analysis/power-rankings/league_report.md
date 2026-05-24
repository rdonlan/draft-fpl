# BMS FPL Draft Power Rankings

Tracks a simple Elo-style rating within each season. Every manager starts at 1500 at the beginning of each year, and ratings move after each gameweek based on H2H results and opponent strength.

## Best Quick Hits

- **Latest Season Power #1**: Ryan Donlan (1634.3 in 2025-26).
- **Highest Single-Season Peak**: Ryan Donlan reached 1645.6 after 2024-25 33.
- **Most Weeks At #1 In A Season**: Ryan Donlan (26 weeks in 2024-25).

<details open>
<summary><h2>Season Elo Tabs</h2></summary>

Use the tabs to switch between seasons. Each season has its own Elo chart, final power table, weekly path, time-at-top table, and biggest rating swings.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- Every manager starts at `1500` before week 1 of each season.
- This uses a standard Elo update with `K = 24`.
- Expected result is `1 / (1 + 10 ^ ((Opponent Rating - Manager Rating) / 400))`.
- Actual result is `1` for a win, `0.5` for a draw, and `0` for a loss.
- Updates are calculated simultaneously within each gameweek using ratings from before that gameweek.
- This first version intentionally uses only H2H result and opponent strength, with no score or margin bonus.

</details>

<div class="power-tabs">
<input class="power-tab-input" type="radio" name="power-season-tabs" id="power-season-2025-26" checked>
<input class="power-tab-input" type="radio" name="power-season-tabs" id="power-season-2024-25">
<div class="power-tab-list" role="tablist" aria-label="Power rankings seasons">
<label class="power-tab-label" id="power-season-2025-26-label" role="tab" for="power-season-2025-26">2025-26</label>
<label class="power-tab-label" id="power-season-2024-25-label" role="tab" for="power-season-2024-25">2024-25</label>
</div>
<section class="power-tab-panel" id="power-panel-2025-26" role="tabpanel" aria-labelledby="power-season-2025-26-label">
### 2025-26 Elo Movement
<div class="rating-chart-wrap" role="img" aria-label="2025-26 Elo rating movement chart">
<svg class="rating-chart" viewBox="0 0 1060 520" xmlns="http://www.w3.org/2000/svg">
<text class="chart-title" x="64" y="18">2025-26 Elo Movement</text>
<line class="axis-line" x1="64" y1="398" x2="884" y2="398" />
<line class="axis-line" x1="64" y1="28" x2="64" y2="398" />
<line class="grid-line" x1="64" y1="398.0" x2="884" y2="398.0" />
<text class="axis-label" x="54" y="402.0" text-anchor="end">1375</text>
<line class="grid-line" x1="64" y1="367.2" x2="884" y2="367.2" />
<text class="axis-label" x="54" y="371.2" text-anchor="end">1400</text>
<line class="grid-line" x1="64" y1="336.3" x2="884" y2="336.3" />
<text class="axis-label" x="54" y="340.3" text-anchor="end">1425</text>
<line class="grid-line" x1="64" y1="305.5" x2="884" y2="305.5" />
<text class="axis-label" x="54" y="309.5" text-anchor="end">1450</text>
<line class="grid-line" x1="64" y1="274.7" x2="884" y2="274.7" />
<text class="axis-label" x="54" y="278.7" text-anchor="end">1475</text>
<line class="grid-line" x1="64" y1="243.8" x2="884" y2="243.8" />
<text class="axis-label" x="54" y="247.8" text-anchor="end">1500</text>
<line class="grid-line" x1="64" y1="213.0" x2="884" y2="213.0" />
<text class="axis-label" x="54" y="217.0" text-anchor="end">1525</text>
<line class="grid-line" x1="64" y1="182.2" x2="884" y2="182.2" />
<text class="axis-label" x="54" y="186.2" text-anchor="end">1550</text>
<line class="grid-line" x1="64" y1="151.3" x2="884" y2="151.3" />
<text class="axis-label" x="54" y="155.3" text-anchor="end">1575</text>
<line class="grid-line" x1="64" y1="120.5" x2="884" y2="120.5" />
<text class="axis-label" x="54" y="124.5" text-anchor="end">1600</text>
<line class="grid-line" x1="64" y1="89.7" x2="884" y2="89.7" />
<text class="axis-label" x="54" y="93.7" text-anchor="end">1625</text>
<line class="grid-line" x1="64" y1="58.8" x2="884" y2="58.8" />
<text class="axis-label" x="54" y="62.8" text-anchor="end">1650</text>
<line class="grid-line" x1="64" y1="28.0" x2="884" y2="28.0" />
<text class="axis-label" x="54" y="32.0" text-anchor="end">1675</text>
<line class="tick-line" x1="64.0" y1="398" x2="64.0" y2="404" />
<text class="axis-label" x="64.0" y="422" text-anchor="middle">Start</text>
<line class="tick-line" x1="174.8" y1="398" x2="174.8" y2="404" />
<text class="axis-label" x="174.8" y="422" text-anchor="middle">5</text>
<line class="tick-line" x1="285.6" y1="398" x2="285.6" y2="404" />
<text class="axis-label" x="285.6" y="422" text-anchor="middle">10</text>
<line class="tick-line" x1="396.4" y1="398" x2="396.4" y2="404" />
<text class="axis-label" x="396.4" y="422" text-anchor="middle">15</text>
<line class="tick-line" x1="507.2" y1="398" x2="507.2" y2="404" />
<text class="axis-label" x="507.2" y="422" text-anchor="middle">20</text>
<line class="tick-line" x1="618.1" y1="398" x2="618.1" y2="404" />
<text class="axis-label" x="618.1" y="422" text-anchor="middle">25</text>
<line class="tick-line" x1="728.9" y1="398" x2="728.9" y2="404" />
<text class="axis-label" x="728.9" y="422" text-anchor="middle">30</text>
<line class="tick-line" x1="839.7" y1="398" x2="839.7" y2="404" />
<text class="axis-label" x="839.7" y="422" text-anchor="middle">35</text>
<line class="tick-line" x1="884.0" y1="398" x2="884.0" y2="404" />
<text class="axis-label" x="884.0" y="422" text-anchor="middle">37</text>
<text class="axis-caption" x="474.0" y="446" text-anchor="middle">Week</text>
<text class="axis-caption" transform="translate(18 213.0) rotate(-90)" text-anchor="middle">Elo rating</text>
<polyline class="rating-line" points="64.0,243.8 86.2,258.6 108.3,272.4 130.5,286.3 152.6,270.5 174.8,253.9 197.0,237.2 219.1,253.2 241.3,239.5 263.5,255.2 285.6,239.7 307.8,226.2 329.9,239.4 352.1,225.6 374.3,241.6 396.4,255.0 418.6,240.2 440.8,225.2 462.9,212.0 485.1,197.6 507.2,186.1 529.4,171.0 551.6,159.4 573.7,177.0 595.9,164.9 618.1,183.1 640.2,168.9 662.4,187.2 684.5,173.4 706.7,163.8 728.9,150.5 751.0,141.0 773.2,131.1 795.4,119.9 817.5,109.5 839.7,95.9 861.8,87.8 884.0,78.2" stroke="hsl(44 76% 38%)"><title>Ryan Donlan</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="78.2" r="3.5" fill="hsl(44 76% 38%)"><title>Ryan Donlan</title></circle>
<line class="legend-swatch" x1="910" y1="44" x2="932" y2="44" stroke="hsl(44 76% 38%)" />
<text class="legend-label" x="940" y="48">Ryan Donlan</text>
<polyline class="rating-line" points="64.0,243.8 86.2,258.6 108.3,242.8 130.5,256.7 152.6,241.9 174.8,255.7 197.0,270.7 219.1,285.4 241.3,299.1 263.5,281.4 285.6,266.0 307.8,278.3 329.9,263.9 352.1,247.4 374.3,261.0 396.4,247.4 418.6,233.6 440.8,248.6 462.9,232.5 485.1,219.2 507.2,202.4 529.4,220.6 551.6,207.1 573.7,193.5 595.9,182.0 618.1,201.0 640.2,215.2 662.4,230.6 684.5,215.8 706.7,200.2 728.9,190.1 751.0,176.0 773.2,162.8 795.4,153.6 817.5,143.1 839.7,156.7 861.8,144.5 884.0,136.4" stroke="hsl(352 76% 38%)"><title>Justin Miller</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="136.4" r="3.5" fill="hsl(352 76% 38%)"><title>Justin Miller</title></circle>
<line class="legend-swatch" x1="910" y1="72" x2="932" y2="72" stroke="hsl(352 76% 38%)" />
<text class="legend-label" x="940" y="76">Justin Miller</text>
<polyline class="rating-line" points="64.0,243.8 86.2,229.0 108.3,244.9 130.5,231.0 152.6,216.2 174.8,232.9 197.0,218.2 219.1,204.3 241.3,190.5 263.5,205.2 285.6,192.0 307.8,179.7 329.9,166.5 352.1,184.2 374.3,171.0 396.4,158.7 418.6,148.9 440.8,153.9 462.9,140.4 485.1,160.0 507.2,176.8 529.4,191.9 551.6,208.4 573.7,195.7 595.9,211.6 618.1,229.5 640.2,217.4 662.4,204.3 684.5,191.2 706.7,206.8 728.9,220.2 751.0,204.8 773.2,190.7 795.4,179.6 817.5,170.2 839.7,190.4 861.8,191.4 884.0,210.3" stroke="hsl(266 76% 38%)"><title>Luke Lockwood</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="210.3" r="3.5" fill="hsl(266 76% 38%)"><title>Luke Lockwood</title></circle>
<line class="legend-swatch" x1="910" y1="100" x2="932" y2="100" stroke="hsl(266 76% 38%)" />
<text class="legend-label" x="940" y="104">Luke Lockwood</text>
<polyline class="rating-line" points="64.0,243.8 86.2,258.6 108.3,273.4 130.5,258.6 152.6,273.3 174.8,256.6 197.0,270.4 219.1,254.5 241.3,240.0 263.5,225.5 285.6,208.9 307.8,225.8 329.9,212.8 352.1,229.4 374.3,242.6 396.4,256.7 418.6,271.4 440.8,255.6 462.9,271.7 485.1,254.6 507.2,270.9 529.4,256.4 551.6,270.0 573.7,282.7 595.9,265.5 618.1,247.3 640.2,230.8 662.4,219.0 684.5,235.9 706.7,222.8 728.9,209.9 751.0,224.0 773.2,238.2 795.4,252.0 817.5,262.4 839.7,249.8 861.8,237.3 884.0,221.8" stroke="hsl(12 76% 38%)"><title>Ryan Houseman</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="221.8" r="3.5" fill="hsl(12 76% 38%)"><title>Ryan Houseman</title></circle>
<line class="legend-swatch" x1="910" y1="128" x2="932" y2="128" stroke="hsl(12 76% 38%)" />
<text class="legend-label" x="940" y="132">Ryan Houseman</text>
<polyline class="rating-line" points="64.0,243.8 86.2,229.0 108.3,243.8 130.5,229.0 152.6,213.3 174.8,199.5 197.0,216.1 219.1,201.3 241.3,188.3 263.5,173.6 285.6,190.1 307.8,208.0 329.9,194.8 352.1,213.3 374.3,199.7 396.4,186.3 418.6,172.2 440.8,191.0 462.9,204.5 485.1,221.6 507.2,238.8 529.4,255.0 551.6,241.3 573.7,254.9 595.9,267.1 618.1,251.0 640.2,267.1 662.4,280.2 684.5,263.3 706.7,247.9 728.9,234.8 751.0,223.9 773.2,237.0 795.4,248.2 817.5,231.6 839.7,218.9 861.8,218.0 884.0,233.4" stroke="hsl(154 76% 38%)"><title>Drake Byrd</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="233.4" r="3.5" fill="hsl(154 76% 38%)"><title>Drake Byrd</title></circle>
<line class="legend-swatch" x1="910" y1="156" x2="932" y2="156" stroke="hsl(154 76% 38%)" />
<text class="legend-label" x="940" y="160">Drake Byrd</text>
<polyline class="rating-line" points="64.0,243.8 86.2,258.6 108.3,272.4 130.5,287.2 152.6,269.5 174.8,284.4 197.0,267.9 219.1,253.2 241.3,266.2 263.5,250.5 285.6,263.7 307.8,278.0 329.9,291.0 352.1,274.6 374.3,260.1 396.4,276.3 418.6,290.1 440.8,271.3 462.9,284.5 485.1,264.9 507.2,278.8 529.4,293.4 551.6,306.9 573.7,291.0 595.9,306.6 618.1,287.6 640.2,271.5 662.4,253.3 684.5,266.4 706.7,280.0 728.9,292.8 751.0,277.4 773.2,264.0 795.4,282.5 817.5,293.0 839.7,305.7 861.8,313.7 884.0,294.8" stroke="hsl(118 76% 38%)"><title>Levi Morant</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="294.8" r="3.5" fill="hsl(118 76% 38%)"><title>Levi Morant</title></circle>
<line class="legend-swatch" x1="910" y1="184" x2="932" y2="184" stroke="hsl(118 76% 38%)" />
<text class="legend-label" x="940" y="188">Levi Morant</text>
<polyline class="rating-line" points="64.0,243.8 86.2,258.6 108.3,243.8 130.5,258.6 152.6,274.4 174.8,259.4 197.0,244.5 219.1,258.4 241.3,272.2 263.5,287.2 285.6,271.6 307.8,254.6 329.9,267.8 352.1,281.6 374.3,296.2 396.4,309.8 418.6,319.6 440.8,331.0 462.9,313.8 485.1,297.7 507.2,281.4 529.4,265.1 551.6,276.7 573.7,292.6 595.9,304.0 618.1,286.1 640.2,299.5 662.4,281.8 684.5,283.5 706.7,296.7 728.9,309.8 751.0,319.4 773.2,332.7 795.4,341.9 817.5,351.4 839.7,331.9 861.8,317.4 884.0,332.6" stroke="hsl(224 76% 38%)"><title>Julius Long</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="332.6" r="3.5" fill="hsl(224 76% 38%)"><title>Julius Long</title></circle>
<line class="legend-swatch" x1="910" y1="212" x2="932" y2="212" stroke="hsl(224 76% 38%)" />
<text class="legend-label" x="940" y="216">Julius Long</text>
<polyline class="rating-line" points="64.0,243.8 86.2,229.0 108.3,215.3 130.5,230.0 152.6,244.9 174.8,229.1 197.0,215.2 219.1,230.1 241.3,216.3 263.5,233.9 285.6,249.4 307.8,235.1 329.9,250.8 352.1,233.1 374.3,220.2 396.4,206.2 418.6,220.3 440.8,208.8 462.9,225.0 485.1,239.4 507.2,225.5 529.4,241.9 551.6,225.4 573.7,213.1 595.9,230.3 618.1,246.4 640.2,232.9 662.4,217.5 684.5,231.3 706.7,217.7 728.9,204.4 751.0,219.8 773.2,209.7 795.4,195.9 817.5,212.5 839.7,231.9 861.8,244.1 884.0,253.8" stroke="hsl(292 76% 38%)"><title>Dylan Reid</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="253.8" r="3.5" fill="hsl(292 76% 38%)"><title>Dylan Reid</title></circle>
<line class="legend-swatch" x1="910" y1="240" x2="932" y2="240" stroke="hsl(292 76% 38%)" />
<text class="legend-label" x="940" y="244">Dylan Reid</text>
<polyline class="rating-line" points="64.0,243.8 86.2,229.0 108.3,215.3 130.5,201.4 152.6,217.2 174.8,232.9 197.0,249.5 219.1,234.7 241.3,248.4 263.5,262.9 285.6,278.6 307.8,292.0 329.9,306.3 352.1,287.8 374.3,300.7 396.4,284.5 418.6,298.4 440.8,293.4 462.9,277.3 485.1,293.4 507.2,304.9 529.4,286.6 551.6,300.3 573.7,312.6 595.9,297.0 618.1,308.8 640.2,320.9 662.4,332.7 684.5,330.9 706.7,340.5 728.9,350.6 751.0,361.5 773.2,371.6 795.4,353.2 817.5,336.9 839.7,316.6 861.8,329.2 884.0,313.9" stroke="hsl(78 76% 38%)"><title>Ethan Ellsworth</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="313.9" r="3.5" fill="hsl(78 76% 38%)"><title>Ethan Ellsworth</title></circle>
<line class="legend-swatch" x1="910" y1="268" x2="932" y2="268" stroke="hsl(78 76% 38%)" />
<text class="legend-label" x="940" y="272">Ethan Ellsworth</text>
<polyline class="rating-line" points="64.0,243.8 86.2,229.0 108.3,214.2 130.5,199.5 152.6,217.3 174.8,233.9 197.0,248.7 219.1,263.5 241.3,278.0 263.5,263.0 285.6,278.4 307.8,260.6 329.9,244.9 352.1,261.3 374.3,245.3 396.4,257.5 418.6,243.7 440.8,259.4 462.9,276.7 485.1,289.9 507.2,272.8 529.4,256.4 551.6,242.9 573.7,225.2 595.9,209.4 618.1,197.6 640.2,214.1 662.4,231.8 684.5,246.6 706.7,261.9 728.9,275.2 751.0,290.6 773.2,300.5 795.4,311.5 817.5,327.8 839.7,340.3 861.8,354.8 884.0,362.9" stroke="hsl(28 76% 38%)"><title>Alexander Chaban</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="362.9" r="3.5" fill="hsl(28 76% 38%)"><title>Alexander Chaban</title></circle>
<line class="legend-swatch" x1="910" y1="296" x2="932" y2="296" stroke="hsl(28 76% 38%)" />
<text class="legend-label" x="940" y="300">Alexander Chaban</text>
</svg>
</div>
### 2025-26 Power Rankings
| Rank | Manager | Final Rating | Net | Peak | Peak Week | Low | Low Week | Avg Rank | Weeks #1 | Top 3 Weeks | Bottom 3 Weeks |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | Ryan Donlan | 1634.3 | +134.3 | 1634.3 | 2025-26 37 | 1465.6 | 2025-26 3 | 3.19 | 17 | 21 | 4 |
| 2 | Justin Miller | 1587.1 | +87.1 | 1587.1 | 2025-26 37 | 1455.2 | 2025-26 8 | 4.59 | 0 | 18 | 6 |
| 3 | Luke Lockwood | 1527.2 | +27.2 | 1583.9 | 2025-26 18 | 1499.2 | 2025-26 2 | 2.62 | 10 | 29 | 0 |
| 4 | Ryan Houseman | 1517.8 | +17.8 | 1528.3 | 2025-26 10 | 1468.5 | 2025-26 23 | 5.89 | 0 | 4 | 5 |
| 5 | Drake Byrd | 1508.4 | +8.4 | 1558.1 | 2025-26 16 | 1470.5 | 2025-26 27 | 3.78 | 6 | 17 | 1 |
| 6 | Dylan Reid | 1492.0 | -8.1 | 1538.9 | 2025-26 33 | 1492.0 | 2025-26 37 | 4.03 | 1 | 12 | 0 |
| 7 | Levi Morant | 1458.7 | -41.4 | 1494.6 | 2025-26 9 | 1443.3 | 2025-26 36 | 7.81 | 0 | 0 | 22 |
| 8 | Ethan Ellsworth | 1443.2 | -56.9 | 1534.4 | 2025-26 3 | 1396.4 | 2025-26 32 | 8.19 | 0 | 4 | 28 |
| 9 | Julius Long | 1428.0 | -72.0 | 1500.0 | 2025-26 2 | 1412.8 | 2025-26 34 | 8.62 | 0 | 0 | 33 |
| 10 | Alexander Chaban | 1403.5 | -96.5 | 1537.5 | 2025-26 25 | 1403.5 | 2025-26 37 | 6.27 | 3 | 6 | 12 |

### 2025-26 Weekly Path
| Week | #1 | #2 | #3 | #4 | #5 | Bottom |
|---|---:|---:|---:|---:|---:|---:|
| 1 | Alexander Chaban (1512) | Drake Byrd (1512) | Dylan Reid (1512) | Ethan Ellsworth (1512) | Luke Lockwood (1512) | Ryan Houseman (1488) |
| 2 | Alexander Chaban (1524) | Dylan Reid (1523) | Ethan Ellsworth (1523) | Justin Miller (1501) | Drake Byrd (1500) | Ryan Houseman (1476) |
| 3 | Alexander Chaban (1536) | Ethan Ellsworth (1534) | Drake Byrd (1512) | Dylan Reid (1511) | Luke Lockwood (1510) | Levi Morant (1465) |
| 4 | Drake Byrd (1525) | Luke Lockwood (1522) | Ethan Ellsworth (1522) | Alexander Chaban (1522) | Justin Miller (1502) | Julius Long (1475) |
| 5 | Drake Byrd (1536) | Dylan Reid (1512) | Ethan Ellsworth (1509) | Luke Lockwood (1509) | Alexander Chaban (1508) | Levi Morant (1467) |
| 6 | Dylan Reid (1523) | Drake Byrd (1522) | Luke Lockwood (1521) | Ryan Donlan (1505) | Julius Long (1499) | Justin Miller (1478) |
| 7 | Drake Byrd (1534) | Luke Lockwood (1532) | Dylan Reid (1511) | Ethan Ellsworth (1507) | Levi Morant (1492) | Justin Miller (1466) |
| 8 | Drake Byrd (1545) | Luke Lockwood (1543) | Dylan Reid (1522) | Ryan Donlan (1504) | Ryan Houseman (1503) | Justin Miller (1455) |
| 9 | Drake Byrd (1557) | Luke Lockwood (1531) | Ryan Houseman (1515) | Dylan Reid (1508) | Levi Morant (1495) | Julius Long (1465) |
| 10 | Drake Byrd (1544) | Luke Lockwood (1542) | Ryan Houseman (1528) | Ryan Donlan (1503) | Dylan Reid (1495) | Ethan Ellsworth (1472) |
| 11 | Luke Lockwood (1552) | Drake Byrd (1529) | Ryan Houseman (1515) | Ryan Donlan (1514) | Dylan Reid (1507) | Ethan Ellsworth (1461) |
| 12 | Luke Lockwood (1563) | Drake Byrd (1540) | Ryan Houseman (1525) | Ryan Donlan (1504) | Alexander Chaban (1499) | Ethan Ellsworth (1449) |
| 13 | Luke Lockwood (1548) | Drake Byrd (1525) | Ryan Donlan (1515) | Ryan Houseman (1512) | Dylan Reid (1509) | Ethan Ellsworth (1464) |
| 14 | Luke Lockwood (1559) | Drake Byrd (1536) | Dylan Reid (1519) | Ryan Donlan (1502) | Ryan Houseman (1501) | Ethan Ellsworth (1454) |
| 15 | Luke Lockwood (1569) | Drake Byrd (1547) | Dylan Reid (1531) | Justin Miller (1497) | Ryan Donlan (1491) | Julius Long (1447) |
| 16 | Luke Lockwood (1577) | Drake Byrd (1558) | Dylan Reid (1519) | Justin Miller (1508) | Ryan Donlan (1503) | Julius Long (1439) |
| 17 | Luke Lockwood (1573) | Drake Byrd (1543) | Dylan Reid (1528) | Ryan Donlan (1515) | Justin Miller (1496) | Julius Long (1429) |
| 18 | Luke Lockwood (1584) | Drake Byrd (1532) | Ryan Donlan (1526) | Dylan Reid (1515) | Justin Miller (1509) | Julius Long (1443) |
| 19 | Luke Lockwood (1568) | Ryan Donlan (1537) | Justin Miller (1520) | Drake Byrd (1518) | Dylan Reid (1504) | Julius Long (1456) |
| 20 | Luke Lockwood (1554) | Ryan Donlan (1547) | Justin Miller (1534) | Dylan Reid (1515) | Drake Byrd (1504) | Ethan Ellsworth (1450) |
| 21 | Ryan Donlan (1559) | Luke Lockwood (1542) | Justin Miller (1519) | Dylan Reid (1502) | Drake Byrd (1491) | Levi Morant (1460) |
| 22 | Ryan Donlan (1568) | Justin Miller (1530) | Luke Lockwood (1529) | Dylan Reid (1515) | Drake Byrd (1502) | Levi Morant (1449) |
| 23 | Ryan Donlan (1554) | Justin Miller (1541) | Luke Lockwood (1539) | Dylan Reid (1525) | Alexander Chaban (1515) | Ethan Ellsworth (1444) |
| 24 | Ryan Donlan (1564) | Justin Miller (1550) | Alexander Chaban (1528) | Luke Lockwood (1526) | Dylan Reid (1511) | Levi Morant (1449) |
| 25 | Ryan Donlan (1549) | Alexander Chaban (1538) | Justin Miller (1535) | Luke Lockwood (1512) | Dylan Reid (1498) | Ethan Ellsworth (1447) |
| 26 | Ryan Donlan (1561) | Alexander Chaban (1524) | Justin Miller (1523) | Luke Lockwood (1521) | Ryan Houseman (1511) | Ethan Ellsworth (1437) |
| 27 | Ryan Donlan (1546) | Luke Lockwood (1532) | Dylan Reid (1521) | Ryan Houseman (1520) | Justin Miller (1511) | Ethan Ellsworth (1428) |
| 28 | Ryan Donlan (1557) | Luke Lockwood (1543) | Justin Miller (1523) | Dylan Reid (1510) | Ryan Houseman (1506) | Ethan Ellsworth (1429) |
| 29 | Ryan Donlan (1565) | Justin Miller (1535) | Luke Lockwood (1530) | Dylan Reid (1521) | Ryan Houseman (1517) | Ethan Ellsworth (1422) |
| 30 | Ryan Donlan (1576) | Justin Miller (1544) | Dylan Reid (1532) | Ryan Houseman (1527) | Luke Lockwood (1519) | Ethan Ellsworth (1413) |
| 31 | Ryan Donlan (1583) | Justin Miller (1555) | Luke Lockwood (1532) | Dylan Reid (1520) | Drake Byrd (1516) | Ethan Ellsworth (1405) |
| 32 | Ryan Donlan (1591) | Justin Miller (1566) | Luke Lockwood (1543) | Dylan Reid (1528) | Drake Byrd (1506) | Ethan Ellsworth (1396) |
| 33 | Ryan Donlan (1600) | Justin Miller (1573) | Luke Lockwood (1552) | Dylan Reid (1539) | Drake Byrd (1496) | Ethan Ellsworth (1411) |
| 34 | Ryan Donlan (1609) | Justin Miller (1582) | Luke Lockwood (1560) | Dylan Reid (1525) | Drake Byrd (1510) | Julius Long (1413) |
| 35 | Ryan Donlan (1620) | Justin Miller (1571) | Luke Lockwood (1543) | Drake Byrd (1520) | Dylan Reid (1510) | Alexander Chaban (1422) |
| 36 | Ryan Donlan (1626) | Justin Miller (1581) | Luke Lockwood (1542) | Drake Byrd (1521) | Ryan Houseman (1505) | Alexander Chaban (1410) |
| 37 | Ryan Donlan (1634) | Justin Miller (1587) | Luke Lockwood (1527) | Ryan Houseman (1518) | Drake Byrd (1508) | Alexander Chaban (1403) |

### 2025-26 Time At The Top And Bottom
| Manager | Weeks #1 | Top 3 Weeks | Bottom 3 Weeks | Avg Rank | Final Rank |
|---|---:|---:|---:|---:|---:|
| Ryan Donlan | 17 | 21 | 4 | 3.19 | 1 |
| Luke Lockwood | 10 | 29 | 0 | 2.62 | 3 |
| Drake Byrd | 6 | 17 | 1 | 3.78 | 5 |
| Alexander Chaban | 3 | 6 | 12 | 6.27 | 10 |
| Dylan Reid | 1 | 12 | 0 | 4.03 | 6 |
| Justin Miller | 0 | 18 | 6 | 4.59 | 2 |
| Ryan Houseman | 0 | 4 | 5 | 5.89 | 4 |
| Ethan Ellsworth | 0 | 4 | 28 | 8.19 | 8 |
| Levi Morant | 0 | 0 | 22 | 7.81 | 7 |
| Julius Long | 0 | 0 | 33 | 8.62 | 9 |

### 2025-26 Biggest Rating Swings
| Week | Manager | Opponent | Result | Score | Rating Before | Rating Change | Rating After |
|---|---:|---:|---:|---:|---:|---:|---:|
| 35 | Ethan Ellsworth | Luke Lockwood | W | 42-21 | 1424.5 | +16.4 | 1441.0 |
| 35 | Luke Lockwood | Ethan Ellsworth | L | 21-42 | 1559.7 | -16.4 | 1543.3 |
| 19 | Levi Morant | Luke Lockwood | W | 48-45 | 1467.0 | +15.9 | 1482.9 |
| 19 | Luke Lockwood | Levi Morant | L | 45-48 | 1583.9 | -15.9 | 1568.0 |
| 35 | Dylan Reid | Julius Long | L | 52-59 | 1525.4 | -15.8 | 1509.7 |
| 35 | Julius Long | Dylan Reid | W | 59-52 | 1412.8 | +15.8 | 1428.6 |
| 25 | Justin Miller | Levi Morant | L | 28-66 | 1550.1 | -15.4 | 1534.7 |
| 25 | Levi Morant | Justin Miller | W | 66-28 | 1449.1 | +15.4 | 1464.5 |
| 37 | Levi Morant | Luke Lockwood | W | 37-32 | 1443.3 | +15.3 | 1458.7 |
| 37 | Luke Lockwood | Levi Morant | L | 32-37 | 1542.5 | -15.3 | 1527.2 |
| 17 | Drake Byrd | Levi Morant | L | 23-45 | 1558.1 | -15.2 | 1542.8 |
| 17 | Levi Morant | Drake Byrd | W | 45-23 | 1462.5 | +15.2 | 1477.7 |
| 13 | Drake Byrd | Ethan Ellsworth | L | 39-41 | 1539.8 | -15.1 | 1524.7 |
| 13 | Ethan Ellsworth | Drake Byrd | W | 41-39 | 1449.3 | +15.1 | 1464.4 |
| 33 | Ethan Ellsworth | Levi Morant | W | 60-34 | 1396.4 | +14.9 | 1411.4 |
| 33 | Levi Morant | Ethan Ellsworth | L | 34-60 | 1483.6 | -14.9 | 1468.7 |
| 21 | Ethan Ellsworth | Justin Miller | W | 51-35 | 1450.5 | +14.8 | 1465.3 |
| 21 | Justin Miller | Ethan Ellsworth | L | 35-51 | 1533.6 | -14.8 | 1518.8 |
| 27 | Levi Morant | Ryan Donlan | W | 66-48 | 1477.5 | +14.8 | 1492.3 |
| 27 | Ryan Donlan | Levi Morant | L | 48-66 | 1560.8 | -14.8 | 1545.9 |

</section>
<section class="power-tab-panel" id="power-panel-2024-25" role="tabpanel" aria-labelledby="power-season-2024-25-label">
### 2024-25 Elo Movement
<div class="rating-chart-wrap" role="img" aria-label="2024-25 Elo rating movement chart">
<svg class="rating-chart" viewBox="0 0 1060 520" xmlns="http://www.w3.org/2000/svg">
<text class="chart-title" x="64" y="18">2024-25 Elo Movement</text>
<line class="axis-line" x1="64" y1="398" x2="884" y2="398" />
<line class="axis-line" x1="64" y1="28" x2="64" y2="398" />
<line class="grid-line" x1="64" y1="398.0" x2="884" y2="398.0" />
<text class="axis-label" x="54" y="402.0" text-anchor="end">1350</text>
<line class="grid-line" x1="64" y1="369.5" x2="884" y2="369.5" />
<text class="axis-label" x="54" y="373.5" text-anchor="end">1375</text>
<line class="grid-line" x1="64" y1="341.1" x2="884" y2="341.1" />
<text class="axis-label" x="54" y="345.1" text-anchor="end">1400</text>
<line class="grid-line" x1="64" y1="312.6" x2="884" y2="312.6" />
<text class="axis-label" x="54" y="316.6" text-anchor="end">1425</text>
<line class="grid-line" x1="64" y1="284.2" x2="884" y2="284.2" />
<text class="axis-label" x="54" y="288.2" text-anchor="end">1450</text>
<line class="grid-line" x1="64" y1="255.7" x2="884" y2="255.7" />
<text class="axis-label" x="54" y="259.7" text-anchor="end">1475</text>
<line class="grid-line" x1="64" y1="227.2" x2="884" y2="227.2" />
<text class="axis-label" x="54" y="231.2" text-anchor="end">1500</text>
<line class="grid-line" x1="64" y1="198.8" x2="884" y2="198.8" />
<text class="axis-label" x="54" y="202.8" text-anchor="end">1525</text>
<line class="grid-line" x1="64" y1="170.3" x2="884" y2="170.3" />
<text class="axis-label" x="54" y="174.3" text-anchor="end">1550</text>
<line class="grid-line" x1="64" y1="141.8" x2="884" y2="141.8" />
<text class="axis-label" x="54" y="145.8" text-anchor="end">1575</text>
<line class="grid-line" x1="64" y1="113.4" x2="884" y2="113.4" />
<text class="axis-label" x="54" y="117.4" text-anchor="end">1600</text>
<line class="grid-line" x1="64" y1="84.9" x2="884" y2="84.9" />
<text class="axis-label" x="54" y="88.9" text-anchor="end">1625</text>
<line class="grid-line" x1="64" y1="56.5" x2="884" y2="56.5" />
<text class="axis-label" x="54" y="60.5" text-anchor="end">1650</text>
<line class="grid-line" x1="64" y1="28.0" x2="884" y2="28.0" />
<text class="axis-label" x="54" y="32.0" text-anchor="end">1675</text>
<line class="tick-line" x1="64.0" y1="398" x2="64.0" y2="404" />
<text class="axis-label" x="64.0" y="422" text-anchor="middle">Start</text>
<line class="tick-line" x1="171.9" y1="398" x2="171.9" y2="404" />
<text class="axis-label" x="171.9" y="422" text-anchor="middle">5</text>
<line class="tick-line" x1="279.8" y1="398" x2="279.8" y2="404" />
<text class="axis-label" x="279.8" y="422" text-anchor="middle">10</text>
<line class="tick-line" x1="387.7" y1="398" x2="387.7" y2="404" />
<text class="axis-label" x="387.7" y="422" text-anchor="middle">15</text>
<line class="tick-line" x1="495.6" y1="398" x2="495.6" y2="404" />
<text class="axis-label" x="495.6" y="422" text-anchor="middle">20</text>
<line class="tick-line" x1="603.5" y1="398" x2="603.5" y2="404" />
<text class="axis-label" x="603.5" y="422" text-anchor="middle">25</text>
<line class="tick-line" x1="711.4" y1="398" x2="711.4" y2="404" />
<text class="axis-label" x="711.4" y="422" text-anchor="middle">30</text>
<line class="tick-line" x1="819.3" y1="398" x2="819.3" y2="404" />
<text class="axis-label" x="819.3" y="422" text-anchor="middle">35</text>
<line class="tick-line" x1="884.0" y1="398" x2="884.0" y2="404" />
<text class="axis-label" x="884.0" y="422" text-anchor="middle">38</text>
<text class="axis-caption" x="474.0" y="446" text-anchor="middle">Week</text>
<text class="axis-caption" transform="translate(18 213.0) rotate(-90)" text-anchor="middle">Elo rating</text>
<polyline class="rating-line" points="64.0,227.2 85.6,213.6 107.2,200.9 128.7,187.2 150.3,175.4 171.9,163.0 193.5,176.7 215.1,165.6 236.6,181.8 258.2,171.3 279.8,187.7 301.4,176.1 322.9,162.3 344.5,164.4 366.1,152.0 387.7,140.8 409.3,132.4 430.8,121.0 452.4,110.9 474.0,102.0 495.6,94.3 517.2,112.5 538.7,103.1 560.3,91.8 581.9,84.2 603.5,76.5 625.1,66.0 646.6,86.0 668.2,78.0 689.8,97.1 711.4,87.8 732.9,81.5 754.5,68.5 776.1,61.5 797.7,82.9 819.3,100.4 840.8,120.9 862.4,139.3 884.0,127.2" stroke="hsl(44 76% 38%)"><title>Ryan Donlan</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="127.2" r="3.5" fill="hsl(44 76% 38%)"><title>Ryan Donlan</title></circle>
<line class="legend-swatch" x1="910" y1="44" x2="932" y2="44" stroke="hsl(44 76% 38%)" />
<text class="legend-label" x="940" y="48">Ryan Donlan</text>
<polyline class="rating-line" points="64.0,227.2 85.6,213.6 107.2,227.2 128.7,227.2 150.3,214.0 171.9,226.3 193.5,238.7 215.1,253.7 236.6,240.3 258.2,227.0 279.8,212.8 301.4,198.4 322.9,186.5 344.5,202.0 366.1,214.4 387.7,199.1 409.3,188.2 430.8,206.0 452.4,192.9 474.0,179.4 495.6,168.5 517.2,184.9 538.7,172.6 560.3,183.9 581.9,172.3 603.5,161.6 625.1,151.8 646.6,142.2 668.2,129.5 689.8,121.0 711.4,111.8 732.9,103.0 754.5,115.9 776.1,106.4 797.7,95.1 819.3,87.9 840.8,81.5 862.4,70.8 884.0,89.7" stroke="hsl(352 76% 38%)"><title>Justin Miller</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="89.7" r="3.5" fill="hsl(352 76% 38%)"><title>Justin Miller</title></circle>
<line class="legend-swatch" x1="910" y1="72" x2="932" y2="72" stroke="hsl(352 76% 38%)" />
<text class="legend-label" x="940" y="76">Justin Miller</text>
<polyline class="rating-line" points="64.0,227.2 85.6,240.9 107.2,253.6 128.7,267.3 150.3,278.2 171.9,290.6 193.5,276.1 215.1,261.1 236.6,244.2 258.2,231.6 279.8,246.5 301.4,258.1 322.9,271.0 344.5,282.9 366.1,269.0 387.7,281.6 409.3,292.4 430.8,302.8 452.4,288.9 474.0,287.0 495.6,294.7 517.2,305.0 538.7,290.7 560.3,274.6 581.9,260.1 603.5,270.8 625.1,269.7 646.6,256.6 668.2,243.9 689.8,224.8 711.4,210.3 732.9,199.1 754.5,187.1 776.1,176.7 797.7,188.0 819.3,177.0 840.8,194.9 862.4,185.6 884.0,197.7" stroke="hsl(266 76% 38%)"><title>Luke Lockwood</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="197.7" r="3.5" fill="hsl(266 76% 38%)"><title>Luke Lockwood</title></circle>
<line class="legend-swatch" x1="910" y1="100" x2="932" y2="100" stroke="hsl(266 76% 38%)" />
<text class="legend-label" x="940" y="104">Luke Lockwood</text>
<polyline class="rating-line" points="64.0,227.2 85.6,240.9 107.2,253.6 128.7,239.9 150.3,226.3 171.9,238.3 193.5,252.0 215.1,239.3 236.6,223.1 258.2,210.0 279.8,224.3 301.4,236.6 322.9,223.7 344.5,239.8 366.1,225.1 387.7,210.8 409.3,197.6 430.8,209.1 452.4,196.6 474.0,210.1 495.6,196.7 517.2,186.3 538.7,176.2 560.3,194.0 581.9,181.7 603.5,170.9 625.1,181.3 646.6,170.1 668.2,182.8 689.8,198.5 711.4,213.1 732.9,201.8 754.5,218.6 776.1,208.2 797.7,197.4 819.3,179.9 840.8,168.7 862.4,179.4 884.0,196.3" stroke="hsl(12 76% 38%)"><title>Ryan Houseman</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="196.3" r="3.5" fill="hsl(12 76% 38%)"><title>Ryan Houseman</title></circle>
<line class="legend-swatch" x1="910" y1="128" x2="932" y2="128" stroke="hsl(12 76% 38%)" />
<text class="legend-label" x="940" y="132">Ryan Houseman</text>
<polyline class="rating-line" points="64.0,227.2 85.6,240.9 107.2,227.2 128.7,227.2 150.3,240.4 171.9,228.1 193.5,243.1 215.1,253.6 236.6,239.4 258.2,252.5 279.8,236.1 301.4,250.8 322.9,262.7 344.5,273.7 366.1,287.7 387.7,274.2 409.3,259.1 430.8,243.6 452.4,256.1 474.0,265.0 495.6,249.8 517.2,233.4 538.7,219.0 560.3,235.1 581.9,250.4 603.5,265.4 625.1,251.6 646.6,262.8 668.2,270.8 689.8,255.6 711.4,264.8 732.9,250.2 754.5,262.1 776.1,250.0 797.7,264.8 819.3,252.6 840.8,263.8 862.4,245.4 884.0,261.3" stroke="hsl(154 76% 38%)"><title>Drake Byrd</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="261.3" r="3.5" fill="hsl(154 76% 38%)"><title>Drake Byrd</title></circle>
<line class="legend-swatch" x1="910" y1="156" x2="932" y2="156" stroke="hsl(154 76% 38%)" />
<text class="legend-label" x="940" y="160">Drake Byrd</text>
<polyline class="rating-line" points="64.0,227.2 85.6,213.6 107.2,199.9 128.7,187.2 150.3,176.3 171.9,164.3 193.5,150.6 215.1,140.1 236.6,158.8 258.2,173.3 279.8,190.8 301.4,205.2 322.9,220.0 344.5,208.1 366.1,222.8 387.7,234.1 409.3,249.1 430.8,262.4 452.4,246.2 474.0,262.0 495.6,272.8 517.2,285.7 538.7,300.1 560.3,282.3 581.9,289.8 603.5,274.8 625.1,288.5 646.6,300.5 668.2,286.8 689.8,295.3 711.4,282.2 732.9,293.4 754.5,276.6 776.1,283.7 797.7,268.9 819.3,256.4 840.8,243.5 862.4,231.3 884.0,212.3" stroke="hsl(118 76% 38%)"><title>Levi Morant</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="212.3" r="3.5" fill="hsl(118 76% 38%)"><title>Levi Morant</title></circle>
<line class="legend-swatch" x1="910" y1="184" x2="932" y2="184" stroke="hsl(118 76% 38%)" />
<text class="legend-label" x="940" y="188">Levi Morant</text>
<polyline class="rating-line" points="64.0,227.2 85.6,213.6 107.2,200.9 128.7,214.5 150.3,201.3 171.9,189.5 193.5,177.1 215.1,165.1 236.6,182.0 258.2,167.5 279.8,185.1 301.4,172.8 322.9,186.6 344.5,175.5 366.1,165.4 387.7,180.8 409.3,195.8 430.8,185.4 452.4,201.7 474.0,216.6 495.6,230.0 517.2,211.8 538.7,226.2 560.3,242.4 581.9,254.0 603.5,240.1 625.1,241.2 646.6,229.2 668.2,243.3 689.8,227.5 711.4,236.8 732.9,251.5 754.5,239.3 776.1,248.8 797.7,265.1 819.3,276.1 840.8,289.1 862.4,275.7 884.0,258.8" stroke="hsl(224 76% 38%)"><title>Julius Long</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="258.8" r="3.5" fill="hsl(224 76% 38%)"><title>Julius Long</title></circle>
<line class="legend-swatch" x1="910" y1="212" x2="932" y2="212" stroke="hsl(224 76% 38%)" />
<text class="legend-label" x="940" y="216">Julius Long</text>
<polyline class="rating-line" points="64.0,227.2 85.6,213.6 107.2,228.2 128.7,240.9 150.3,252.7 171.9,239.0 193.5,225.3 215.1,237.4 236.6,251.6 258.2,264.8 279.8,250.0 301.4,237.1 322.9,222.3 344.5,220.3 366.1,206.8 387.7,221.1 409.3,206.0 430.8,221.5 452.4,234.6 474.0,236.5 495.6,252.1 517.2,239.1 538.7,248.6 560.3,234.5 581.9,246.8 603.5,260.7 625.1,274.5 646.6,284.1 668.2,296.8 689.8,311.0 711.4,324.1 732.9,330.4 754.5,314.6 776.1,325.0 797.7,308.8 819.3,320.9 840.8,327.3 862.4,336.6 884.0,348.9" stroke="hsl(292 76% 38%)"><title>Dylan Reid</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="348.9" r="3.5" fill="hsl(292 76% 38%)"><title>Dylan Reid</title></circle>
<line class="legend-swatch" x1="910" y1="240" x2="932" y2="240" stroke="hsl(292 76% 38%)" />
<text class="legend-label" x="940" y="244">Dylan Reid</text>
<polyline class="rating-line" points="64.0,227.2 85.6,240.9 107.2,254.6 128.7,239.9 150.3,253.1 171.9,266.8 193.5,281.3 215.1,293.9 236.6,275.2 258.2,285.7 279.8,268.1 301.4,253.3 322.9,240.7 344.5,225.2 366.1,238.7 387.7,226.0 409.3,239.2 430.8,225.9 452.4,236.0 474.0,221.1 495.6,236.3 517.2,224.1 538.7,236.4 560.3,250.5 581.9,264.9 603.5,275.8 625.1,262.1 646.6,242.2 668.2,228.0 689.8,243.2 711.4,258.7 732.9,267.5 754.5,283.3 776.1,293.8 797.7,304.5 819.3,316.9 840.8,296.5 862.4,309.9 884.0,294.0" stroke="hsl(78 76% 38%)"><title>Ethan Ellsworth</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="294.0" r="3.5" fill="hsl(78 76% 38%)"><title>Ethan Ellsworth</title></circle>
<line class="legend-swatch" x1="910" y1="268" x2="932" y2="268" stroke="hsl(78 76% 38%)" />
<text class="legend-label" x="940" y="272">Ethan Ellsworth</text>
<polyline class="rating-line" points="64.0,227.2 85.6,240.9 107.2,226.3 128.7,240.9 150.3,254.6 171.9,266.4 193.5,251.4 215.1,262.5 236.6,275.9 258.2,288.4 279.8,270.9 301.4,283.9 322.9,296.5 344.5,280.3 366.1,290.4 387.7,304.0 409.3,312.3 430.8,294.5 452.4,308.5 474.0,292.7 495.6,277.1 517.2,289.3 538.7,299.5 560.3,283.4 581.9,268.0 603.5,275.8 625.1,285.6 646.6,298.7 668.2,312.4 689.8,298.2 711.4,282.7 732.9,294.0 754.5,306.2 776.1,318.3 797.7,296.8 819.3,304.1 840.8,286.2 862.4,298.4 884.0,286.0" stroke="hsl(28 76% 38%)"><title>Alexander Chaban</title></polyline>
<circle class="rating-endpoint" cx="884.0" cy="286.0" r="3.5" fill="hsl(28 76% 38%)"><title>Alexander Chaban</title></circle>
<line class="legend-swatch" x1="910" y1="296" x2="932" y2="296" stroke="hsl(28 76% 38%)" />
<text class="legend-label" x="940" y="300">Alexander Chaban</text>
</svg>
</div>
### 2024-25 Power Rankings
| Rank | Manager | Final Rating | Net | Peak | Peak Week | Low | Low Week | Avg Rank | Weeks #1 | Top 3 Weeks | Bottom 3 Weeks |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | Justin Miller | 1620.8 | +120.8 | 1637.4 | 2024-25 37 | 1476.8 | 2024-25 7 | 2.82 | 4 | 28 | 0 |
| 2 | Ryan Donlan | 1587.8 | +87.8 | 1645.6 | 2024-25 33 | 1512.0 | 2024-25 1 | 1.45 | 26 | 37 | 0 |
| 3 | Ryan Houseman | 1527.1 | +27.1 | 1551.4 | 2024-25 36 | 1476.8 | 2024-25 2 | 4.42 | 0 | 15 | 3 |
| 4 | Luke Lockwood | 1525.9 | +25.9 | 1544.3 | 2024-25 33 | 1431.7 | 2024-25 21 | 7.08 | 0 | 6 | 20 |
| 5 | Levi Morant | 1513.1 | +13.1 | 1576.5 | 2024-25 7 | 1435.6 | 2024-25 27 | 5.79 | 4 | 9 | 13 |
| 6 | Julius Long | 1472.3 | -27.7 | 1554.6 | 2024-25 7 | 1445.7 | 2024-25 36 | 3.89 | 3 | 17 | 1 |
| 7 | Drake Byrd | 1470.1 | -29.9 | 1507.3 | 2024-25 22 | 1446.9 | 2024-25 14 | 6.29 | 0 | 0 | 7 |
| 8 | Alexander Chaban | 1448.4 | -51.6 | 1500.8 | 2024-25 2 | 1420.0 | 2024-25 33 | 8.87 | 0 | 0 | 34 |
| 9 | Ethan Ellsworth | 1441.3 | -58.6 | 1505.3 | 2024-25 19 | 1421.2 | 2024-25 35 | 7.39 | 0 | 0 | 19 |
| 10 | Dylan Reid | 1393.1 | -106.9 | 1518.6 | 2024-25 16 | 1393.1 | 2024-25 38 | 7.00 | 1 | 2 | 17 |

### 2024-25 Weekly Path
| Week | #1 | #2 | #3 | #4 | #5 | Bottom |
|---|---:|---:|---:|---:|---:|---:|
| 1 | Dylan Reid (1512) | Julius Long (1512) | Justin Miller (1512) | Levi Morant (1512) | Ryan Donlan (1512) | Ryan Houseman (1488) |
| 2 | Levi Morant (1524) | Julius Long (1523) | Ryan Donlan (1523) | Alexander Chaban (1501) | Drake Byrd (1500) | Ethan Ellsworth (1476) |
| 3 | Ryan Donlan (1535) | Levi Morant (1535) | Julius Long (1511) | Drake Byrd (1500) | Justin Miller (1500) | Luke Lockwood (1465) |
| 4 | Ryan Donlan (1546) | Levi Morant (1545) | Julius Long (1523) | Justin Miller (1512) | Ryan Houseman (1501) | Luke Lockwood (1455) |
| 5 | Ryan Donlan (1556) | Levi Morant (1555) | Julius Long (1533) | Justin Miller (1501) | Drake Byrd (1499) | Luke Lockwood (1444) |
| 6 | Levi Morant (1567) | Ryan Donlan (1544) | Julius Long (1544) | Dylan Reid (1502) | Justin Miller (1490) | Ethan Ellsworth (1453) |
| 7 | Levi Morant (1577) | Julius Long (1555) | Ryan Donlan (1554) | Dylan Reid (1491) | Ryan Houseman (1489) | Ethan Ellsworth (1441) |
| 8 | Levi Morant (1560) | Ryan Donlan (1540) | Julius Long (1540) | Ryan Houseman (1504) | Drake Byrd (1489) | Alexander Chaban (1457) |
| 9 | Julius Long (1552) | Ryan Donlan (1549) | Levi Morant (1547) | Ryan Houseman (1515) | Justin Miller (1500) | Alexander Chaban (1446) |
| 10 | Julius Long (1537) | Ryan Donlan (1535) | Levi Morant (1532) | Justin Miller (1513) | Ryan Houseman (1503) | Alexander Chaban (1462) |
| 11 | Julius Long (1548) | Ryan Donlan (1545) | Justin Miller (1525) | Levi Morant (1519) | Ryan Houseman (1492) | Alexander Chaban (1450) |
| 12 | Ryan Donlan (1557) | Justin Miller (1536) | Julius Long (1536) | Levi Morant (1506) | Dylan Reid (1504) | Alexander Chaban (1439) |
| 13 | Ryan Donlan (1555) | Julius Long (1545) | Justin Miller (1522) | Levi Morant (1517) | Dylan Reid (1506) | Luke Lockwood (1451) |
| 14 | Ryan Donlan (1566) | Julius Long (1554) | Dylan Reid (1518) | Justin Miller (1511) | Levi Morant (1504) | Alexander Chaban (1444) |
| 15 | Ryan Donlan (1576) | Julius Long (1541) | Justin Miller (1525) | Ryan Houseman (1514) | Dylan Reid (1505) | Alexander Chaban (1433) |
| 16 | Ryan Donlan (1583) | Justin Miller (1534) | Julius Long (1528) | Ryan Houseman (1526) | Dylan Reid (1519) | Alexander Chaban (1425) |
| 17 | Ryan Donlan (1593) | Julius Long (1537) | Justin Miller (1519) | Ryan Houseman (1516) | Dylan Reid (1505) | Luke Lockwood (1434) |
| 18 | Ryan Donlan (1602) | Justin Miller (1530) | Ryan Houseman (1527) | Julius Long (1522) | Dylan Reid (1493) | Alexander Chaban (1429) |
| 19 | Ryan Donlan (1610) | Justin Miller (1542) | Ryan Houseman (1515) | Julius Long (1509) | Ethan Ellsworth (1505) | Alexander Chaban (1443) |
| 20 | Ryan Donlan (1617) | Justin Miller (1552) | Ryan Houseman (1527) | Julius Long (1498) | Ethan Ellsworth (1492) | Luke Lockwood (1441) |
| 21 | Ryan Donlan (1601) | Justin Miller (1537) | Ryan Houseman (1536) | Julius Long (1514) | Ethan Ellsworth (1503) | Luke Lockwood (1432) |
| 22 | Ryan Donlan (1609) | Justin Miller (1548) | Ryan Houseman (1545) | Drake Byrd (1507) | Julius Long (1501) | Levi Morant (1436) |
| 23 | Ryan Donlan (1619) | Justin Miller (1538) | Ryan Houseman (1529) | Dylan Reid (1494) | Drake Byrd (1493) | Alexander Chaban (1451) |
| 24 | Ryan Donlan (1626) | Justin Miller (1548) | Ryan Houseman (1540) | Dylan Reid (1483) | Drake Byrd (1480) | Levi Morant (1445) |
| 25 | Ryan Donlan (1632) | Justin Miller (1558) | Ryan Houseman (1550) | Julius Long (1489) | Dylan Reid (1471) | Ethan Ellsworth (1457) |
| 26 | Ryan Donlan (1642) | Justin Miller (1566) | Ryan Houseman (1540) | Julius Long (1488) | Drake Byrd (1479) | Levi Morant (1446) |
| 27 | Ryan Donlan (1624) | Justin Miller (1575) | Ryan Houseman (1550) | Julius Long (1498) | Ethan Ellsworth (1487) | Levi Morant (1436) |
| 28 | Ryan Donlan (1631) | Justin Miller (1586) | Ryan Houseman (1539) | Ethan Ellsworth (1499) | Julius Long (1486) | Alexander Chaban (1425) |
| 29 | Ryan Donlan (1614) | Justin Miller (1593) | Ryan Houseman (1525) | Luke Lockwood (1502) | Julius Long (1500) | Dylan Reid (1426) |
| 30 | Ryan Donlan (1622) | Justin Miller (1601) | Luke Lockwood (1515) | Ryan Houseman (1512) | Julius Long (1492) | Dylan Reid (1415) |
| 31 | Ryan Donlan (1628) | Justin Miller (1609) | Luke Lockwood (1525) | Ryan Houseman (1522) | Drake Byrd (1480) | Dylan Reid (1409) |
| 32 | Ryan Donlan (1639) | Justin Miller (1598) | Luke Lockwood (1535) | Ryan Houseman (1508) | Julius Long (1489) | Dylan Reid (1423) |
| 33 | Ryan Donlan (1646) | Justin Miller (1606) | Luke Lockwood (1544) | Ryan Houseman (1517) | Julius Long (1481) | Dylan Reid (1414) |
| 34 | Ryan Donlan (1627) | Justin Miller (1616) | Luke Lockwood (1534) | Ryan Houseman (1526) | Drake Byrd (1467) | Dylan Reid (1428) |
| 35 | Justin Miller (1622) | Ryan Donlan (1611) | Luke Lockwood (1544) | Ryan Houseman (1542) | Drake Byrd (1478) | Dylan Reid (1418) |
| 36 | Justin Miller (1628) | Ryan Donlan (1593) | Ryan Houseman (1551) | Luke Lockwood (1528) | Levi Morant (1486) | Dylan Reid (1412) |
| 37 | Justin Miller (1637) | Ryan Donlan (1577) | Ryan Houseman (1542) | Luke Lockwood (1537) | Levi Morant (1496) | Dylan Reid (1404) |
| 38 | Justin Miller (1621) | Ryan Donlan (1588) | Ryan Houseman (1527) | Luke Lockwood (1526) | Levi Morant (1513) | Dylan Reid (1393) |

### 2024-25 Time At The Top And Bottom
| Manager | Weeks #1 | Top 3 Weeks | Bottom 3 Weeks | Avg Rank | Final Rank |
|---|---:|---:|---:|---:|---:|
| Ryan Donlan | 26 | 37 | 0 | 1.45 | 2 |
| Justin Miller | 4 | 28 | 0 | 2.82 | 1 |
| Levi Morant | 4 | 9 | 13 | 5.79 | 5 |
| Julius Long | 3 | 17 | 1 | 3.89 | 6 |
| Dylan Reid | 1 | 2 | 17 | 7.00 | 10 |
| Ryan Houseman | 0 | 15 | 3 | 4.42 | 3 |
| Luke Lockwood | 0 | 6 | 20 | 7.08 | 4 |
| Drake Byrd | 0 | 0 | 7 | 6.29 | 7 |
| Ethan Ellsworth | 0 | 0 | 19 | 7.39 | 9 |
| Alexander Chaban | 0 | 0 | 34 | 8.87 | 8 |

### 2024-25 Biggest Rating Swings
| Week | Manager | Opponent | Result | Score | Rating Before | Rating Change | Rating After |
|---|---:|---:|---:|---:|---:|---:|---:|
| 34 | Alexander Chaban | Ryan Donlan | W | 58-54 | 1420.0 | +18.9 | 1438.8 |
| 34 | Ryan Donlan | Alexander Chaban | L | 54-58 | 1645.6 | -18.9 | 1626.8 |
| 36 | Ethan Ellsworth | Ryan Donlan | W | 40-25 | 1421.2 | +18.0 | 1439.2 |
| 36 | Ryan Donlan | Ethan Ellsworth | L | 25-40 | 1611.4 | -18.0 | 1593.4 |
| 27 | Ethan Ellsworth | Ryan Donlan | W | 46-44 | 1469.4 | +17.5 | 1486.9 |
| 27 | Ryan Donlan | Ethan Ellsworth | L | 44-46 | 1641.6 | -17.5 | 1624.1 |
| 29 | Luke Lockwood | Ryan Donlan | W | 47-33 | 1485.4 | +16.8 | 1502.1 |
| 29 | Ryan Donlan | Luke Lockwood | L | 33-47 | 1631.0 | -16.8 | 1614.3 |
| 38 | Justin Miller | Levi Morant | L | 37-39 | 1637.4 | -16.6 | 1620.8 |
| 38 | Levi Morant | Justin Miller | W | 39-37 | 1496.5 | +16.6 | 1513.1 |
| 8 | Ethan Ellsworth | Levi Morant | W | 40-34 | 1441.4 | +16.4 | 1457.9 |
| 8 | Levi Morant | Ethan Ellsworth | L | 34-40 | 1576.5 | -16.4 | 1560.1 |
| 37 | Drake Byrd | Ryan Donlan | W | 35-34 | 1467.9 | +16.2 | 1484.0 |
| 37 | Ryan Donlan | Drake Byrd | L | 34-35 | 1593.4 | -16.2 | 1577.2 |
| 21 | Julius Long | Ryan Donlan | W | 46-32 | 1497.6 | +16.0 | 1513.5 |
| 21 | Ryan Donlan | Julius Long | L | 32-46 | 1616.7 | -16.0 | 1600.8 |
| 36 | Alexander Chaban | Luke Lockwood | W | 41-33 | 1432.5 | +15.7 | 1448.2 |
| 36 | Luke Lockwood | Alexander Chaban | L | 33-41 | 1544.2 | -15.7 | 1528.4 |
| 17 | Alexander Chaban | Justin Miller | W | 53-48 | 1425.2 | +15.7 | 1440.9 |
| 17 | Justin Miller | Alexander Chaban | L | 48-53 | 1534.3 | -15.7 | 1518.6 |

</section>
</div>
</details>

<details>
<summary><h2>Output Files</h2></summary>

These are the supporting CSVs exposed for the power rankings page.

- `power_ranking_summary.csv`
- `power_ranking_weekly.csv`
- `power_ranking_path.csv`
- `power_ranking_swings.csv`
</details>
