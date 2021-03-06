Contributing to the Genesys Framework Quick-Start
======================

This document describes contribution guidelines that are specific to the Genesys Framework Quick-Start. Please read [C# Programming Guide](https://msdn.microsoft.com/en-us/library/ff926074.aspx) for more general C# .Net contribution guidelines.

Coding Style Changes
--------------------

The Genesys Framework Quick-Start is in full conformance with the style guidelines described in [Coding Style](../coding-style.md). We plan to do that with tooling, in a holistic way. In the meantime, please:

* **DO NOT** send PRs for style changes.
* **DO** give priority to the current style of the project or file you're changing even if it diverges from the general guidelines.

API Changes
-----------

* **DON'T** submit API additions to any type that has shipped in the Genesys Framework Quick-Start to the *master* branch. Instead, use the *future* branch.

