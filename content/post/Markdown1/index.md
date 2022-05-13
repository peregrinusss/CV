---
title: Markdown
subtitle: A lightweight markup language for creating formatted text using a plain-text editor.

# Summary for listings and search engines
summary: About a lightweight markup language for creating formatted text using a plain-text editor.

# Link this post with a project
projects: []

# Date published
date: '2022-05-13T14:30:00Z'

# Date updated
lastmod: '2022-05-13T14:30:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Markdown

categories:
  - Theory

---

## <b>Markdown</b>
<hr>

Markdown is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form. Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files.

The initial description of Markdown contained ambiguities and raised unanswered questions, causing implementations to both intentionally and accidentally diverge from the original version. This was addressed in 2014, when long-standing Markdown contributors released CommonMark, an unambiguous specification and test suite for Markdown.

## <b>History</b>
<hr>

In 2002 Aaron Swartz created atx, "the true structured text format". Swartz and Gruber then worked together to create the Markdown language in 2004, with the goal of enabling people "to write using an easy-to-read and easy-to-write plain text format, optionally convert it to structurally valid XHTML (or HTML)".

Its key design goal was readability, that the language be readable as-is, without looking like it has been marked up with tags or formatting instructions unlike text formatted with a markup language, such as Rich Text Format (RTF) or HTML, which have obvious tags and formatting instructions. To this end, its main inspiration is the existing conventions for marking up plain text in email, though it also draws from earlier markup languages, notably setext, Textile, and reStructuredText.

Gruber wrote a Perl script, ```Markdown.pl```, which converts marked-up text input to valid, well-formed XHTML or HTML and replaces angle brackets ```(<, >)``` and ampersands ```(&)``` with their corresponding character entity references. It can take the role of a standalone script, a plugin for Blosxom or a Movable Type, or of a text filter for BBEdit.

## <b>Rise and divergence</b>
<hr>

As Markdown's popularity grew rapidly, many Markdown implementations appeared, driven mostly by the need for additional features such as tables, footnotes, definition lists,[note 1] and Markdown inside HTML blocks.

The behavior of some of these diverged from the reference implementation, as Markdown was only characterised by an informal specification and a Perl implementation for conversion to HTML.

At the same time, a number of ambiguities in the informal specification had attracted attention. These issues spurred the creation of tools such as Babelmark to compare the output of various implementations, and an effort by some developers of Markdown parsers for standardisation. However, Gruber has argued that complete standardization would be a mistake: "Different sites (and people) have different needs. No one syntax would make all happy."

## <b>Standardization</b>
<hr>

From 2012, a group of people, including Jeff Atwood and John MacFarlane, launched what Atwood characterised as a standardisation effort. A community website now aims to "document various tools and resources available to document authors and developers, as well as implementors of the various Markdown implementations". In September 2014, Gruber objected to the usage of "Markdown" in the name of this effort and it was rebranded as CommonMark. CommonMark.org published several versions of a specification, reference implementation, test suite, and "[plans] to announce a finalized 1.0 spec and test suite in 2019." No 1.0 spec has since been released as major issues still remain unsolved. Nonetheless, the following sites and projects have adopted CommonMark: Discourse, GitHub, GitLab, Reddit, Qt, Stack Exchange (Stack Overflow), and Swift.

In March 2016 two relevant informational Internet RFCs were published:

RFC 7763 introduced MIME type ```text/markdown```.
RFC 7764 discussed and registered the variants MultiMarkdown, GitHub Flavored Markdown (GFM), Pandoc, and Markdown Extra among others.
