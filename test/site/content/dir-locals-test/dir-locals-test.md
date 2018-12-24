---
title: ".dir-locals.el test"
description: "Test setting of few Org Hugo variables via `.dir-locals.el`."
date: 2018-10-31
tags: ["dir-locals"]
draft: false
creator: "Dummy creator string"
---

<style>
  .ox-hugo-toc ul {
    list-style: none;
  }
</style>
<div class="ox-hugo-toc toc">
<div></div>

<div class="heading">Table of Contents</div>

- <span class="section-num">1</span> [Variables set in <kbd>.dir-locals.el</kbd>](#variables-set-in)
- <span class="section-num">2</span> [Test text](#test-text)
- <span class="section-num">3</span> [Local Variables](#local-variables):ARCHIVE:

</div>
<!--endtoc-->



## <span class="section-num">1</span> Variables set in <kbd>.dir-locals.el</kbd> {#variables-set-in}

<a id="table--vars-dir-locals"></a>
<div class="table-caption">
  <span class="table-number"><a href="#table--vars-dir-locals">Table 1</a></span>:
  Variables set using <code>.dir-locals.el</code>
</div>

| Variable                               | Value                                                                   |
|----------------------------------------|-------------------------------------------------------------------------|
| `org-hugo-section`                     | `"dir-locals-test"`                                                     |
| `org-hugo-front-matter-format`         | `"yaml"`                                                                |
| `org-hugo-footer`                      | `"\n\nThis text is auto inserted at the end of the exported Markdown."` |
| `org-hugo-preserve-filling`            | `nil`                                                                   |
| `org-hugo-use-code-for-kbd`            | `t`                                                                     |
| `org-hugo-export-with-toc`             | `t`                                                                     |
| `org-hugo-export-with-section-numbers` | `t`                                                                     |
| `org-hugo-export-creator-string`       | `"Dummy creator string"`                                                |
| `org-hugo-date-format`                 | `"%Y-%m-%d"`                                                            |
| `org-hugo-auto-export-mode`            | `t`                                                                     |


## <span class="section-num">2</span> Test text {#test-text}

`This is verbatim` but <kbd>this</kbd> is wrapped in the `kbd` tag. As `org-hugo-preserve-filling` is set to `nil`, the column filling in the Org source is not preserved in the exported Markdown.


## <span class="section-num">3</span> Local Variables {#local-variables}

This text is auto inserted at the end of the exported Markdown.
