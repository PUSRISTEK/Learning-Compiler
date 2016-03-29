<h4>Setup Ant & Grunt</h4>
<b>setup java -cp ant.jar org.ant.v4.Tool</b><br>
<b>java -cp .;ant.jar org.ant.v4.gui.TestRig<b><br>

<h4>Generate Ant</h4>
<b>ant Hello.g4</b><br>
<b>javac lexer.java<br>

<h4>Grunt TestRig</h4>
<p>TestRig is a flexible testing tool in the runtime library. It can display lots of information about how a recognizer matches input from a file or standard input. TestRig uses Java reflection to invoke compiled recognizers.</p>

<h4>Grunt TestRig Tokens</h4>
<p>The test rig takes a grammar name, a starting rule name kind of like a main() method, and various options that dictate the output we want.</p>
<b>grunt Hello r -tokens</b><br>
<b>hello world</b><br>
<b>CTRL+Z</b><br>

<h4></h4>
<p>Print the Parse Tree with LISP style text form (root childern)</p>
<b>Grunt Hello r -tree</b><br>
<b>hello World</b><br>
<b>r hello world</b><br>

<b></b><br>
