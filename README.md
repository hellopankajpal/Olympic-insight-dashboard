# 📊 Olympic-insight-dashboard
 This is a Power BI dashboard titled "Olympic Insights Dashboard" that visualizes historical Olympic Games data. Here's a breakdown of its components:
Filters (left sidebar)

Year, Country, Sex (F/M), Season (Summer/Winter), Sport, and Medal type (Bronze/Silver/Gold) — all used as slicers to filter the entire dashboard.

## KPI cards (top row)

##### 207 Total Countries
##### 12K Total Athletes
##### 725 Total Events
##### 61 Number of Sports
##### 40K Total Medals
##### 13.4K Gold Medals
##### 13.1K Silver Medals
##### 13.1K(+) Bronze Medals

# 1. Which countries dominate the Olympics?
The "Total medals by country" map shows bubble sizes representing medal counts. The largest, densest bubbles cluster over Europe and North America (notably a large marker over what appears to be the Eastern US and clusters across Western/Central Europe), suggesting these regions have historically dominated medal counts. The dashboard doesn't display an exact country ranking or table, so specific country names/values can't be confirmed from this view alone — filtering by "country" or adding a top-N country chart would clarify this.
# 2. How has participation evolved over time?
The "Participation trend over the years" line chart shows a steady rise from ~1880 to the 1980s, followed by a sharp, oscillating (zig-zag) pattern from around 2000 onward. This zig-zag likely reflects alternating Summer/Winter Games in recent years being counted together, rather than a real decline/spike in participation — it's a charting artifact worth noting rather than a genuine trend reversal.
# 3. Which sports contribute the most medals?
The "Sports with their medals" bar chart is sorted descending, with Athletics, Swimming, and Rowing contributing the highest total medals, followed by Gymnastics, Fencing, and Hockey. Medal contribution drops off steadily across the remaining sports (Football, Ice Hockey, Sailing, Cycling, etc.), with the smallest bars toward Diving, Judo, and Biathlon.
# 4. Which athletes have had the greatest Olympic careers?
The athlete table ranks individuals by total medals. Michael Fred Phelps II leads by a wide margin with 28 total medals (23 Gold, 3 Silver), far ahead of others. Next tier includes Larysa Semenivna Latynina (18 total, 9 Gold, 5 Silver) and Nikolay Yefimovich Andrianov (15 total, 7 Gold, 5 Silver). Most others in the visible list cluster around 12–13 total medals.
# 5. Is gender participation becoming more balanced?
The dashboard includes a Sex filter (F/M), but no chart currently visualizes the gender trend over time — this data isn't displayed in the current view. To answer this properly, a visual would need to be added (e.g., a trend line split by Sex), since the filter alone doesn't reveal the balance.

# Summary: The dashboard directly answers questions 1 (partially, via map), 2, 3, and 4. Questions 5 and 6 require additional visuals/fields that aren't currently built into the report — the underlying data may support them, but they're not exposed in this view.
