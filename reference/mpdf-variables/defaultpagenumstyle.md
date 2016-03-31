---
layout: page
title: defaultPageNumStyle
parent_title: mPDF Variables
permalink: /reference/mpdf-variables/defaultpagenumstyle.html
modification_time: 2015-08-05T12:01:54+00:00
---

<p>(mPDF &gt;= 6.0)</p>

# Description

<p class="manual_block">void <b>defaultPageNumStyle</b></p>
<p>Specifies a default page number style to use from the start of the document.</p>
<p>For more information, see <a href="{{ "/paging/page-numbering.html" | prepend: site.baseurl }}">page numbering</a>.</p>

# Values

<p class="manual_param_dt"><span class="parameter">defaultPageNumStyle</span></p>
<p class="manual_param_dd"><b>Values</b>

(Uses the same values as for list-style-type)

1 | A | a | I | i | disc | circle | square | decimal | lower-roman | upper-roman | lower-latin | upper-latin | lower-alpha | upper-alpha | none

arabic-indic | bengali | cambodian | cjk-decimal | devanagari | gujarati | gurmukhi | hebrew |kannada | khmer | lao | malayalam | oriya | persian | telugu | thai | urdu | tamil

"1" - decimal

"A" = upper-latin

"a" = lower-latin

"I" = upper-roman

"i" = lower-roman<span class="smallblock">

DEFAULT</span>: "1"</p>

# Changelog

<table class="table"> <thead>
<tr> <th>Version</th><th>Description</th> </tr>
</thead> <tbody>
<tr>
<td>6.0</td>
<td>Variable was added.</td>
</tr>
</tbody> </table>

# See Also

<ul>
<li class="manual_boxlist"><a href="{{ "/paging/page-numbering.html" | prepend: site.baseurl }}">Page numbering</a></li>
</ul>