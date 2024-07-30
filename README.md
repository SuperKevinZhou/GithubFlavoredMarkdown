# Github Flavored Markdown Ultimate Guide
Some examples for using GFM to build a better markdown.

## Contents
- [Github Flavored Markdown Ultimate Guide](#github-flavored-markdown-ultimate-guide)
    - [Contents](#contents)
    - [Alerts](#alerts)
    - [Fold](#fold)
    - [Sentence with Footnote](#sentence-with-footnote)
    - [Definition](#definition)

## Alerts

Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

Use alerts only when they are crucial for user success and limit them to one or two per article to prevent overloading the reader. Additionally, you should avoid placing alerts consecutively. Alerts cannot be nested within other elements.

To add an alert, use a special blockquote line specifying the alert type, followed by the alert information in a standard blockquote. Five types of alerts are available:

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

The source code is:
```markdown
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

## Fold

<details>
    <summary>Click to reveal!</summary>
    Looks like you click me!
</details>

## Sentence with Footnote
This is a sentence with footnote[^1]!

[^1]: This is the footnote!

## Definition

Apple
: a kind of fruit.
: the name of an IT company.