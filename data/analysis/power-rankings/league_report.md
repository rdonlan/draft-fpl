# BMS FPL Draft Power Rankings

Tracks a simple Elo-style rating across the 2024-25 and 2025-26 matchup timeline. Everyone starts at 1500, and ratings move after each gameweek based on H2H results and opponent strength.

## Best Quick Hits

- **Current Power #1**: Ryan Donlan (1656.2).
- **Highest Peak Rating**: Ryan Donlan reached 1656.2 after 2025-26 37.
- **Most Weeks At #1**: Ryan Donlan (42 weeks).

<details open>
<summary><h2>Current Power Rankings</h2></summary>

Use this table as the latest strength rating: it rewards beating strong opponents and penalizes losing to weaker opponents more heavily.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- Every manager starts at `1500` before 2024-25 week 1.
- This uses a standard Elo update with `K = 24`.
- Expected result is `1 / (1 + 10 ^ ((Opponent Rating - Manager Rating) / 400))`.
- Actual result is `1` for a win, `0.5` for a draw, and `0` for a loss.
- Updates are calculated simultaneously within each gameweek using ratings from before that gameweek.
- This first version intentionally uses only H2H result and opponent strength, with no score or margin bonus.

</details>

| Rank | Manager | Rating | Net | Peak | Peak Week | Low | Low Week | Avg Rank | Weeks #1 | Top 3 Weeks | Bottom 3 Weeks |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | Ryan Donlan | 1656.2 | +156.2 | 1656.2 | 2025-26 37 | 1512.0 | 2024-25 1 | 1.57 | 42 | 74 | 0 |
| 2 | Justin Miller | 1617.0 | +117.0 | 1637.4 | 2024-25 37 | 1476.8 | 2024-25 7 | 2.31 | 17 | 65 | 0 |
| 3 | Luke Lockwood | 1534.3 | +34.4 | 1597.8 | 2025-26 18 | 1431.7 | 2024-25 21 | 4.84 | 8 | 42 | 20 |
| 4 | Ryan Houseman | 1523.8 | +23.8 | 1551.4 | 2024-25 36 | 1476.8 | 2024-25 2 | 4.41 | 0 | 16 | 3 |
| 5 | Drake Byrd | 1501.3 | +1.3 | 1541.4 | 2025-26 16 | 1446.9 | 2024-25 14 | 5.80 | 0 | 0 | 10 |
| 6 | Dylan Reid | 1467.2 | -32.8 | 1518.6 | 2024-25 16 | 1393.1 | 2024-25 38 | 7.33 | 1 | 2 | 35 |
| 7 | Levi Morant | 1461.4 | -38.6 | 1576.5 | 2024-25 7 | 1435.6 | 2024-25 27 | 6.13 | 4 | 9 | 18 |
| 8 | Ethan Ellsworth | 1427.5 | -72.5 | 1505.3 | 2024-25 19 | 1378.1 | 2025-26 32 | 8.35 | 0 | 0 | 55 |
| 9 | Julius Long | 1419.8 | -80.2 | 1554.6 | 2024-25 7 | 1405.8 | 2025-26 34 | 6.15 | 3 | 17 | 31 |
| 10 | Alexander Chaban | 1391.5 | -108.5 | 1517.8 | 2025-26 25 | 1391.5 | 2025-26 37 | 8.11 | 0 | 0 | 53 |

</details>

<details>
<summary><h2>Weekly Power Ranking Path</h2></summary>

Use this table to see who the model considered strongest after each gameweek. The page shows the top five and the bottom-ranked manager; the CSV contains the full 1-10 order every week.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- Ratings update after each completed gameweek, then ranks are assigned from highest rating to lowest.
- The manager shown in each rank cell includes their rounded rating after that gameweek.
- The final row is the latest available week in the dataset, currently 2025-26 week 37.

</details>

| Week | #1 | #2 | #3 | #4 | #5 | Bottom |
|---|---:|---:|---:|---:|---:|---:|
| 2024-25 1 | Dylan Reid (1512) | Julius Long (1512) | Justin Miller (1512) | Levi Morant (1512) | Ryan Donlan (1512) | Ryan Houseman (1488) |
| 2024-25 2 | Levi Morant (1524) | Julius Long (1523) | Ryan Donlan (1523) | Alexander Chaban (1501) | Drake Byrd (1500) | Ethan Ellsworth (1476) |
| 2024-25 3 | Ryan Donlan (1535) | Levi Morant (1535) | Julius Long (1511) | Drake Byrd (1500) | Justin Miller (1500) | Luke Lockwood (1465) |
| 2024-25 4 | Ryan Donlan (1546) | Levi Morant (1545) | Julius Long (1523) | Justin Miller (1512) | Ryan Houseman (1501) | Luke Lockwood (1455) |
| 2024-25 5 | Ryan Donlan (1556) | Levi Morant (1555) | Julius Long (1533) | Justin Miller (1501) | Drake Byrd (1499) | Luke Lockwood (1444) |
| 2024-25 6 | Levi Morant (1567) | Ryan Donlan (1544) | Julius Long (1544) | Dylan Reid (1502) | Justin Miller (1490) | Ethan Ellsworth (1453) |
| 2024-25 7 | Levi Morant (1577) | Julius Long (1555) | Ryan Donlan (1554) | Dylan Reid (1491) | Ryan Houseman (1489) | Ethan Ellsworth (1441) |
| 2024-25 8 | Levi Morant (1560) | Ryan Donlan (1540) | Julius Long (1540) | Ryan Houseman (1504) | Drake Byrd (1489) | Alexander Chaban (1457) |
| 2024-25 9 | Julius Long (1552) | Ryan Donlan (1549) | Levi Morant (1547) | Ryan Houseman (1515) | Justin Miller (1500) | Alexander Chaban (1446) |
| 2024-25 10 | Julius Long (1537) | Ryan Donlan (1535) | Levi Morant (1532) | Justin Miller (1513) | Ryan Houseman (1503) | Alexander Chaban (1462) |
| 2024-25 11 | Julius Long (1548) | Ryan Donlan (1545) | Justin Miller (1525) | Levi Morant (1519) | Ryan Houseman (1492) | Alexander Chaban (1450) |
| 2024-25 12 | Ryan Donlan (1557) | Justin Miller (1536) | Julius Long (1536) | Levi Morant (1506) | Dylan Reid (1504) | Alexander Chaban (1439) |
| 2024-25 13 | Ryan Donlan (1555) | Julius Long (1545) | Justin Miller (1522) | Levi Morant (1517) | Dylan Reid (1506) | Luke Lockwood (1451) |
| 2024-25 14 | Ryan Donlan (1566) | Julius Long (1554) | Dylan Reid (1518) | Justin Miller (1511) | Levi Morant (1504) | Alexander Chaban (1444) |
| 2024-25 15 | Ryan Donlan (1576) | Julius Long (1541) | Justin Miller (1525) | Ryan Houseman (1514) | Dylan Reid (1505) | Alexander Chaban (1433) |
| 2024-25 16 | Ryan Donlan (1583) | Justin Miller (1534) | Julius Long (1528) | Ryan Houseman (1526) | Dylan Reid (1519) | Alexander Chaban (1425) |
| 2024-25 17 | Ryan Donlan (1593) | Julius Long (1537) | Justin Miller (1519) | Ryan Houseman (1516) | Dylan Reid (1505) | Luke Lockwood (1434) |
| 2024-25 18 | Ryan Donlan (1602) | Justin Miller (1530) | Ryan Houseman (1527) | Julius Long (1522) | Dylan Reid (1493) | Alexander Chaban (1429) |
| 2024-25 19 | Ryan Donlan (1610) | Justin Miller (1542) | Ryan Houseman (1515) | Julius Long (1509) | Ethan Ellsworth (1505) | Alexander Chaban (1443) |
| 2024-25 20 | Ryan Donlan (1617) | Justin Miller (1552) | Ryan Houseman (1527) | Julius Long (1498) | Ethan Ellsworth (1492) | Luke Lockwood (1441) |
| 2024-25 21 | Ryan Donlan (1601) | Justin Miller (1537) | Ryan Houseman (1536) | Julius Long (1514) | Ethan Ellsworth (1503) | Luke Lockwood (1432) |
| 2024-25 22 | Ryan Donlan (1609) | Justin Miller (1548) | Ryan Houseman (1545) | Drake Byrd (1507) | Julius Long (1501) | Levi Morant (1436) |
| 2024-25 23 | Ryan Donlan (1619) | Justin Miller (1538) | Ryan Houseman (1529) | Dylan Reid (1494) | Drake Byrd (1493) | Alexander Chaban (1451) |
| 2024-25 24 | Ryan Donlan (1626) | Justin Miller (1548) | Ryan Houseman (1540) | Dylan Reid (1483) | Drake Byrd (1480) | Levi Morant (1445) |
| 2024-25 25 | Ryan Donlan (1632) | Justin Miller (1558) | Ryan Houseman (1550) | Julius Long (1489) | Dylan Reid (1471) | Ethan Ellsworth (1457) |
| 2024-25 26 | Ryan Donlan (1642) | Justin Miller (1566) | Ryan Houseman (1540) | Julius Long (1488) | Drake Byrd (1479) | Levi Morant (1446) |
| 2024-25 27 | Ryan Donlan (1624) | Justin Miller (1575) | Ryan Houseman (1550) | Julius Long (1498) | Ethan Ellsworth (1487) | Levi Morant (1436) |
| 2024-25 28 | Ryan Donlan (1631) | Justin Miller (1586) | Ryan Houseman (1539) | Ethan Ellsworth (1499) | Julius Long (1486) | Alexander Chaban (1425) |
| 2024-25 29 | Ryan Donlan (1614) | Justin Miller (1593) | Ryan Houseman (1525) | Luke Lockwood (1502) | Julius Long (1500) | Dylan Reid (1426) |
| 2024-25 30 | Ryan Donlan (1622) | Justin Miller (1601) | Luke Lockwood (1515) | Ryan Houseman (1512) | Julius Long (1492) | Dylan Reid (1415) |
| 2024-25 31 | Ryan Donlan (1628) | Justin Miller (1609) | Luke Lockwood (1525) | Ryan Houseman (1522) | Drake Byrd (1480) | Dylan Reid (1409) |
| 2024-25 32 | Ryan Donlan (1639) | Justin Miller (1598) | Luke Lockwood (1535) | Ryan Houseman (1508) | Julius Long (1489) | Dylan Reid (1423) |
| 2024-25 33 | Ryan Donlan (1646) | Justin Miller (1606) | Luke Lockwood (1544) | Ryan Houseman (1517) | Julius Long (1481) | Dylan Reid (1414) |
| 2024-25 34 | Ryan Donlan (1627) | Justin Miller (1616) | Luke Lockwood (1534) | Ryan Houseman (1526) | Drake Byrd (1467) | Dylan Reid (1428) |
| 2024-25 35 | Justin Miller (1622) | Ryan Donlan (1611) | Luke Lockwood (1544) | Ryan Houseman (1542) | Drake Byrd (1478) | Dylan Reid (1418) |
| 2024-25 36 | Justin Miller (1628) | Ryan Donlan (1593) | Ryan Houseman (1551) | Luke Lockwood (1528) | Levi Morant (1486) | Dylan Reid (1412) |
| 2024-25 37 | Justin Miller (1637) | Ryan Donlan (1577) | Ryan Houseman (1542) | Luke Lockwood (1537) | Levi Morant (1496) | Dylan Reid (1404) |
| 2024-25 38 | Justin Miller (1621) | Ryan Donlan (1588) | Ryan Houseman (1527) | Luke Lockwood (1526) | Levi Morant (1513) | Dylan Reid (1393) |
| 2025-26 1 | Justin Miller (1603) | Ryan Donlan (1570) | Luke Lockwood (1537) | Ryan Houseman (1513) | Levi Morant (1502) | Dylan Reid (1411) |
| 2025-26 2 | Justin Miller (1613) | Ryan Donlan (1554) | Luke Lockwood (1528) | Ryan Houseman (1499) | Levi Morant (1486) | Dylan Reid (1426) |
| 2025-26 3 | Justin Miller (1596) | Ryan Donlan (1541) | Luke Lockwood (1541) | Ryan Houseman (1511) | Alexander Chaban (1489) | Dylan Reid (1416) |
| 2025-26 4 | Justin Miller (1605) | Ryan Donlan (1550) | Luke Lockwood (1549) | Ryan Houseman (1502) | Drake Byrd (1496) | Dylan Reid (1408) |
| 2025-26 5 | Justin Miller (1590) | Ryan Donlan (1560) | Luke Lockwood (1535) | Ryan Houseman (1515) | Drake Byrd (1511) | Dylan Reid (1422) |
| 2025-26 6 | Justin Miller (1574) | Ryan Donlan (1570) | Luke Lockwood (1545) | Drake Byrd (1501) | Ryan Houseman (1500) | Dylan Reid (1438) |
| 2025-26 7 | Justin Miller (1559) | Ryan Donlan (1556) | Luke Lockwood (1554) | Ryan Houseman (1515) | Drake Byrd (1511) | Dylan Reid (1428) |
| 2025-26 8 | Ryan Donlan (1568) | Luke Lockwood (1563) | Justin Miller (1547) | Ryan Houseman (1524) | Drake Byrd (1522) | Alexander Chaban (1435) |
| 2025-26 9 | Justin Miller (1555) | Ryan Donlan (1553) | Luke Lockwood (1550) | Drake Byrd (1536) | Ryan Houseman (1534) | Dylan Reid (1433) |
| 2025-26 10 | Justin Miller (1563) | Ryan Donlan (1561) | Luke Lockwood (1560) | Ryan Houseman (1546) | Drake Byrd (1524) | Dylan Reid (1425) |
| 2025-26 11 | Luke Lockwood (1572) | Ryan Donlan (1569) | Justin Miller (1551) | Ryan Houseman (1531) | Drake Byrd (1509) | Ethan Ellsworth (1423) |
| 2025-26 12 | Luke Lockwood (1584) | Justin Miller (1559) | Ryan Donlan (1557) | Ryan Houseman (1541) | Drake Byrd (1520) | Ethan Ellsworth (1415) |
| 2025-26 13 | Justin Miller (1571) | Luke Lockwood (1567) | Ryan Donlan (1566) | Ryan Houseman (1530) | Drake Byrd (1504) | Ethan Ellsworth (1431) |
| 2025-26 14 | Luke Lockwood (1578) | Justin Miller (1556) | Ryan Donlan (1550) | Ryan Houseman (1519) | Drake Byrd (1518) | Ethan Ellsworth (1419) |
| 2025-26 15 | Luke Lockwood (1586) | Justin Miller (1564) | Ryan Donlan (1537) | Drake Byrd (1531) | Ryan Houseman (1505) | Julius Long (1433) |
| 2025-26 16 | Luke Lockwood (1593) | Justin Miller (1573) | Ryan Donlan (1548) | Drake Byrd (1541) | Ryan Houseman (1494) | Ethan Ellsworth (1423) |
| 2025-26 17 | Luke Lockwood (1588) | Ryan Donlan (1561) | Justin Miller (1561) | Drake Byrd (1527) | Ryan Houseman (1505) | Julius Long (1415) |
| 2025-26 18 | Luke Lockwood (1598) | Ryan Donlan (1570) | Justin Miller (1570) | Drake Byrd (1517) | Ryan Houseman (1491) | Julius Long (1429) |
| 2025-26 19 | Luke Lockwood (1582) | Ryan Donlan (1578) | Justin Miller (1578) | Drake Byrd (1504) | Ryan Houseman (1504) | Ethan Ellsworth (1430) |
| 2025-26 20 | Justin Miller (1590) | Ryan Donlan (1586) | Luke Lockwood (1570) | Drake Byrd (1490) | Ryan Houseman (1489) | Ethan Ellsworth (1423) |
| 2025-26 21 | Ryan Donlan (1597) | Justin Miller (1572) | Luke Lockwood (1558) | Ryan Houseman (1501) | Drake Byrd (1477) | Ethan Ellsworth (1441) |
| 2025-26 22 | Ryan Donlan (1605) | Justin Miller (1582) | Luke Lockwood (1543) | Ryan Houseman (1491) | Drake Byrd (1487) | Ethan Ellsworth (1430) |
| 2025-26 23 | Justin Miller (1591) | Ryan Donlan (1589) | Luke Lockwood (1553) | Alexander Chaban (1494) | Ryan Houseman (1481) | Ethan Ellsworth (1419) |
| 2025-26 24 | Justin Miller (1598) | Ryan Donlan (1597) | Luke Lockwood (1539) | Alexander Chaban (1508) | Ryan Houseman (1493) | Ethan Ellsworth (1433) |
| 2025-26 25 | Ryan Donlan (1581) | Justin Miller (1581) | Luke Lockwood (1524) | Alexander Chaban (1518) | Ryan Houseman (1509) | Ethan Ellsworth (1423) |
| 2025-26 26 | Ryan Donlan (1593) | Justin Miller (1569) | Luke Lockwood (1532) | Ryan Houseman (1521) | Alexander Chaban (1506) | Ethan Ellsworth (1415) |
| 2025-26 27 | Ryan Donlan (1578) | Justin Miller (1554) | Luke Lockwood (1542) | Ryan Houseman (1529) | Levi Morant (1496) | Ethan Ellsworth (1406) |
| 2025-26 28 | Ryan Donlan (1587) | Justin Miller (1564) | Luke Lockwood (1552) | Ryan Houseman (1515) | Levi Morant (1486) | Ethan Ellsworth (1408) |
| 2025-26 29 | Ryan Donlan (1593) | Justin Miller (1575) | Luke Lockwood (1541) | Ryan Houseman (1525) | Dylan Reid (1488) | Ethan Ellsworth (1402) |
| 2025-26 30 | Ryan Donlan (1603) | Justin Miller (1582) | Ryan Houseman (1535) | Luke Lockwood (1531) | Dylan Reid (1499) | Ethan Ellsworth (1395) |
| 2025-26 31 | Ryan Donlan (1610) | Justin Miller (1592) | Luke Lockwood (1542) | Ryan Houseman (1525) | Drake Byrd (1506) | Ethan Ellsworth (1387) |
| 2025-26 32 | Ryan Donlan (1616) | Justin Miller (1601) | Luke Lockwood (1553) | Ryan Houseman (1513) | Dylan Reid (1497) | Ethan Ellsworth (1378) |
| 2025-26 33 | Ryan Donlan (1624) | Justin Miller (1608) | Luke Lockwood (1561) | Dylan Reid (1509) | Ryan Houseman (1501) | Ethan Ellsworth (1394) |
| 2025-26 34 | Ryan Donlan (1632) | Justin Miller (1615) | Luke Lockwood (1568) | Drake Byrd (1501) | Dylan Reid (1497) | Julius Long (1406) |
| 2025-26 35 | Ryan Donlan (1644) | Justin Miller (1604) | Luke Lockwood (1551) | Drake Byrd (1512) | Ryan Houseman (1502) | Alexander Chaban (1408) |
| 2025-26 36 | Ryan Donlan (1650) | Justin Miller (1612) | Luke Lockwood (1550) | Drake Byrd (1513) | Ryan Houseman (1512) | Alexander Chaban (1397) |
| 2025-26 37 | Ryan Donlan (1656) | Justin Miller (1617) | Luke Lockwood (1534) | Ryan Houseman (1524) | Drake Byrd (1501) | Alexander Chaban (1391) |

</details>

<details>
<summary><h2>Time At The Top And Bottom</h2></summary>

Use this table to separate brief peaks from sustained power: weeks at #1, weeks in the top three, and weeks in the bottom three.

| Manager | Weeks #1 | Top 3 Weeks | Bottom 3 Weeks | Avg Rank | Current Rank |
|---|---:|---:|---:|---:|---:|
| Ryan Donlan | 42 | 74 | 0 | 1.57 | 1 |
| Justin Miller | 17 | 65 | 0 | 2.31 | 2 |
| Luke Lockwood | 8 | 42 | 20 | 4.84 | 3 |
| Levi Morant | 4 | 9 | 18 | 6.13 | 7 |
| Julius Long | 3 | 17 | 31 | 6.15 | 9 |
| Dylan Reid | 1 | 2 | 35 | 7.33 | 6 |
| Ryan Houseman | 0 | 16 | 3 | 4.41 | 4 |
| Drake Byrd | 0 | 0 | 10 | 5.80 | 5 |
| Alexander Chaban | 0 | 0 | 53 | 8.11 | 10 |
| Ethan Ellsworth | 0 | 0 | 55 | 8.35 | 8 |

</details>

<details>
<summary><h2>Biggest Rating Swings</h2></summary>

Use this table to find the matchups that changed the power ratings the most, usually upsets or wins between highly rated managers.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- **Rating Change** is the manager's Elo movement from that matchup week.
- Positive changes are good; negative changes are bad.
- The table is sorted by the absolute size of the swing, so a painful drop can appear beside a big gain from the same matchup.

</details>

| Week | Manager | Opponent | Result | Score | Rating Before | Rating Change | Rating After |
|---|---:|---:|---:|---:|---:|---:|---:|
| 2024-25 34 | Alexander Chaban | Ryan Donlan | W | 58-54 | 1420.0 | +18.9 | 1438.8 |
| 2024-25 34 | Ryan Donlan | Alexander Chaban | L | 54-58 | 1645.6 | -18.9 | 1626.8 |
| 2025-26 1 | Dylan Reid | Ryan Donlan | W | 51-43 | 1393.1 | +18.1 | 1411.2 |
| 2025-26 1 | Ryan Donlan | Dylan Reid | L | 43-51 | 1587.8 | -18.1 | 1569.7 |
| 2024-25 36 | Ethan Ellsworth | Ryan Donlan | W | 40-25 | 1421.2 | +18.0 | 1439.2 |
| 2024-25 36 | Ryan Donlan | Ethan Ellsworth | L | 25-40 | 1611.4 | -18.0 | 1593.4 |
| 2025-26 1 | Alexander Chaban | Justin Miller | W | 59-39 | 1448.4 | +17.5 | 1465.9 |
| 2025-26 1 | Justin Miller | Alexander Chaban | L | 39-59 | 1620.8 | -17.5 | 1603.3 |
| 2024-25 27 | Ethan Ellsworth | Ryan Donlan | W | 46-44 | 1469.4 | +17.5 | 1486.9 |
| 2024-25 27 | Ryan Donlan | Ethan Ellsworth | L | 44-46 | 1641.6 | -17.5 | 1624.1 |
| 2025-26 21 | Ethan Ellsworth | Justin Miller | W | 51-35 | 1423.3 | +17.3 | 1440.6 |
| 2025-26 21 | Justin Miller | Ethan Ellsworth | L | 35-51 | 1589.7 | -17.3 | 1572.3 |
| 2025-26 35 | Ethan Ellsworth | Luke Lockwood | W | 42-21 | 1407.0 | +17.2 | 1424.2 |
| 2025-26 35 | Luke Lockwood | Ethan Ellsworth | L | 21-42 | 1568.4 | -17.2 | 1551.2 |
| 2025-26 13 | Dylan Reid | Luke Lockwood | W | 45-38 | 1427.6 | +17.1 | 1444.7 |
| 2025-26 13 | Luke Lockwood | Dylan Reid | L | 38-45 | 1584.3 | -17.1 | 1567.2 |
| 2025-26 25 | Justin Miller | Levi Morant | L | 28-66 | 1598.0 | -16.8 | 1581.3 |
| 2025-26 25 | Levi Morant | Justin Miller | W | 66-28 | 1451.4 | +16.8 | 1468.2 |
| 2024-25 29 | Luke Lockwood | Ryan Donlan | W | 47-33 | 1485.4 | +16.8 | 1502.1 |
| 2024-25 29 | Ryan Donlan | Luke Lockwood | L | 33-47 | 1631.0 | -16.8 | 1614.3 |
| 2025-26 3 | Ethan Ellsworth | Justin Miller | W | 49-30 | 1470.3 | +16.7 | 1486.9 |
| 2025-26 3 | Justin Miller | Ethan Ellsworth | L | 30-49 | 1613.1 | -16.7 | 1596.4 |
| 2024-25 38 | Justin Miller | Levi Morant | L | 37-39 | 1637.4 | -16.6 | 1620.8 |
| 2024-25 38 | Levi Morant | Justin Miller | W | 39-37 | 1496.5 | +16.6 | 1513.1 |
| 2024-25 8 | Ethan Ellsworth | Levi Morant | W | 40-34 | 1441.4 | +16.4 | 1457.9 |
| 2024-25 8 | Levi Morant | Ethan Ellsworth | L | 34-40 | 1576.5 | -16.4 | 1560.1 |
| 2025-26 23 | Alexander Chaban | Ryan Donlan | W | 36-34 | 1478.2 | +16.2 | 1494.4 |
| 2025-26 23 | Ryan Donlan | Alexander Chaban | L | 34-36 | 1604.8 | -16.2 | 1588.6 |
| 2024-25 37 | Drake Byrd | Ryan Donlan | W | 35-34 | 1467.9 | +16.2 | 1484.0 |
| 2024-25 37 | Ryan Donlan | Drake Byrd | L | 34-35 | 1593.4 | -16.2 | 1577.2 |

</details>

<details>
<summary><h2>Output Files</h2></summary>

These are the supporting CSVs exposed for the power rankings page.

- `power_ranking_summary.csv`
- `power_ranking_weekly.csv`
- `power_ranking_path.csv`
- `power_ranking_swings.csv`
</details>
