# Labeled statements

* Go 버전: 1.9
* 원문: [Labeled statements](https://golang.org/ref/spec#Labeled_statements)
* 번역자: Myoungho Choi (@afraxas)

A labeled statement may be the target of a goto, break or continue statement.

<pre>
<a id="LabeledStmt">LabeledStmt</a> = <a href="#Label">Label</a> ":" <a href="/Statements/#Statement">Statement</a> .
<a id="Label">Label</a>       = <a href="/Lexical%20elements/identifiers.html#identifier">identifier</a> .
</pre>

```
Error: log.Panic("error encountered")
```