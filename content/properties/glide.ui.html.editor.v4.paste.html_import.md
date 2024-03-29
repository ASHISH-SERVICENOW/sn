---
title: "glide.ui.html.editor.v4.paste.html_import"
description: "Property"
---

Description: <p>Paste formatting behavior for HTML.  This setting controls how content being pasted from sources other than Microsoft Word is filtered. Note that this includes content copied from TinyMCE itself. The supported values are:</p>

<ul>
    <li><code>clean</code> (Default) - Preserve the structure of the content such as headings, tables, and lists but remove inline styles and classes. This results in simple content that uses the site's CSS stylesheet while retaining the semantic structure from the original document.</li>
    <li><code>merge</code> - Preserve the inline formatting and structure of the original document. Invalid and proprietary styles, tags and attributes are still removed ensuring that the HTML is valid while more closely matching the original document formatting.</li>
    <li><code>prompt</code> - Prompt the user to choose between the clean and merge options after attempting to paste HTML content.</li>
</ul>

Value: `clean`