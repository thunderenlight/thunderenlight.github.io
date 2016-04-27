---
layout: post
title:  "Css Design"
date:   2015-02-02
categories: Technical dbc
tags: Technical
---


![My dbc climb]({{ site.url }}/assets/imgs/lil_mount.jpg)
![My dbc journey]({{ site.url }}/assets/imgs/journey.png)

### What does it mean to display inline vs inline blocks?	
			
<img width="350px" src="/assets/imgs/inline_block.png">

I wanted to discuss the differences between the display inline vs. inline block because it was one of the hardest for me to grasp. So the firstp>The <code>display</code> CSS property specifies the type of rendering box used for an element. In HTML, default <code>display</code> property values are taken from behaviors described in the HTML specifications or from the browser/user default stylesheet. The default value in XML is <code>inline</code>.
<p>In addition to the many different display box types, the value <code>none</code> lets you turn off the display of an element; when you use <code>none</code>, all descendant elements also have their display turned off. The document is rendered as though the element doesn't exist in the document tree.
		<p><li><strong>inline</strong> - An inline box will be produced by the element. Inline box elements are not proceeded or followed by line breaks and they occupy only the width that they need.</li>
  		<li><strong>block</strong> - A block box will be produced by the element. Block box elements are proceeded and followed by line breaks. Block box elements occupy the full available width unless their widths are specifically set.</li>
  		<li><strong>list-item</strong> - The element will be displayed as a list-item element.</li>
	  <li><strong>inline-block</strong> - A combination block and inline box is produced by the element. The element will be laid out as if it were an inline box. However, the element functions as a block container to its contents. The width of the element's box can be set.</li>
	  <li><strong>table</strong> - The element functions like the HTML <a href="/html/table_tag/">&lt;table&gt;</a> element formatted as a block element.</li>
	  <li><strong>inline-table</strong> - The element functions like the HTML <a href="/html/table_tag/">&lt;table&gt;</a> element formatted as an inline element.</li>
	  <li><strong>table-row-group</strong> - The element functions like the HTML <a href="/html/tbody_tag/">&lt;tbody&gt;</a> element.</li>
	  <li><strong>table-header-group</strong> - The element functions like the HTML <a href="/html/thead_tag/">&lt;thead&gt;</a> element.</li>
	  <li><strong>table-footer-group</strong> - The element functions like the HTML <a href="/html/tfoot_tag/">&lt;tfoot&gt;</a> element.</li>
	  <li><strong>table-row</strong> - The element functions like the HTML <a href="/html/tr_tag/">&lt;tr&gt;</a> element.</li>
	  <li><strong>table-column-group</strong> - The element functions like the HTML <a href="/html/colgroup_tag/">&lt;colgroup&gt;</a> element.</li>
	  <li><strong>table-column</strong> - The element functions like the HTML <a href="/html/col_tag/">&lt;col&gt;</a> element.</li>
	  <li><strong>table-cell</strong> - The element functions like the HTML <a href="/html/td_tag/">&lt;td&gt;</a> and <a href="/html/th_tag/">&lt;th&gt;</a> elements.</li>
	  <li><strong>table-caption</strong> - The element functions like the HTML <a href="/html/caption_tag/">&lt;caption&gt;</a> element.</li>
	  <li><strong>none</strong> - The element is prevented from being displayed. No box will be produced.</li>
	  <li><strong>inherit</strong> - The <strong>inherit</strong> keyword is used to specify that the value for this property should be taken from the parent element. If <strong>inherit</strong> is used with the root element, then the initial value for this property will be used.</li>

		Web browsers render different elements in different ways. Some elements are block-level, meaning that their default display value is set to block. Block-level elements have a definable width and height and automatically create a new row in the layout as they’re created.One example of a block-level element is a paragraph.

		
