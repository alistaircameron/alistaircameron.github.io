---
layout: default
title: ac - packages
---

<br><br>
<span style = "font-family: Courier New">creeps. \\
\\
Econ and academia more generally is known to be a place where sexual misconduct goes unpunished. `creeps` is a small contribution to combatting this trend. It allows latex users to quickly and easily identify authors in their .bib files who have been sanctioned for sexual misconduct by their institution. To do so, it matches you .bib file entries to the [ASMD database](https://academic-sexual-misconduct-database.org) (and so currently only picks up US institutions).\\
<br><br>

tldr; here's a [minimum working example](https://www.overleaf.com/project/65916a0c9f98ad02ee07be00).\\
<br><br>

**Expected behaviour**

If you do not cite someone who is matched to an individual in the database, **nothing will happen**. If an author is matched to someone in the database, a message will be printed, showing you who it is, which articles you're citing in which they're an author, and a link to the case.\\
<br><br>

**Installation**

Currently, only available on overleaf, see installation details on [github](https://github.com/alistaircameron/creeps).
