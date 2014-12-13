###9/24/14

##Institutions and vectors

**Blog wordpress/html**---->

**Write Essays Microsoft Word** ---->

**Mail Gmail** ----->

-   The way these formats get backed up are all different. 
-   **Proposal:**
    unify through plaintext (one editorial environment, one way to
    access and search)

-   Political gains: when you are in control of the unified box, you are
    able to encrypt these communications, you are able to preserve them,
    take control

-   The little boxes of editing environments ar all different

-   Tools to achieve the goal: Plaintext, markdown (it is plaintext
    format), and Editor

**Pandoc and Markdown cont’d**

-   File names with spaces and capitals

-   The editor does not matter in plaintext and markdown because there
    is no proprietary ecosystem.

-   Editors online understand Markdown. You are buying into writing in
    plaintext, and where you use it doesn’t matter (it will look the
    same). Worst case scenario: you have a human readable format. The
    formatting in Markdown is not jibberish or gunky.

-   Markdown formatting:

    -   **Bullet list**: -


-   Experimentation happening with markdown softwares (Mashable
    article). **Dillinger**

-   Markup is HTML –clutters the screen

-   Markdown – is “down” because it is human readable

-   Semantic vs. stylistic – conflated in Markdown

-   Two types of emphasis (we call it emphasis, because bold is a
    stylistic term)

    -   **: bold (secondary, double emphasis)

    -   *: italics (primary emphasis)

    -   ***: both

    -   New line: two spaces (carriage return, I want things to be on a
        different line)

    -   Renders on the same line, Markdown ignores returns

-   Headings and organization

    -   #: Heading

    -   ##: Sub heading

    -   ###: Sub sub heading

-   When you write, write. Don’t format. You are not the typesetter (the
    publisher will change what headings look like, whether italic or
    bold or other)

-   HTML has its own stylistic layers: CSS

-   Creating semantic meaningful units of text. Create meaning, and
    don’t worry about mark-up.

**List:**

    -   – (with space): creates bullet list

  **Quote**

    -   >

    -   This means we don’t have to cite in advance – changing between
        formatting.

    -   Source remains the same, and you can later render for MLA or
        Chicago, etc.

-   Unix version of markdown: Nano test.md

-   Editor has to be a plaintext editor, and you can use anything

-   Stack exchange: stack overflow – many web interfaces/blog editors
    understand markdown

**Footnotes:**

- [^1]

- [1]: note 1 

**link:**

 - [link]([www.google.com](http://www.google.com))

**Code blocks**
```
    -   ` code `: preserve everything in between the ticks (but this
        is not an exact rendering…)

    -   ```: preserves space for code in many lines

    -   useful for quoting poetry, it preserves the formatting in the
        block

    -   must hit enter after the final ``` to
```

-   Ecosystem is rich with different markdown interfaces – 79 different
    programs

-   It is both an editor and a renderer.

-   Preview box: shows how it renders

-   Two box model is a crutch.

Chair of Philosophy Department at Berkeley created Pandoc

-   Converts anything into anything; it is a universal renderer

-   Use any editor; it saves the markdown file. When you are done
    writing, you will type set

-   Authoria – reinventing the editorial process everywhere. Integrating
    markdown all the way through the pipeline

-   Pandoc is an **open source tool, command-line tool**, worthwhile
    investment

-   Start in Markdown and produce PDF, Microsoft Word file…

TERMINAL: Pandoc –v: (-: flag), pandoc version

-   More money is made by self-publishers than those who go through
    established publishers.

-   .bib format: plaintext in terminal can look for another entry in
    another file

###Pandoc

-   YAML: yet another markup language

    -   --- title: bibliography: author: ---

    -   bib.bib: looks

-   keep the same formatting within YAML (---) to enter metadata.

-   Pick an editor, start writing in markdown, convert markdown in
    pandoc

-   Indent is not a semantic element. No need – we need to identify

-   Markdown, html are conventions

-   Pandocs works in favor of academics, so it extended Markdown

####Convert files using Pandoc:

-   -so: flag: smart (makes reasonable assumptions about the English
    language), o (guess the type of file based on the extension)

-   extension and type of file (but o-command guesses the type based on
    extension. Just a shortcut)

-   command: pandoc –so test.pdf test.md (pandoc, please convert test.md
    into test.pdf and be smart about the formatting and guess the type
    of file based on the extentsion)

**Questions:**

-   How did these programs become conventions?

-   Many flags: All flags are described in –h (help file)

-   NO such thing as a file name, it is a path to a file.

-   Command line tool: very simple – do one step well. Pandoc converts
    one thing to another

-   **Pandoc –h**: help

-   Type set