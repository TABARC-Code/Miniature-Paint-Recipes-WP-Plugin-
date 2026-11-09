# Miniature Paint Recipes

A WordPress plugin for recording and sharing miniature painting methods.

I wanted somewhere to keep the details that tend to disappear between painting sessions: the basecoat, the odd mix, the glaze that worked, and the highlight I'd otherwise have to work out all over again. Miniature Paint Recipes keeps those details together, then makes them useful as a guide on a website or a printed sheet beside the painting desk.

## What it does

- **Painting guides:** Build recipes with paints, mixing notes, techniques, step-by-step instructions and photographs.
- **Paint library:** Reuse paint entries across guides, with brands, ranges, colour references and recorded alternatives.
- **Step references:** Link paints to the stages where they're used, rather than leaving readers to hunt through a long list.
- **Quantity estimates:** Enter how many of the same miniature you're painting. The calculator scales the recipe's estimated paint usage from its recorded baseline.
- **WordPress publishing:** Insert a recipe into a post with a Gutenberg block or shortcode.
- **Printable sheets:** Keep the method handy at the workbench without constantly unlocking a phone.
- **Organisation:** Browse and maintain recipes using painting-related categories and taxonomies.
- **Community submissions:** Let visitors submit a recipe for editorial review rather than publishing it immediately.
- **Maintenance:** Import and export recipe data, duplicate recipes and manage cached output.

## Getting started

1. Download the plugin ZIP.
2. In WordPress, open **Plugins > Add New Plugin > Upload Plugin**.
3. Upload the ZIP, install it and activate **Miniature Paint Recipes**.
4. Create a painting recipe in the dashboard. Add its paints and painting stages, then publish it.
5. Insert the recipe into an article using the block editor or a shortcode.

If you prefer a manual installation, extract the plugin folder into `wp-content/plugins/` and activate it from the dashboard.

## Shortcodes

Display a recipe by its WordPress post ID:

```text
[paint_recipe id="123"]
```

Request its print layout:

```text
[paint_recipe id="123" print="1"]
```

Show the visitor submission form:

```text
[paint_recipe_submit]
```

Replace `123` with the actual recipe ID.

## Paint estimates

The calculator is deliberately small in scope. One recipe describes one miniature type or painting task, and the reader enters how many identical miniatures they intend to paint.

The result is an estimate, not a promise that a bottle will cover exactly twenty models. Primer, thinning, coats and technique all change the amount used. The calculator is there to help plan a session, not to invent precision we haven't measured.

## Templates

Theme overrides are supported at:

```text
yourtheme/mpr/card.php
yourtheme/mpr/print.php
```

That keeps the painting data separate from its presentation. Change the appearance without having to rewrite the instructions.

## Licence

**Licence:** See the `LICENSE` file for the applicable terms.

## Author

**TABARC-Code**  
https://github.com/TABARC-Code/

I want the plugin to make painting methods easier to record, find and follow. There are plenty of ways to make a hobby tool complicated. Most of them aren't improvements.
