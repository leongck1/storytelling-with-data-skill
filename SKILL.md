---
name: storytelling-with-data
description: >
  Frameworks and principles from "Storytelling with Data" by Cole Nussbaumer Knaflic.
  Use this skill whenever the user asks about data visualisation, presenting data, chart design, data storytelling,
  communicating insights, choosing graph types, decluttering visuals, or designing dashboards and slides.
  Also trigger when the user wants to critique or improve a chart, make a presentation more impactful,
  or structure a data-driven narrative. Even for quick questions like "what chart should I use?" or
  "how do I make this graph clearer?"—consult this skill first.
---

# Storytelling with Data — Skill

> Based on personal reading notes from Cole Nussbaumer Knaflic's book (2015).
> Read: 9 July 2024 – 22 July 2024.

## The 6 Core Lessons

1. Understand the context
2. Choose an appropriate visual to display
3. Eliminate clutter
4. Focus attention where you want it
5. Think like a designer
6. Tell a story

---

## Chapter 1: Understand the Context

### Exploratory vs Explanatory Analysis

- **Exploratory**: Understanding data for yourself — like opening 100 oysters to find 2 pearls.
- **Explanatory**: Communicating only the pearls — the specific story you want your audience to understand.
- **Common mistake**: Showing all the exploratory work (100 oysters) instead of only the 2 pearls that matter.

### The Who–What–How Framework

**WHO (Audience)**
- Be specific: identify the decision-maker. Avoid "anyone interested" or "all stakeholders."
- Consider your relationship with them — new vs established trust shapes how you structure your communication.

**WHAT (Action)**
- What do you need them to know or **do**? If you can't answer this, reconsider whether to communicate at all.
- Prompting a specific action leads to more productive conversations than just presenting data.
- The analyst usually knows the data best — don't assume your audience does.

**HOW (Mechanism)**
- **Live presentation**: Lower detail needed; you're there to answer questions. Don't read slides aloud — use speaking notes and practise.
- **Written doc/email**: High detail needed; audience controls how they consume it.
- **Slideument**: A hybrid for both live and circulation — design so it works both ways.
- **Tone**: Match it to the purpose — celebrating success, driving urgent action, or a lighthearted update.

**HOW (Context/Data)**
- **Do**: Telling a story needs the right amount of context and **both supporting and opposing data**.
- **Don't**: Only showing data that backs your point and ignoring the rest — this actually weakens credibility, not strengthens it.

### Consulting for Context (Questions to Ask)
When building someone else's communication, surface:
1. What background is essential?
2. Who is the audience and decision maker? What do we know about them?
3. What biases might make them supportive or resistant?
4. What data is available and is it familiar to the audience?
5. What factors could weaken the case — and do we need to address them proactively?
6. What would a successful outcome look like?
7. "If you had only limited time or a single sentence, what would you say?"

**Note**: The last two questions (6 and 7) are the most important — they tend to lead to the most insightful conversations.

### The 3-Minute Story & Big Idea

**3-Minute Story**: If you had only 3 minutes, what would you say? Forces clarity. Great for elevator pitches and quick updates.

**Big Idea**: One single sentence that:
- Articulates your unique point of view
- Conveys what's at stake
- Is a complete sentence

### Storyboarding (Content Planning)
- **What**: A visual outline of content before building anything.
- **Don't** start in PowerPoint — attachment to early design work resists necessary changes.
- **Do** use Post-it notes on a whiteboard — easy to rearrange, add, or remove.
- Get stakeholder sign-off at this stage to align early.

---

## Chapter 2: Choose an Effective Visual

**Key principle**: Tables use the verbal system (audience reads). Graphs use the visual system (audience sees). Choose based on what you need them to do.

### Visual Types & When to Use Them

| Visual | Use When |
|---|---|
| **Simple text** | Just 1–2 numbers to share. Make the number prominent; add a few supporting words. |
| **Table** | Multiple different units of measure. Let the design fade — light borders only. |
| **Heatmap** | Adding visual magnitude cues to a table. Always include a legend. |
| **Scatter plot** | Showing relationship between two numerical variables. |
| **Line graph** | Continuous data over time (days, months, years). Keep x-axis intervals consistent. Nonzero baseline is acceptable but use with caution. |
| **Slope graph** | Two time points or comparison points; showing relative increases/decreases across categories. Doesn't work well when many lines overlap. |
| **Vertical bar chart** | Comparing values across categories. **Must have zero baseline.** Use data labels or y-axis, not both. |
| **Stacked vertical bar** | Comparing totals and sub-component pieces. Easy to compare top and bottom segments; middle segments are hard to compare. |
| **Waterfall chart** | Showing a starting point, increases and decreases, and resulting end point. |
| **Horizontal bar chart** | Long category names; audience reads name before data. Order logically (natural ordering or most→least important). |
| **Stacked horizontal bar** | Totals + sub-components, especially for negative-to-positive portions of a whole. |
| **Square area graph** | Numbers of vastly different magnitude only. Human eyes aren't good at judging 2D area otherwise. |

### Things to AVOID
- **Never use 3D** — adds distraction, distorts perception.
- **Never tilt** a graph — misleads size perception.
- **Avoid second y-axis** (right-side axis) — confusing. Instead: label data directly, or use separate panels with same x-axis.

---

## Chapter 3: Clutter is Your Enemy

**Cognitive load**: The mental effort required to process information. Human cognitive processing capacity is limited — structure communication to minimise perceived cognitive load, because audiences quickly decide whether something is "worth the effort."

**Clutter**: Visual elements that take up space without increasing understanding. They contribute to excessive cognitive load.

### Gestalt Principles of Visual Perception

Use these to identify what is signal vs noise:

| Principle | What It Means | How to Apply |
|---|---|---|
| **Proximity** | Objects physically close together appear as a group | Space related elements together; use spacing to create columns/rows |
| **Similarity** | Objects of similar colour/shape/size appear related | Use consistent colours to show category membership |
| **Enclosure** | Objects physically enclosed appear as a group | Use shading or boxes to group related data |
| **Closure** | The eye fills in missing parts to complete a shape | Remove chart borders and unnecessary lines — the eye completes the frame |
| **Continuity** | The eye seeks the smoothest path | Remove y-axis when bar spacing provides enough context |
| **Connection** | Connected objects appear as a group | Line graphs work because lines connect related data points |

### Visual Order Principles

**Alignment**
- Avoid center-justified blocks of text — looks sloppy.
- Use left- or right-justify to create clean vertical lines.
- Avoid diagonal/rotated text — 45° is 52% slower to read; 90° is 205% slower.

**White Space**
- Never add data for the sake of filling space.
- White space directs attention to what is NOT white.
- Preserve margins; don't stretch visuals to fill available space.
- If one thing is critical, make it the only thing on the page.

**Contrast**
- Clear contrast signals "look here."
- Too many contrasting elements = none stand out. "A hawk is easy to spot in a sky of pigeons, but harder as variety increases."

### Decluttering Checklist (6 Things to Remove)
1. **Chart border** — unnecessary due to Gestalt closure
2. **Gridlines** — remove, or make light grey if audience needs to trace values
3. **Data markers** — only keep if serving a specific purpose
4. **Trailing zeros on axis labels** — no informational value
5. **Diagonal axis labels** — abbreviate or reformat to horizontal
6. **Legends** — label data lines/bars directly instead (Gestalt proximity)

---

## Chapter 4: Focus Your Audience's Attention

### Memory Types (for Visual Communication Design)

| Memory | Key Fact | Design Implication |
|---|---|---|
| **Iconic memory** | Processes in milliseconds; unconscious; tuned to pre-attentive attributes | Use pre-attentive attributes to draw attention instantly |
| **Short-term memory** | Holds only ~4 chunks at once | Don't overload a single visual |
| **Long-term memory** | Built over a lifetime; verbal + visual | Combine words and images to make messages stick |

Information path: Iconic → Short-term → either **Long-term memory** (retained) or **Oblivion** (lost).

### Pre-Attentive Attributes

Things the brain picks up **without conscious effort**:

**Size**: Relative size signals relative importance. Same importance = same size. One important thing = make it bigger.

**Colour**:
- Use sparingly — "easy to spot a hawk in a sky of pigeons, but not when there are many different birds."
- Default base colour: **grey** (allows other colours to contrast more than black would).
- Use a single bold colour to direct attention.
- Use **consistently** — same colour = same thing throughout a whole document.
- Change in colour signals a change — don't use it for novelty.
- **Colour blindness**: Avoid red+green together. Use orange (negative) + blue (positive) as an alternative, or add visual cues (+ and − signs).
- Colour conveys tone — consider cultural connotations for international audiences.
- **Brand colours**: Use if attention-grabbing. If not, use a different colour (with client approval).

**Position on Page**:
- Without cues, audiences scan **top-left to bottom-right in a zigzag**.
- Place the most important information (main takeaway or call to action) at the **top left**.

### Creating Visual Hierarchy
- Pull some items to the forefront, push others to the background.
- Use pre-attentive attributes (size, colour intensity) to create a reading order.
- Exploratory analysis: avoid pre-attentive attributes (you want to see everything equally).
- Explanatory analysis: use them to direct attention to your specific story.

---

## Chapter 5: Think Like a Designer

**"Form follows function"**: First decide what your audience needs to DO with the data (function), then create the visualisation (form) that enables it.

### Design Concepts

**Affordances**: Design elements that suggest how to interact with something (a knob affords turning; a button affords pushing). Apply this to charts — make it visually obvious how to read the chart.

**Highlight Important Stuff** (preference order for emphasis):
1. **Bold** — minimal noise, stands out, legible ✓
2. **Italics** — more noise, less stand out, less legible
3. **Underline** — most noise, least stand out, least legible
4. **Uppercase**, **Colour**, **Inverse element**, **Size** — all effective for signalling importance

**Eliminate Distractions**:
- "You know you've achieved perfection not when there's nothing more to add, but when there's nothing left to take away."
- Not all data is equally important — remove non-critical info.
- When detail isn't needed, summarise.
- Ask: "Would eliminating this change anything?" If no — remove it.
- Push necessary but non-message-impacting items to the background (use grey).
- When unsure, move to an appendix rather than the main visual.

**Create a Clear Hierarchy of Information**: Pull key items to the foreground; push context to the background. Guide the audience through content in order of importance.

### Accessibility
- The more complicated a visual looks, the less likely the audience will engage with it.
- Tips: legible typeface, clean layout, simple language, fewer words, define jargon/acronyms, favour simple over complex.

**Text is your friend** — use it to:
- Label (title, axes)
- Introduce, Explain, Reinforce
- Highlight key values
- Recommend actions
- Tell the story directly

**Best practices for text in charts**:
- Use **action titles** on slides (not just descriptive titles).
- Label graph axes clearly.
- State the conclusion in words — don't make the audience figure it out.
- Annotate directly on charts: explain nuances, highlight what to pay attention to, describe external factors.

### Aesthetics
- People perceive more aesthetic designs as easier to use — and are more patient with them.
- **Colours**: Sparse and strategic.
- **Alignment**: Create clean vertical and horizontal lines for unity.
- **White space**: Preserve margins. Don't stretch visuals to fill space.
- Collect inspiring visuals and analyse what makes them effective — then adapt.

### Gaining Acceptance for Design Changes
Human nature resists change. Strategies:
1. Articulate the *why* behind the new approach.
2. Show side-by-side before/after.
3. Provide multiple options and seek input.
4. Get a vocal, influential audience member on board first.
5. Test with a neutral third party before presenting — ask what they notice, what questions they have, which they prefer.

---

## Chapter 6: Dissecting Model Visuals (Reference Examples)

### Model Visual #1: Line Graph (Giving Campaign)
Context: Company running an annual month-long giving campaign to raise money for charity.
- Lines labelled directly (no legend needed)
- Key "progress to date" line: contrast colour + thicker line + data marker + data label + bigger text size
- De-emphasised "goal" line: thinner, light grey (same grey as title and axis — ties them together visually)
- De-emphasised "last year" line: thinner, lighter shade of the same blue as the key line — related but not competing
- Y-axis: full dollar amounts ($60,000 not $60K), unless millions
- X-axis: days labelled at intervals, not every day — audience cares about overall trend
- "Where are your eyes drawn?" test — should land on the progress-to-date line

### Model Visual #2: Annotated Line Graph with Forecast
Context: Actual and forecast annual sales.
- Solid thick line + bigger markers with white fill = actual (more certain)
- Dotted thin line + smaller markers = forecast (dotted connotes uncertainty)
- Most elements pushed to grey background; key elements in blue/dark
- Footnote in small font to de-emphasise

### Model Visual #3: 100% Stacked Bars (Consulting Projects)
Context: Progress (goal attained) of consulting projects across years.
- All elements left-aligned: title, legend, y-axis label, footnote — creates clean vertical line on the left
- Attention colour: burnt-red (not pure red — too loud; burnt-red is "just right")
- Everything else grey for clear contrast
- Bar arrangement: "Miss" at bottom (closest to x-axis baseline — easiest to compare trend), "Exceed" at top (also has baseline), "Meet" in the middle (lower priority)
- Data label inside the burnt-red bar: white text, large — reinforces what to focus on

### Model Visual #4: Positive and Negative Stacked Bars (Directors)
Context: Number of directors in a company over time — showing need vs supply.
- "Today's directors": blue (base, starting from x-axis)
- "Attrition": less saturated blue in negative direction (visually ties to "Today's directors", bar direction reinforces reduction)
- "Promotions" and "Acquisitions": green (positive connotation)
- "Unmet need (gap)": outline only, no colour fill — represents a gap visually; large bold black text
- Colour of bar = colour of its label (Gestalt similarity throughout)
- Text hierarchy: graph title bigger, y-axis bigger (rotated so needs more emphasis), "Unmet need" bigger+bold, footnote smaller and at the very bottom

### Model Visual #5: Horizontal Stacked Bars (Survey Priorities)
Context: Relative priorities in developing countries — a lot of data but strategically de-emphasised.
- Horizontal bars: easy to read long category names left-to-right
- Categories ordered by "Total %" descending — most important first
- Colour: top 3 priorities in blue (varying saturation), rest in grey — every element in a row uses the same colour
- Data labels inside bars: left-aligned, grey or darker shade of bar colour — de-emphasised
- Legend: placed directly above the bars, bold — "most / 2nd / 3rd"
- x-axis removed: data labels provide enough context, trend not important here

### Key Design Elements Across All Good Charts
- Colour of bar/line = colour of its label (Gestalt similarity)
- Strategically ordered data series (most important at baseline or at top)
- Action title + well-labelled axes + footnote for context
- "Where are your eyes drawn?" test — should land on the key message

---

## Chapter 7: Lessons in Storytelling

Stories are a time-tested structure for human communication. Three frameworks inform how to apply storytelling to data:

**Aristotle (Plays)**: Every story has a clear beginning (setup), middle (conflict), and end (resolution). Setup introduces the protagonist and their world. Conflict is the bulk — the protagonist faces a problem they lack the skills to solve, and undergoes major change. Resolution is the climax where the problem is solved and the protagonist has a new understanding of who they are.

**Robert McKee (Cinematic)**: A story expresses how and why life changes — starting with balance, then something happens that creates imbalance. The story is about restoring that balance. To find the plot, ask: What does the protagonist need to restore balance? What's keeping them from it? How will they act in the face of those forces? Then test it: "Do I believe this? Is it honest?"

**Kurt Vonnegut (Written words)**: Principles for effective communication:
- Find a subject you care about — your genuine care is the most compelling element in your style
- Do not ramble
- Keep it simple (childlike sentences)
- Have the guts to cut — remove anything that doesn't illuminate the subject
- Sound like yourself
- Say what you mean to say
- Pity the readers — be patient, willing to clarify and simplify

### Story Structure (Beginning–Middle–End)

**Beginning (Setup/Plot)**:
- The setting (when/where)
- The main character — framed in terms of your **audience**
- The imbalance (why action is needed; what has changed)
- The balance (desired outcome)
- The solution (how you'll get there)

**Middle (Conflict)**:
- Convince audience of the need for action
- Address the problem and why your solution should be accepted
- What will resonate with *this* audience? (money? competition? saving resources? innovation?)
- Integrate data as evidence

**End (Resolution/Call to Action)**:
- Recap the problem
- State clearly what you want the audience to **do**

### Narrative Flow Options
- **Chronological**: Takes audience through the analysis journey — builds credibility.
- **Leading with the ending**: Start with the call to action. Makes the audience's role clear immediately, tells them why to keep listening.

### Delivery Mode
- **Spoken (live)**: Voiceover reinforces slides; can respond to questions. Keep slides clean enough that audience listens rather than reads.
  - Manage interruptions: "Write questions down — I'll address them at the end."
- **Written**: No voiceover — write the "so what" explicitly on every slide/page.
- **Slideument**: Works for both live and circulation.

### Repetition — Bing, Bang, Bongo
Use 3-part repetition to move information from short-term to long-term memory:
1. **Bing** = Introduction / Executive Summary / Table of Contents
2. **Bang** = Main Content / Detail
3. **Bongo** = Conclusion / Recap

### Story Clarity Tactics

**Horizontal logic**: Read only the slide titles in sequence — do they tell the story on their own?
- Use **action titles** (not just descriptive ones)
- Executive summary bullets should correspond to subsequent slide titles in order

**Vertical logic**: All content on a given slide reinforces the title, and vice versa. Words reinforce the visual. Visual reinforces the words.

**Reverse storyboarding**: After building the deck, write down the main point of each slide to create an outline — compare against your intended storyboard to find gaps.

**Fresh perspective**: Show your communication to someone without context. Ask:
- What did they pay attention to?
- What did they think was important?
- Where did they have questions?

### The Main Character = Your Audience
Make the story about **them**, not about you or your process. Relevant data for your specific audience is no longer "just data" — it becomes a story.

---

## Chapter 8: End-to-End Process (Pulling It All Together)

| Step | Chapter | Action |
|---|---|---|
| 1 | Ch 1 | Understand context: Who, What (big idea), How |
| 2 | Ch 2 | Choose the right visual type for the message |
| 3 | Ch 3 | Eliminate clutter (6-point checklist) |
| 4 | Ch 4 | Add pre-attentive attributes to direct attention |
| 5 | Ch 5 | Apply design principles (accessibility + aesthetics + alignment) |
| 6 | Ch 7 | Build a story: beginning, middle, end — with narrative flow and repetition |

---

## Chapter 9: Common Challenges & Solutions

### Dark vs Light Background
- Light background (white/cream): Easier to read; focus goes to data.
- Dark background: Creates heaviness; pulls attention to background. Use only for brand requirements.
- Contrast rule: On white background, black stands out most. On black background, white/yellow stands out most.

### Spaghetti Graphs (Overlapping Lines)
**Strategy 1 — Emphasise one line at a time**: Use colour + data marker + data label to highlight one series; grey out the rest.

**Strategy 2 — Separate spatially**:
- Vertical separation: When trend of each line matters more than comparing values.
- Horizontal separation: When comparing values across lines matters more.

**Strategy 3 — Combine**: Small multiples with one highlighted series per panel + a context panel showing all. Better for written/circulated documents than live presentations.

### Pie Chart Alternatives
Pie charts require effort to compare segments. Better alternatives:

| Alternative | Best When |
|---|---|
| **Show numbers directly** | Main message is a single improvement metric |
| **Simple bar chart** | Comparing two categories; place them side by side on a common baseline |
| **100% stacked horizontal bar** | Part-to-whole comparison; survey data with scale responses |
| **Slope graph** | Showing change between two time points across multiple categories |

### Establishing Logic in Order
- Keep the **same bar/category order** across multiple related visuals to reduce cognitive effort.
- Start with a baseline "neutral" visual, then add pre-attentive attributes to tell positive, negative, or neutral stories — from the same baseline.
- There should always be a logical reason for data ordering.

### Animation in Live Presentations
- Showing a complex chart all at once loses control of where the audience looks.
- Use **animation** to reveal data chronologically — forces audience attention where you want it.
- **Slideument version**: Build a single static visual with full context for offline circulation; add animation on top for live delivery.

---

## Chapter 10: Practical Improvement

### Developing Your Skills
- **Learn your tool well** — don't let it limit you. Options: Excel (used in the book), Google Sheets, Tableau, Adobe Illustrator, Python/R/JS, PowerPoint (for animation).
- **Start on paper** — less attachment to early work; easier to explore new approaches.
- **Optometrist approach**: Version A → copy and make one change → Version B → which is better? → continue iterating.
- **Seek feedback**: Show visuals to a friend or colleague. Ask what they notice, what seems important, what questions they have.
- **Give yourself enough time**: Context understanding, crafting the big idea, iterating on visuals, forming the narrative — all require dedicated time.
- **Build an inspiration library**: When you see a great visual, pause to analyse what makes it effective. Collect and adapt.
- **Learn from bad examples too**: WTF Visualisation (wtfviz.net) — analyse why it fails and how it could be fixed.

### Recommended Resources
- storytellingwithdata.com (author's site)
- eagereyes.org
- fivethirtyeight.com/datalab
- flowingdata.com
- theguardian.com/data (The Guardian Data Blog)
- junkcharts.typepad.com (Junk Charts)
- perceptualedge.com
- visualisingdata.com
- vizwiz.blogspot.com (VizWiz)
- wtfviz.net (bad examples to learn from)

### Recommended Books
- *Data Points* — Nathan Yau (for more on exploratory analysis)
- *Resonate* — Nancy Duarte (knowing your audience, segmenting, creating common ground)
- *Show Me the Numbers* — Stephen Few (entire chapter on table design)
- *The Visual Miscellaneum* — David McCandless (colour meaning across cultures)
- *Universal Principles of Design* — William Lidwell (purpose not noted in reading notes)
- *Beyond Bullet Points* — Cliff Atkinson (using PowerPoint to tell stories)

---

## Quick Reference: Chart Selection Guide

```
What do you want to show?
│
├── ONE or TWO numbers → Simple Text
├── Multiple units of measure → Table (or Heatmap for magnitude)
├── Relationship between two variables → Scatter Plot
├── Change over time (continuous) → Line Graph
├── Change between TWO time points, multiple categories → Slope Graph
├── Compare categories
│   ├── Short category names → Vertical Bar Chart
│   └── Long category names → Horizontal Bar Chart
├── Compare totals AND sub-components → Stacked Bar (V or H)
├── Starting point + changes + ending point → Waterfall Chart
├── Part of a whole (avoiding pie) → 100% Stacked Horizontal Bar
└── Vastly different magnitudes → Square Area Graph

AVOID: 3D charts, tilted charts, second y-axis
```

---

## Reference Files

Load these when the user asks for specific examples, demonstrations, or visual illustrations:

| File | Load when |
|---|---|
| `references/visual-examples.md` | User asks about a specific before/after example, wants the real chart data/values, or needs to understand a transformation in detail |
| `references/demos/declutter-demo.html` | User wants an interactive walkthrough of the 6-step declutter process; show as a rendered HTML demo |
| `references/demos/preattentive-demo.html` | User wants to understand pre-attentive attributes interactively (colour, size, position demos) |
| `references/demos/chart-selector-demo.html` | User is choosing a chart type and wants to see live examples of each option |

When generating a demo to show the user, render the HTML file contents directly as an artifact in the conversation.

---

## Quick Reference: Pre-Attentive Attribute Decision

```
Need to highlight ONE key data point or series?
└── Bold colour on grey base + direct label

Need to create a reading order?
└── Top-left = most important; use size and colour intensity

Showing positive vs negative?
└── Separate colours + directional cues (+ / − signs for colour-blind accessibility)

Comparing two time points?
└── Slope graph with colour emphasis on key line
```