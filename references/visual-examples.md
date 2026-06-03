# Visual Examples Reference

Structured before/after transformations from the book's figures.
Load this file when the user asks about a specific example, wants to see a transformation process, or needs illustration of a principle.

---

## Example 1 — IT Ticket Trend (Intro + Ch3 Declutter)

**Context**: IT manager wants to show that losing 2 staff has hurt team productivity.

### BEFORE (Fig 0.2 / Fig 3.17 — Cluttered bar chart)
- Chart type: Grouped vertical bar chart (blue + red bars per month)
- Data: Ticket Volume Received vs Ticket Volume Processed, Jan–Dec
- Approximate values: Received peaks at ~241 (Mar), Processed at ~237 (Mar); gap widens from Aug onward (Received ~202, Processed ~156)
- Problems:
  - Heavy black chart border
  - Dense gridlines
  - Diamond/square data markers on every point
  - Y-axis labels with trailing zeros (150.00, 200.00, 250.00)
  - Diagonal x-axis month labels (harder to read)
  - Legend at bottom (reader must look back and forth)
  - No title conveying the "so what"
  - Bars make trend harder to read than lines

### AFTER (Fig 0.3 / Fig 3.23 — Clean line chart telling the story)
- Chart type: Two-line chart (grey = Received, orange/yellow = Processed)
- Title changed to action title: **"Please approve the hire of 2 FTEs"** / subtitle: "to backfill those who quit in the past year"
- Annotation added directly on chart: **"2 employees quit in May. We nearly kept up in following 2 months, but fell behind with the increase in Aug and haven't caught up since."**
- Lines labelled directly at right end ("Received", "Processed") — legend removed
- Y-axis label horizontal: "Number of tickets"
- X-axis: abbreviated months (Jan Feb Mar…), no diagonal
- Trailing zeros removed from y-axis
- Chart border removed
- Gridlines removed
- Data markers removed (except at key annotation point)
- Footnote: data source, small grey text

### Declutter Step-by-Step (Ch3, Figs 3.17–3.23)
1. Remove chart border → border gone, eye still frames the chart (Gestalt closure)
2. Remove gridlines → light grey kept only if audience needs to trace values
3. Remove data markers → only keep where serving a purpose
4. Clean axis labels → remove trailing zeros; abbreviate month names to horizontal
5. Label lines directly → "Received" and "Processed" placed at line ends
6. Colour lines consistently → label colour matches line colour (Gestalt similarity)

**Key lesson**: The AFTER version has a specific action as its title, a contextual annotation, and nothing that doesn't serve the story.

---

## Example 2 — Science Survey (Intro + Ch9 Case Study 5)

**Context**: Pilot summer science program wants to prove it changed kids' perceptions.

### BEFORE (Fig 0.4 — Two pie charts side by side)
- Two pie charts: PRE survey and POST survey
- Categories: Bored (19%), Not great (5%), OK (40%), Kind of interested (11%), Excited (25%) → POST: Bored (12%), Not great (6%), OK (14%), Kind of interested (30%), Excited (38%)
- Problem: Audience must compare segments across two separate pies — hard to see the shift. "OK" dropped from 40% to 14%; positive sentiment rose from 36% to 68%, but this is not immediately obvious.

### AFTER OPTIONS

**Alternative 1 — Show numbers directly (Fig 9.8)**
- Pull out only the key comparison numbers
- "BEFORE program: 36% of kids were Kind of interested or Excited"
- "AFTER program: 68% of kids were Kind of interested or Excited"
- Best when: single improvement metric is the whole message

**Alternative 2 — Simple grouped bar chart (Fig 0.5 / Fig 9.9)**
- 5 category pairs of bars side by side (Before = grey, After = blue)
- Title: **"Pilot program was a success"**
- Annotation left: "BEFORE program, the majority of children felt just OK about science."
- Annotation right: "AFTER program, more children were Kind of interested & Excited about science."
- Colour of annotation text matches bar colour (Gestalt similarity)
- Source footnote below
- Best when: comparing two groups across multiple categories

**Alternative 3 — 100% Stacked Horizontal Bar (Fig 9.10)**
- Two rows (Before / After), stacked bar from 0–100%
- Blue = positive (Excited + Kind of interested), Orange = neutral (OK), Grey = negative (Bored + Not great)
- Consistent baseline allows easy visual comparison of positive and negative ends
- x-axis preserved so audience can gauge % magnitude
- Best when: part-to-whole AND before/after is the message; ideal for survey scales

**Alternative 4 — Slope graph (Fig 9.11)**
- Each category shown as a line connecting BEFORE % to AFTER %
- Steep downward slope for "OK" (40% → 14%) clearly shows the drop
- Steep upward slope for "Excited" shows the gain
- Best when: you want audience to feel the magnitude of change for each category; no control over ordering (values determine position)

**Key lesson**: Pie charts make comparison hard. Grouped bars, stacked bars, or slopegraphs all tell the story more clearly depending on what aspect matters most.

---

## Example 3 — Product Pricing (Intro + Ch8 End-to-End)

**Context**: Startup needs to price a new product. Audience: VP of Product.

**Big idea**: "Based on competitor pricing analysis, we recommend entering at $150–$200."

### BEFORE (Fig 0.6 / Fig 8.1 — Rainbow grouped bar chart)
- 5 product groups (A–E) on x-axis, 7 coloured bars per group (2008–2014)
- Rainbow colours (different colour per year)
- Problems: 35 bars, rainbow colours distract, trend over time completely invisible, no story told

### TRANSFORMATION STEPS (Ch8)

**Step 1 — Remove colour variance (Fig 8.2)**
- All bars unified to grey
- Purpose: remove distraction before choosing chart type

**Step 2 — Change to line graph (Fig 8.4)**
- x-axis = years (2008–2014), y-axis = price
- Each product = one line; x-axis now = time (correct for trend)
- Interim issue: lines plotted per product with year labels cluttered

**Step 3 — Fix axis/legend (Fig 8.5)**
- All 5 product lines on shared time x-axis
- Products labelled directly at line ends
- Legend removed

**Step 4 — Eliminate clutter (Fig 8.6)**
- Chart border: removed
- Gridlines: removed
- Bold chart title: de-emphasised (not bold)
- Axis lines and labels: pushed to grey
- Colour variance: eliminated (all grey, emphasis colour added in next step)

**Step 5 — Draw attention (Figs 8.7–8.9)**
Three different story variations from same data:
- Variation A: Blue = existing products (A+B); highlight "after Product C launch in 2010, price of EXISTING products declined"
- Variation B: Blue = rise, Black = decline; shows "new product entry → price spike then decline" pattern
- Variation C: Blue data markers at 2014 only; shows "prices converged at ~$223 average in 2014"

**Step 6 — Add design polish (Fig 8.10)**
- Graph title: left-aligned, sentence case (not ALL CAPS)
- Y-axis title: added and left-aligned vertically
- X-axis title: added and left-aligned horizontally
- All alignments create clean reading entry point before audience reaches data

### AFTER (Final slide 9 — Call to action)**
- Blue shaded band = "Recommended range $150–$200"
- Action title: "To be competitive, we recommend introducing our product below the $223 average price point in the $150–$200 range"
- Grey lines = context (other products), one bold blue line = key insight

**Key lesson**: The transformation from rainbow bar chart to annotated line chart with a recommendation title is the whole 6-lesson process in one example.

---

## Example 4 — Moonville Active Users (Ch9 Case Study 2 — Animation)

**Context**: Online game company showing user growth story in a live presentation.

### Data points (approximate)
- Sep 2013: ~5,000 users
- Growth through 2014: steady rise to ~40,000
- Aug 2014: new feature launch → accelerating growth
- Jan 2015: ~60,000
- May 2015: ~95,000

### BAD approach (Fig 9.4 — Show all at once)
Show the complete line chart with sharp 2015 spike from the start.
- Problem: Audience immediately jumps to the spike, asks "what caused that?" — you've lost control.

### GOOD approach — Animation sequence (Figs 9.5–9.10)
Reveal the chart chronologically using animation:
1. Show title only: "Moonville: active users over time"
2. Reveal 2013 line segment (initial launch): voiceover about early growth
3. Reveal through mid-2014: voiceover about steady organic growth
4. Add annotation marker for "New feature launch Aug 2014"
5. Reveal 2014 sharp rise: explain driver
6. Reveal full 2015 surge with final annotation

### SLIDEUMENT version (Fig 9.11 — static for circulation)
- Full line chart shown with all annotations built in as text
- Key events annotated directly on the chart
- Same deck used for live (with animation layers) AND for offline circulation (annotations replace narration)

**Key lesson**: In a live presentation, animation = attention control. For written/circulated decks, annotations replace the narration.

---

## Example 5 — Feature Satisfaction Survey (Ch9 Case Study 3 — Logic in Order)

**Context**: Product with multiple features; user survey on adoption and satisfaction.

### Problem with original (Fig 9.12)
- Stacked bar chart for each feature, but no "so what" — no action title, no ordering logic

### Solution: Multiple story variations from one baseline

**Baseline visual**: All features in a fixed alphabetical order; all bars in neutral grey.

**Positive story variation**: "Feature A & B top user satisfaction"
- Order: sorted by (Completely satisfied + Very satisfied) descending
- Colour: dark blue for top 2 satisfaction bars; lighter blue for others
- Legend positioned left so audience reads it first

**Negative story variation**: "Features D & E need improvement"
- Same bar ORDER as positive (critical — don't re-sort!)
- Colour: burnt orange for bottom 2 features
- Legend positioned left, orange legend items first

**Neutral story variation**: "Mixed satisfaction across features"
- Same bar ORDER
- All teal, various saturations

**Key design rule**: Keep the same bar order across all variations. Changing the order for each story forces the audience to re-orient — adds cognitive load.

**Comprehensive visual (for written doc)**:
- Shows all three story segments in one chart
- Logical zigzag eye path: Bold title → Dark blue bar → Dark blue annotation box → Orange box → Orange bar → Teal bar → Teal box → Footnote

---

## Example 6 — Spaghetti Graph: Non-profit Funding (Ch9 Case Study 4)

**Context**: Types of non-profits supported by funders — Health, Education, Arts, Environment, Other — over time.

### BEFORE — Spaghetti graph
- 5 overlapping coloured lines from 2003–2013
- Lines cross repeatedly; impossible to focus on any single category

### Solutions

**Strategy 1 — Emphasise one line at a time**
- Variation A: "Health non-profits have grown" — Health line = bold blue, others = grey
- Variation B: "Education non-profits have declined" — Education line = bold blue, others = grey
- Use: For live presentation, reveal one story at a time (can animate)

**Strategy 2a — Separate vertically (small multiples)**
- 5 separate mini line charts stacked vertically, sharing the same x-axis
- Y-axis removed; data labels at start and end points only
- Use: When the trend of each category matters more than comparing values across categories

**Strategy 2b — Separate horizontally**
- 5 separate mini line charts side by side, sharing the same y-axis scale
- Use: When comparing values across categories at a given time matters more than trends

**Strategy 3 — Combine (emphasis + small multiples)**
- Small multiples layout BUT each panel highlights one category's line in blue while others stay grey
- Plus one "all lines" panel for full context
- Use: Best for written/circulated documents where you want full context AND individual story clarity

---

## Summary: Key Before/After Principles Illustrated by All Examples

| What changed | Why it matters |
|---|---|
| Bar chart → Line chart | Lines show trends; bars show comparisons |
| Rainbow colours → One highlight colour | Colour = attention; too many colours = no attention |
| Legend → Direct labels | Removes back-and-forth eye movement |
| Descriptive title → Action title | Tells audience what to DO, not just what they're looking at |
| No annotation → Contextual annotation | Explains the "so what" without requiring the audience to interpret |
| Heavy borders/gridlines → Removed | Gestalt closure; clutter adds cognitive load without adding value |
| All data shown → Key data highlighted | Audience has ~4 chunks of working memory; prioritise ruthlessly |
| Same chart for all audiences → Variations per story | Different audiences / different story angles = different emphasis |