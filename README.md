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
    - [Task list](#task-list)

## Alerts

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

<details>
<summary>Source code</summary>

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
</details>

## Fold

<details>
    <summary>Click to reveal!</summary>
    Looks like you click me!
</details>

<details>
<summary>Source code</summary>

```markdown
<details>
    <summary>Click to reveal!</summary>
    Looks like you click me!
</details>
```
</details>

## Sentence with Footnote
This is a sentence with footnote[^1]!

[^1]: This is the footnote!

<details>
<summary>Source code</summary>

```markdown
This is a sentence with footnote[^1]!

[^1]: This is the footnote!
```
</details>

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

<details>
<summary>Source code</summary>

```markdown
<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```
</details>

## Keyboard
Use <kbd>Ctrl</kbd>+<kbd>C</kbd> to copy.


<details>
<summary>Source code</summary>

```markdown
Use <kbd>Ctrl</kbd>+<kbd>C</kbd> to copy.
```
</details>

## Mermaid
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

<details>
<summary>Source code</summary>

````markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````
</details>

## Task list
- [ ] Not completed yet.
- [x] Completed.

<details>
<summary>Source code</summary>

```markdown
- [ ] Not completed yet.
- [x] Completed.
```
</details>
