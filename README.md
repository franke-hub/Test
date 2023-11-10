# Test
Repository used for github markdown testing. It does not cover [basic github documentation.](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

For basic testing, I use the Firefox extension [Github Markdown Viewer](https://github.com/painyeph/GitLabMarkdownViewer). Unfortunately, it doesn't *exactly* match github markdown syntax,
but this repository is only on `github.com`, so it's the final arbiter of github markdown coding.

By comparing the raw markdown here with the formatted markdown, you can see how github markdown works (or doesn't) in special situations.

I'm editing this file using github's editor. It doesn't check speelling. 

## How is text that uses "\<\>" characters handled?
\#include <github.com/franke-hub/Test/edit/trunk/README.md> Sample include file coding.

#include <github.com/franke-hub/Test/edit/trunk/README.md> Sample include file coding.

\# include <github.com/franke-hub/Test/edit/trunk/README.md> You don't have to use "\\#", but you would if there was a space after the "#".

Aside: the Firefox extension discards all text between a '<' and the '>' character. If you use &lt and &gt it's happy, but (as you can see) github markdown isn't.

## Creating links to page sections in another file

- [section1](./section-page#section1)

- [section2](./section-page#section2)

- [section3](section-page#section3)

---
