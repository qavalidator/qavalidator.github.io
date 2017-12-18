---
layout: page
title: Getting Started
permalink: /getstarted/
---

<h1 class="page-title">{{ page.title | escape }}</h1>

<div class="section">
    <h5>Maven</h5>

Include the Maven Plugin in your pom.xml.
See the <a href="/static/doc/qav-doc.html#usage-maven">documentation</a> for details.

Call the QAvalidator run with this command:

<pre><code>mvn qav:qav</code></pre>
</div>
<div class="divider"></div>

<div class="section">
    <h5>Gradle</h5> 

Apply the Gradle plugin to your build.gradle. 
See the <a href="/static/doc/qav-doc.html#usage-gradle">documentation</a> for details.

Call the QAvalidator run with this command:

<pre><code>gradlew qavalidator</code></pre>

</div>
<div class="divider"></div>

<div class="section">
    <h5>Command Line</h5> 
</div>

There is also a command line tool. It needs the analysis file (mandatory), the output directory (optional), and the input directories (also optional) - if the optional arguments are not given on the command line, they must be defined in the analysis file.

<pre><code>$ java -jar qav-app-VERSION.jar --analysis=&lt;analysis-file&gt; [--outputDir=&lt;output-dir&gt;] [input-dirs ...]</code></pre>

See the <a href="/static/doc/qav-doc.html#usage-cli">documentation</a> for details.
