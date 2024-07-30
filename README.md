# Github Flavored Markdown Ultimate Guide
Some examples for using GFM to build a better markdown.

## Contents
- [Github Flavored Markdown Ultimate Guide](#github-flavored-markdown-ultimate-guide)
    - [Contents](#contents)
    - [Alerts](#alerts)
    - [Fold](#fold)
    - [Sentence with Footnote](#sentence-with-footnote)
    - [Definition](#definition)
    - [Keyboard](#keyboard)
    - [Mermaid](#mermaid)

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
The source code is:
```markdown
<details>
    <summary>Click to reveal!</summary>
    Looks like you click me!
</details>
```

## Sentence with Footnote
This is a sentence with footnote[^1]!

[^1]: This is the footnote!

The source code is:
```markdown
This is a sentence with footnote[^1]!

[^1]: This is the footnote!
```

> [!NOTE]
> `[^1]` is just after the sentence, there is no need to put it in the end.

## Definition

<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
The source code is:
```markdown
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```

## Keyboard
Use <kbd>Ctrl</kbd>+<kbd>C</kbd> to copy.
The source code is:
```markdown
Use <kbd>Ctrl</kbd>+<kbd>C</kbd> to copy.
```

## Mermaid
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

The source code is:
````markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````