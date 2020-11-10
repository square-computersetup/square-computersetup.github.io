---
permalink: /howto/
title: "How-To Update"
author_profile: true
sidebar:
  nav: "nav-shared"
---

Here are the basics

### _pages

This is the directory with all of the pages. Filenames are not indicative of the URL which is specified in the **front matter**

### _data/navigation.yml

This contains the left-side navigation

`NOTE:` changes will take between 3-5 minutes to regenerated and visible on the GitHub hosting

<hr color='#a00'>

### Formatting


| Markdown      | Result      |
| --------      | -----       |
| `**bold**`    | **bold**    |
| `__bold__`    | __bold__    |
| `*italics*`   | *italics*   |
| `_italics_`   | _italics_   |
| `## Two`      | Header Two  |
| `### Three`   | Header Three  |
| `#### Four`   | Header Four  |
| ` > quote `   | Block-quote |

```markdown
[Link Text to Google](https://www.google.com){: target='_blank'}
```

### Backticks `` ` ``

Surround literal typed code with backticks for different formatting/handling.
Surround chunks of code with triple backticks and a syntax name (markdown/html).


## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice}` class.
{: .notice}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--primary}` class.
{: .notice--primary}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--info}` class.
{: .notice--info}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--warning}` class.
{: .notice--warning}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--success}` class.
{: .notice--success}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--danger}` class.
{: .notice--danger}


## Buttons

[Default Button](#){: .btn}
[Primary Button](#){: .btn .btn--primary .btn--large}
[Success Button](#){: .btn .btn--success}
[Warning Button](#){: .btn .btn--warning}
[Danger Button](#){: .btn .btn--danger}
[Info Button](#){: .btn .btn--info .btn--small}
[Inverse Button](#){: .btn .btn--inverse}
[Light Outline Button](#){: .btn .btn--light-outline}

```markdown
[Default Button](#){: .btn}
[Primary Button](#){: .btn .btn--primary .btn--large}
[Success Button](#){: .btn .btn--success}
[Warning Button](#){: .btn .btn--warning}
[Danger Button](#){: .btn .btn--danger}
[Info Button](#){: .btn .btn--info .btn--small}
[Inverse Button](#){: .btn .btn--inverse}
[Light Outline Button](#){: .btn .btn--light-outline}
```

