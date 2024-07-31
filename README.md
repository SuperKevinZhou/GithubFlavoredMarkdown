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

<details>
<summary>Something fun</summary>

<div class="markdown-alert markdown-alert-note" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-info mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg>Note</p><p dir="auto">Useful information that users should know, even when skimming content.</p>
</div>

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
