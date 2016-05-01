# JayList
Threadsafe circular dynamic array-based implementation of deque

Skip to content
This repository
Search
Pull requests
Issues
Gist
 @jaewany
 Unwatch 1
  Star 0
  Fork 0 jaewany/JayList
 Code  Issues 0  Pull requests 0  Wiki  Pulse  Graphs  Settings
Branch: master Find file Copy pathJayList/JayList.html
b4c701b  2 minutes ago
@jaewany jaewany javadoc
1 contributor
RawBlameHistory     790 lines (789 sloc)  28.9 KB
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<!-- NewPage -->
<html lang="en">
<head>
<!-- Generated by javadoc (1.8.0_65) on Sun May 01 02:51:44 EDT 2016 -->
<title>JayList</title>
<meta name="date" content="2016-05-01">
<link rel="stylesheet" type="text/css" href="stylesheet.css" title="Style">
<script type="text/javascript" src="script.js"></script>
</head>
<body>
<script type="text/javascript"><!--
    try {
        if (location.href.indexOf('is-external=true') == -1) {
            parent.document.title="JayList";
        }
    }
    catch(err) {
    }
//-->
var methods = {"i0":10,"i1":10,"i2":10,"i3":10,"i4":10,"i5":10,"i6":10,"i7":10,"i8":10,"i9":10,"i10":10,"i11":10,"i12":10,"i13":10,"i14":10,"i15":10,"i16":10,"i17":10,"i18":10,"i19":10,"i20":10};
var tabs = {65535:["t0","All Methods"],2:["t2","Instance Methods"],8:["t4","Concrete Methods"]};
var altColor = "altColor";
var rowColor = "rowColor";
var tableTab = "tableTab";
var activeTableTab = "activeTableTab";
</script>
<noscript>
<div>JavaScript is disabled on your browser.</div>
</noscript>
<!-- ========= START OF TOP NAVBAR ======= -->
<div class="topNav"><a name="navbar.top">
<!--   -->
</a>
<div class="skipNav"><a href="#skip.navbar.top" title="Skip navigation links">Skip navigation links</a></div>
<a name="navbar.top.firstrow">
<!--   -->
</a>
<ul class="navList" title="Navigation">
<li><a href="package-summary.html">Package</a></li>
<li class="navBarCell1Rev">Class</li>
<li><a href="package-tree.html">Tree</a></li>
<li><a href="deprecated-list.html">Deprecated</a></li>
<li><a href="index-all.html">Index</a></li>
<li><a href="help-doc.html">Help</a></li>
</ul>
</div>
<div class="subNav">
<ul class="navList">
<li>Prev&nbsp;Class</li>
<li>Next&nbsp;Class</li>
</ul>
<ul class="navList">
<li><a href="index.html?JayList.html" target="_top">Frames</a></li>
<li><a href="JayList.html" target="_top">No&nbsp;Frames</a></li>
</ul>
<ul class="navList" id="allclasses_navbar_top">
<li><a href="allclasses-noframe.html">All&nbsp;Classes</a></li>
</ul>
<div>
<script type="text/javascript"><!--
  allClassesLink = document.getElementById("allclasses_navbar_top");
  if(window==top) {
    allClassesLink.style.display = "block";
  }
  else {
    allClassesLink.style.display = "none";
  }
  //-->
</script>
</div>
<div>
<ul class="subNavList">
<li>Summary:&nbsp;</li>
<li>Nested&nbsp;|&nbsp;</li>
<li>Field&nbsp;|&nbsp;</li>
<li><a href="#constructor.summary">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.summary">Method</a></li>
</ul>
<ul class="subNavList">
<li>Detail:&nbsp;</li>
<li>Field&nbsp;|&nbsp;</li>
<li><a href="#constructor.detail">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.detail">Method</a></li>
</ul>
</div>
<a name="skip.navbar.top">
<!--   -->
</a></div>
<!-- ========= END OF TOP NAVBAR ========= -->
<!-- ======== START OF CLASS DATA ======== -->
<div class="header">
<h2 title="Class JayList" class="title">Class JayList&lt;T&gt;</h2>
</div>
<div class="contentContainer">
<ul class="inheritance">
<li>java.lang.Object</li>
<li>
<ul class="inheritance">
<li>JayList&lt;T&gt;</li>
</ul>
</li>
</ul>
<div class="description">
<ul class="blockList">
<li class="blockList">
<dl>
<dt>All Implemented Interfaces:</dt>
<dd>MyDeque&lt;T&gt;</dd>
</dl>
<hr>
<br>
<pre>public class <span class="typeNameLabel">JayList&lt;T&gt;</span>
extends java.lang.Object
implements MyDeque&lt;T&gt;</pre>
</li>
</ul>
</div>
<div class="summary">
<ul class="blockList">
<li class="blockList">
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<ul class="blockList">
<li class="blockList"><a name="constructor.summary">
<!--   -->
</a>
<h3>Constructor Summary</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Constructor Summary table, listing constructors, and an explanation">
<caption><span>Constructors</span><span class="tabEnd">&nbsp;</span></caption>
<tr>
<th class="colOne" scope="col">Constructor and Description</th>
</tr>
<tr class="altColor">
<td class="colOne"><code><span class="memberNameLink"><a href="JayList.html#JayList--">JayList</a></span>()</code>&nbsp;</td>
</tr>
<tr class="rowColor">
<td class="colOne"><code><span class="memberNameLink"><a href="JayList.html#JayList-int-">JayList</a></span>(int&nbsp;capacity)</code>&nbsp;</td>
</tr>
<tr class="altColor">
<td class="colOne"><code><span class="memberNameLink"><a href="JayList.html#JayList-T:A-">JayList</a></span>(<a href="JayList.html" title="type parameter in JayList">T</a>[]&nbsp;input)</code>&nbsp;</td>
</tr>
</table>
</li>
</ul>
<!-- ========== METHOD SUMMARY =========== -->
<ul class="blockList">
<li class="blockList"><a name="method.summary">
<!--   -->
</a>
<h3>Method Summary</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Method Summary table, listing methods, and an explanation">
<caption><span id="t0" class="activeTableTab"><span>All Methods</span><span class="tabEnd">&nbsp;</span></span><span id="t2" class="tableTab"><span><a href="javascript:show(2);">Instance Methods</a></span><span class="tabEnd">&nbsp;</span></span><span id="t4" class="tableTab"><span><a href="javascript:show(8);">Concrete Methods</a></span><span class="tabEnd">&nbsp;</span></span></caption>
<tr>
<th class="colFirst" scope="col">Modifier and Type</th>
<th class="colLast" scope="col">Method and Description</th>
</tr>
<tr id="i0" class="altColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#addFirst-T-">addFirst</a></span>(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry)</code>&nbsp;</td>
</tr>
<tr id="i1" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#addFirst-T-constant.Keyword-">addFirst</a></span>(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry,
        constant.Keyword&nbsp;keyword)</code>
<div class="block">Bottleneck synchronized with this.</div>
</td>
</tr>
<tr id="i2" class="altColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#addLast-T-">addLast</a></span>(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry)</code>&nbsp;</td>
</tr>
<tr id="i3" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#addLast-T-constant.Keyword-">addLast</a></span>(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry,
       constant.Keyword&nbsp;keyword)</code>
<div class="block">Bottleneck synchronized with this.</div>
</td>
</tr>
<tr id="i4" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#clear--">clear</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i5" class="rowColor">
<td class="colFirst"><code>protected void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#finalize--">finalize</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i6" class="altColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#getFirst--">getFirst</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i7" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#getFirst-constant.Keyword-">getFirst</a></span>(constant.Keyword&nbsp;keyword)</code>
<div class="block">Bottleneck synchronized with this.</div>
</td>
</tr>
<tr id="i8" class="altColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#getLast--">getLast</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i9" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#getLast-constant.Keyword-">getLast</a></span>(constant.Keyword&nbsp;keyword)</code>
<div class="block">Bottleneck synchronized with this.</div>
</td>
</tr>
<tr id="i10" class="altColor">
<td class="colFirst"><code>boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#isEmpty--">isEmpty</a></span>()</code>
<div class="block">Client method needs to ensure synchronization with this.</div>
</td>
</tr>
<tr id="i11" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#removeFirst--">removeFirst</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i12" class="altColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#removeFirst-constant.Keyword-">removeFirst</a></span>(constant.Keyword&nbsp;keyword)</code>
<div class="block">Bottleneck synchronized with this.</div>
</td>
</tr>
<tr id="i13" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#removeLast--">removeLast</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i14" class="altColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#removeLast-constant.Keyword-">removeLast</a></span>(constant.Keyword&nbsp;keyword)</code>
<div class="block">Bottleneck synchronized with this.</div>
</td>
</tr>
<tr id="i15" class="rowColor">
<td class="colFirst"><code>boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#setArray-T:A-">setArray</a></span>(<a href="JayList.html" title="type parameter in JayList">T</a>[]&nbsp;input)</code>&nbsp;</td>
</tr>
<tr id="i16" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#showState-constant.Keyword-">showState</a></span>(constant.Keyword&nbsp;keyword)</code>&nbsp;</td>
</tr>
<tr id="i17" class="rowColor">
<td class="colFirst"><code>int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#size--">size</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i18" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#sort--">sort</a></span>()</code>
<div class="block">Client ensures object types are comparable.</div>
</td>
</tr>
<tr id="i19" class="rowColor">
<td class="colFirst"><code><a href="JayList.html" title="type parameter in JayList">T</a>[]</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#toArray--">toArray</a></span>()</code>&nbsp;</td>
</tr>
<tr id="i20" class="altColor">
<td class="colFirst"><code>java.lang.String</code></td>
<td class="colLast"><code><span class="memberNameLink"><a href="JayList.html#toString--">toString</a></span>()</code>&nbsp;</td>
</tr>
</table>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.java.lang.Object">
<!--   -->
</a>
<h3>Methods inherited from class&nbsp;java.lang.Object</h3>
<code>clone, equals, getClass, hashCode, notify, notifyAll, wait, wait, wait</code></li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
<div class="details">
<ul class="blockList">
<li class="blockList">
<!-- ========= CONSTRUCTOR DETAIL ======== -->
<ul class="blockList">
<li class="blockList"><a name="constructor.detail">
<!--   -->
</a>
<h3>Constructor Detail</h3>
<a name="JayList--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>JayList</h4>
<pre>public&nbsp;JayList()</pre>
<dl>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="JayList-int-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>JayList</h4>
<pre>public&nbsp;JayList(int&nbsp;capacity)</pre>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>capacity</code> - The desired capacity of the underlying data structure.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalArgumentException</code> - when the size of the accepted value exceeds a predetermined maximum capacity.</dd>
<dd><code>java.lang.IllegalArgumentException</code> - when the size of the accepted value is less than one.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="JayList-java.lang.Object:A-">
<!--   -->
</a><a name="JayList-T:A-">
<!--   -->
</a>
<ul class="blockListLast">
<li class="blockList">
<h4>JayList</h4>
<pre>public&nbsp;JayList(<a href="JayList.html" title="type parameter in JayList">T</a>[]&nbsp;input)</pre>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>input</code> - An array used as a template.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
</li>
</ul>
<!-- ============ METHOD DETAIL ========== -->
<ul class="blockList">
<li class="blockList"><a name="method.detail">
<!--   -->
</a>
<h3>Method Detail</h3>
<a name="addFirst-java.lang.Object-">
<!--   -->
</a><a name="addFirst-T-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>addFirst</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;addFirst(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry)</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code>addFirst</code>&nbsp;in interface&nbsp;<code>MyDeque&lt;<a href="JayList.html" title="type parameter in JayList">T</a>&gt;</code></dd>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>entry</code> - An entry to be added.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalStateException</code> - when this has not been properly initialized or when entry cannot be added due to a predetermined maximum capacity.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="addFirst-java.lang.Object-constant.Keyword-">
<!--   -->
</a><a name="addFirst-T-constant.Keyword-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>addFirst</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;addFirst(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry,
                  constant.Keyword&nbsp;keyword)</pre>
<div class="block">Bottleneck synchronized with this.</div>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>entry</code> - An entry to be added.</dd>
<dd><code>keyword</code> - Used for development.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalStateException</code> - when this has not been properly initialized or when entry cannot be added due to a predetermined maximum capacity.</dd>
<dd><code>java.lang.IllegalArgumentException</code> - when entry is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="addLast-java.lang.Object-">
<!--   -->
</a><a name="addLast-T-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>addLast</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;addLast(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry)</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code>addLast</code>&nbsp;in interface&nbsp;<code>MyDeque&lt;<a href="JayList.html" title="type parameter in JayList">T</a>&gt;</code></dd>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>entry</code> - An entry to be added.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalStateException</code> - when this has not been properly initialized or when entry cannot be added due to a predetermined maximum capacity.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="addLast-java.lang.Object-constant.Keyword-">
<!--   -->
</a><a name="addLast-T-constant.Keyword-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>addLast</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;addLast(<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;entry,
                 constant.Keyword&nbsp;keyword)</pre>
<div class="block">Bottleneck synchronized with this.</div>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>entry</code> - An entry to be added.</dd>
<dd><code>keyword</code> - Used for development.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalStateException</code> - when this has not been properly initialized or when entry cannot be added due to a predetermined maximum capacity.</dd>
<dd><code>java.lang.IllegalArgumentException</code> - when entry is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="removeLast--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>removeLast</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;removeLast()</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code>removeLast</code>&nbsp;in interface&nbsp;<code>MyDeque&lt;<a href="JayList.html" title="type parameter in JayList">T</a>&gt;</code></dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that was removed.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalArgumentException</code> - if data structure is empty.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="removeLast-constant.Keyword-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>removeLast</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;removeLast(constant.Keyword&nbsp;keyword)</pre>
<div class="block">Bottleneck synchronized with this.</div>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>keyword</code> - Used for development.</dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that was removed.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.util.NoSuchElementException</code> - if data structure is empty.</dd>
<dd><code>java.lang.NullPointerException</code> - if removed value is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="removeFirst--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>removeFirst</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;removeFirst()</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code>removeFirst</code>&nbsp;in interface&nbsp;<code>MyDeque&lt;<a href="JayList.html" title="type parameter in JayList">T</a>&gt;</code></dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that was popped.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalArgumentException</code> - if data structure is empty.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="removeFirst-constant.Keyword-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>removeFirst</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;removeFirst(constant.Keyword&nbsp;keyword)</pre>
<div class="block">Bottleneck synchronized with this.</div>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>keyword</code> - Used for development.</dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that was popped.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.util.NoSuchElementException</code> - if data structure is empty.</dd>
<dd><code>java.lang.NullPointerException</code> - if popped value is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="getLast--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>getLast</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;getLast()</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code>getLast</code>&nbsp;in interface&nbsp;<code>MyDeque&lt;<a href="JayList.html" title="type parameter in JayList">T</a>&gt;</code></dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that is next in queue.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.util.NoSuchElementException</code> - if data structure is empty.</dd>
<dd><code>java.lang.NullPointerException</code> - if next value is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="getLast-constant.Keyword-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>getLast</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;getLast(constant.Keyword&nbsp;keyword)</pre>
<div class="block">Bottleneck synchronized with this.</div>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>keyword</code> - Used for development.</dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that is next in queue.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.util.NoSuchElementException</code> - if data structure is empty.</dd>
<dd><code>java.lang.NullPointerException</code> - if next value is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="getFirst--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>getFirst</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;getFirst()</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Specified by:</span></dt>
<dd><code>getFirst</code>&nbsp;in interface&nbsp;<code>MyDeque&lt;<a href="JayList.html" title="type parameter in JayList">T</a>&gt;</code></dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that is next in stack.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.util.NoSuchElementException</code> - if data structure is empty.</dd>
<dd><code>java.lang.NullPointerException</code> - if next value is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="getFirst-constant.Keyword-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>getFirst</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>&nbsp;getFirst(constant.Keyword&nbsp;keyword)</pre>
<div class="block">Bottleneck synchronized with this.</div>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>keyword</code> - Used for development.</dd>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>the element that is next in stack.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.util.NoSuchElementException</code> - if data structure is empty.</dd>
<dd><code>java.lang.NullPointerException</code> - if next value is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="clear--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>clear</h4>
<pre>public&nbsp;void&nbsp;clear()</pre>
<dl>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="setArray-java.lang.Object:A-">
<!--   -->
</a><a name="setArray-T:A-">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>setArray</h4>
<pre>public&nbsp;boolean&nbsp;setArray(<a href="JayList.html" title="type parameter in JayList">T</a>[]&nbsp;input)</pre>
</li>
</ul>
<a name="toArray--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>toArray</h4>
<pre>public&nbsp;<a href="JayList.html" title="type parameter in JayList">T</a>[]&nbsp;toArray()</pre>
<dl>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>A copy of this array.</dd>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.IllegalStateException</code> - when this has not been properly initialized.</dd>
<dd><code>java.lang.NullPointerException</code> - when jayList is null.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="sort--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>sort</h4>
<pre>public&nbsp;void&nbsp;sort()</pre>
<div class="block">Client ensures object types are comparable.</div>
<dl>
<dt><span class="throwsLabel">Throws:</span></dt>
<dd><code>java.lang.UnsupportedOperationException</code> - if object types are not comparable.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="size--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>size</h4>
<pre>public&nbsp;int&nbsp;size()</pre>
<dl>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>size The number of elements contained within this data structure.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="isEmpty--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>isEmpty</h4>
<pre>public&nbsp;boolean&nbsp;isEmpty()</pre>
<div class="block">Client method needs to ensure synchronization with this.</div>
<dl>
<dt><span class="returnLabel">Returns:</span></dt>
<dd>true if no elements exist in this data structure.</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="finalize--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>finalize</h4>
<pre>protected&nbsp;void&nbsp;finalize()</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Overrides:</span></dt>
<dd><code>finalize</code>&nbsp;in class&nbsp;<code>java.lang.Object</code></dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="toString--">
<!--   -->
</a>
<ul class="blockList">
<li class="blockList">
<h4>toString</h4>
<pre>public&nbsp;java.lang.String&nbsp;toString()</pre>
<dl>
<dt><span class="overrideSpecifyLabel">Overrides:</span></dt>
<dd><code>toString</code>&nbsp;in class&nbsp;<code>java.lang.Object</code></dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
<a name="showState-constant.Keyword-">
<!--   -->
</a>
<ul class="blockListLast">
<li class="blockList">
<h4>showState</h4>
<pre>public&nbsp;void&nbsp;showState(constant.Keyword&nbsp;keyword)</pre>
<dl>
<dt><span class="paramLabel">Parameters:</span></dt>
<dd><code>keyword</code> - Keyword that the method body portion execution is dependent on</dd>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.0.0</dd>
</dl>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
</div>
<!-- ========= END OF CLASS DATA ========= -->
<!-- ======= START OF BOTTOM NAVBAR ====== -->
<div class="bottomNav"><a name="navbar.bottom">
<!--   -->
</a>
<div class="skipNav"><a href="#skip.navbar.bottom" title="Skip navigation links">Skip navigation links</a></div>
<a name="navbar.bottom.firstrow">
<!--   -->
</a>
<ul class="navList" title="Navigation">
<li><a href="package-summary.html">Package</a></li>
<li class="navBarCell1Rev">Class</li>
<li><a href="package-tree.html">Tree</a></li>
<li><a href="deprecated-list.html">Deprecated</a></li>
<li><a href="index-all.html">Index</a></li>
<li><a href="help-doc.html">Help</a></li>
</ul>
</div>
<div class="subNav">
<ul class="navList">
<li>Prev&nbsp;Class</li>
<li>Next&nbsp;Class</li>
</ul>
<ul class="navList">
<li><a href="index.html?JayList.html" target="_top">Frames</a></li>
<li><a href="JayList.html" target="_top">No&nbsp;Frames</a></li>
</ul>
<ul class="navList" id="allclasses_navbar_bottom">
<li><a href="allclasses-noframe.html">All&nbsp;Classes</a></li>
</ul>
<div>
<script type="text/javascript"><!--
  allClassesLink = document.getElementById("allclasses_navbar_bottom");
  if(window==top) {
    allClassesLink.style.display = "block";
  }
  else {
    allClassesLink.style.display = "none";
  }
  //-->
</script>
</div>
<div>
<ul class="subNavList">
<li>Summary:&nbsp;</li>
<li>Nested&nbsp;|&nbsp;</li>
<li>Field&nbsp;|&nbsp;</li>
<li><a href="#constructor.summary">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.summary">Method</a></li>
</ul>
<ul class="subNavList">
<li>Detail:&nbsp;</li>
<li>Field&nbsp;|&nbsp;</li>
<li><a href="#constructor.detail">Constr</a>&nbsp;|&nbsp;</li>
<li><a href="#method.detail">Method</a></li>
</ul>
</div>
<a name="skip.navbar.bottom">
<!--   -->
</a></div>
<!-- ======== END OF BOTTOM NAVBAR ======= -->
</body>
</html>
Status API Training Shop Blog About
© 2016 GitHub, Inc. Terms Privacy Security Contact Help