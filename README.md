# Storytelling with Data — Claude Skill

A data visualisation skill for [Claude](https://claude.ai) based on [**Storytelling with Data**](https://www.storytellingwithdata.com/books) by **Cole Nussbaumer Knaflic**.

## About the Book

*Storytelling with Data* (2015) is a bestselling data visualisation guide by **Cole Nussbaumer Knaflic**, founder and CEO of [storytelling with data (SWD)](https://www.storytellingwithdata.com). Cole spent years honing her data visualisation skills in banking, private equity, and as a manager in Google's People Analytics team — where she developed a data visualisation course that became so popular she eventually launched her own company. She is the author of five bestselling books on data communication, and her workshops have been sought after by companies and philanthropic organisations all over the world.

The book teaches six core lessons for communicating effectively with data: understanding context, choosing the right visual, eliminating clutter, focusing attention, thinking like a designer, and telling a story. It has been adopted as a textbook by more than 100 universities, translated into a dozen languages, and used as the course book for tens of thousands of SWD workshop participants.

**I highly recommend reading the full book** — it is full of rich examples, annotated before-and-afters, and nuance that no set of notes can fully capture. You can purchase it from [Amazon](https://www.amazon.com/Storytelling-Data-Visualization-Business-Professionals/dp/1119002257), [storytellingwithdata.com](https://www.storytellingwithdata.com/books), or your local bookstore.

## Why I Made This

I read *Storytelling with Data* from **9 July to 22 July 2024** — taking detailed notes throughout. The book changed the way I think about presenting data, and I wanted to keep its principles close at hand rather than having to flip back through notes.

So I turned my personal reading notes into a Claude skill. This way, whenever I need a reminder about choosing the right chart, decluttering a visual, or structuring a data story, Claude can guide me through the framework from the book.

**This skill is built entirely from my own notes** — it captures the key concepts, frameworks, and before/after examples as I understood them. It's a personal study companion, not an official resource. For the full depth of Cole's insights, please read the book itself.

## What This Skill Does

This skill teaches Claude to help you communicate data effectively, covering the book's full 6-lesson framework:

| Lesson | Topic |
|---|---|
| 1 | **Understand context** — Who, What, How; Big Idea; 3-minute story; storyboarding |
| 2 | **Choose an effective visual** — 12 chart types with when and how to use each |
| 3 | **Eliminate clutter** — Gestalt principles; 6-step declutter checklist |
| 4 | **Focus attention** — Memory types; pre-attentive attributes (size, colour, position) |
| 5 | **Think like a designer** — Affordances, hierarchy, accessibility, aesthetics |
| 6 | **Tell a story** — Aristotle/McKee/Vonnegut frameworks applied to data |

It also includes **interactive HTML demos** for the declutter process, pre-attentive attributes, and chart type selection — and **6 annotated before/after case studies** with the real data from the book's figures.

## Installation

### Manual

Copy the `storytelling-with-data/` folder into your Claude skills directory.

## Skill Structure

```
storytelling-with-data/
├── SKILL.md                          # Main skill — all 10 chapters, frameworks, quick references
├── README.md                         # This file
├── LICENSE.txt                       # MIT License
└── references/
    ├── visual-examples.md            # 6 before/after case studies with real chart data
    └── demos/
        ├── declutter-demo.html       # Interactive 6-step declutter walkthrough
        ├── preattentive-demo.html    # Live pre-attentive attributes explorer
        └── chart-selector-demo.html  # Chart type picker with live examples
```

## When It Triggers

The skill activates when you ask Claude about:

- Choosing or critiquing a chart type
- Making a chart or dashboard clearer or less cluttered
- Presenting data to an audience or in a slide deck
- Structuring a data-driven story or narrative
- Gestalt principles, pre-attentive attributes, or visual hierarchy
- Improving a report, visualisation, or presentation

## Credits

All concepts, frameworks, and strategies in this skill originate from [*Storytelling with Data*](https://www.storytellingwithdata.com/books) by **Cole Nussbaumer Knaflic** (published by Wiley, 2015). This skill was created from personal reading notes and is intended as a study companion — not a replacement for the book.

- **Book:** [Storytelling with Data](https://www.storytellingwithdata.com/books) by Cole Nussbaumer Knaflic
- **Author's website:** [storytellingwithdata.com](https://www.storytellingwithdata.com)
- **Buy the book:** [Amazon](https://www.amazon.com/Storytelling-Data-Visualization-Business-Professionals/dp/1119002257) · [storytellingwithdata.com](https://www.storytellingwithdata.com/books)

## Disclaimer

This skill is an unofficial, personal project and is not affiliated with, endorsed by, or connected to Cole Nussbaumer Knaflic, storytelling with data (SWD), or Wiley in any way. All intellectual property belongs to the respective owners.

## License

MIT — see [LICENSE.txt](./LICENSE.txt)