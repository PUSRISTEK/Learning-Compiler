<h2>Initial Setup</h2>

<h4>Setup Ant & Grunt</h4>
<b>setup java -cp ant.jar org.ant.v4.Tool</b><br>
<b>java -cp .;ant.jar org.ant.v4.gui.TestRig</b><br>

<h4>Generate Ant</h4>
<b>ant Hello.g4</b><br>
<b>javac lexer.java</b><br>

<h4>Grunt TestRig</h4>
<p>TestRig is a flexible testing tool in the runtime library. It can display lots of information about how a recognizer matches input from a file or standard input. TestRig uses Java reflection to invoke compiled recognizers.</p>

<h4>Grunt TestRig Tokens</h4>
<p>The test rig takes a grammar name, a starting rule name kind of like a main() method, and various options that dictate the output we want.</p>
<b>grunt Hello r -tokens</b><br>
<b>hello world</b><br>
<b>CTRL+Z</b><br>

<h4>Grunt TestRig Tree</h4>
<p>Print the Parse Tree with LISP style text form (root childern)</p>
<b>Grunt Hello r -tree</b><br>
<b>hello World</b><br>
<b>r hello world</b><br>

<h4>Grunt TestRig </h4>
<p>The easiest way to see how a grammar recognizes the input, though, is by looking at the parse tree visually. Running TestRig with the -gui option.</p>
<b>Grunt Hello r -gui</b><br>
<b>Hello World</b><br>
<b>CTRL+Z</b><br>

<h2>The Big Picture</h2>
<p>To implement a language, we have to build an application that reads sentences and reacts appropriately to the phrases and input symbols it discovers. (A language is a set of valid sentences, a sentence is made up of phrases, and
a phrase is made up of subphrases and vocabulary symbols.)</p>

<p>The parsing method using <b>Recursive-descent parser</b> (collection of recursive method, one per rule). Descent refer to the fact that parsing begins at the root of a parser tree and proceeds towards the leaves. <b>Recursive-descent parser</b> is a one kind of <b>Top Down Parser</b>.</p>

<p><b>Lookahead Token</b> is a token that the parser sniff before matching and consuming it. Decision will be easy when each path start with unique name.</p>

<ol>ANT Class: 
<li>Charstream</li>
<li>Lexer</li>
<li>Token</li>
<li>Parser</li>
<li>Parser Tree</li>
</ol>

<b></b><br>
