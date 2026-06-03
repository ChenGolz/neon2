# NEON_HEARTBEAT_DESIGN_SAME_FUNCTIONALITY_V1

This version keeps the attached neon heartbeat visual design, while using the latest functionality/data from the final art-deco version:

- latest 85-person dataset
- family-group data and group photos
- focus mode: dim unrelated people and illuminate direct family/connected people
- full story modal with relatives section and candles
- search / next / previous / pause
- mobile 3+3 responsive layout, enlarged for readability
- local `START_SITE.bat` launcher


V3 custom appearance order applied.


V4 synced final:
- Same content/data/order/functionality as the matching version.
- Removed story filter UI.
- Mobile search is between poem and people cards; controls are at the bottom.
- Mobile portrait grid spacing fixed to avoid overlapping cards/names.
- Images folder omitted by request.


V5 mobile polish:
- Search stays between poem and portraits but no longer overlaps portraits.
- Portrait rows have more vertical breathing room.
- Portrait/text scale refined for mobile readability.
- Poem decorative badge no longer covers first line.
- Images folder omitted by request.


V6 mobile rechecked:
- Better mobile vertical composition.
- Search no longer touches top portraits.
- More spacing between top-row labels and lower-row portraits.
- Portrait size tuned for 320px and larger phones.
- Modal/story mobile protection improved.


Excel summaries update:
- Integrated 85 not-too-short summaries from the uploaded Excel-derived summary JSON.
- Matched every person to their Excel row and wrote summary_match_report.csv.
- Updated data.json and data.js.
- Added cache-busting query strings in index.html.
- images/ folder omitted.


Long Excel summaries + relatives update:
- Rebuilt storySummary/storySummaryClean from the full Excel row content, with longer descriptions.
- Updated first-degree family fields and relativesLines.
- Added excel_long_summaries_and_relatives_report.csv for checking each row match.
- Added cache busting version long-excel-relatives-v4.
- images/ folder omitted.


V11 polish: cleaned generic attack boilerplate from summaries and fixed several relation/summary edge cases.


V12 updated descriptions + auto family highlight:
- Replaced card/story descriptions using the uploaded Excel file מעודכן תקציר אנשים.xlsx.
- Kept the same data/functionality in both designs.
- Added automatic focus/highlight cycling when user does not click.
- Family/group members are highlighted together where relationship data is present.
- images/ folder omitted.


V16:
- Slowed automatic card/image rotation to 11 seconds.
- Automatic highlight no longer reshuffles visible cards; family members already visible are highlighted together.
- Full printable memorial candle label with title, parents, dates, quote, memorial line, blessing.
- Print button opens browser print dialog so the user can choose Save to PDF.
- Improved story text and candle label visual styling.


V17 slow fade rotation:
- Slower 18s rotation.
- Smooth fade-out / fade-in between changing people.
- Auto-highlight delayed and prevented during fade transitions.
- Cache-busting updated in index.html.


V18 sequential crossfade:
- Initial line starts empty and people fade in one by one.
- Slot changes now crossfade instead of remove-then-add.
- Cache-busting updated.


V19 streaming equal-time:
- Empty-line start.
- Streaming sequence with equal time for each person.
- Ophir → Omer → Aviv while Ophir out → Livnat while Omer out.
- Cache-busting updated.
