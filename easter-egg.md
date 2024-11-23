---
title: "🥚 You Found It!"
layout: layouts/main.vto
---

# 🎉 Congratulations!

You've discovered our hidden easter egg page. As a fellow enthusiast of traditional building techniques, you might appreciate these fun facts:

## Did You Know?

- The world's oldest wooden building, Hōryū-ji Temple in Japan, has stood for over 1,400 years
- Roman concrete actually gets stronger over time due to seawater interaction
- Medieval builders used eggs in their mortar mixtures
- The Great Pyramid of Giza's blocks are so precisely cut that you can't fit a credit card between them
- Some traditional Japanese wood joints don't use any nails or fasteners

## Secret Building Wisdom

> "The old ways are not always the best ways, but they are always worth understanding."
> — Ancient Builder's Proverb (that we just made up)

## Your Reward

For finding this page, here's a special collection of our most interesting hidden resources:

{{for resource of search.pages("type=resource secret=true", "date=desc")}}
- [{{ resource.title }}]({{ resource.url }})
{{/for}}

[← Back to safety](/) 