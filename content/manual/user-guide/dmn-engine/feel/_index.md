---

title: 'FEEL Engine'
weight: 30

menu:
  main:
    name: "FEEL Engine"
    identifier: "user-guide-dmn-engine-feel"
    parent: "user-guide-dmn-engine"
    pre: "Friendly Enough Expression Language Engine"

---

FEEL is part of the DMN specification and stands for "Friendly Enough Expression Language". You can
use it to evaluate expressions in a decision table.

You can use the Expression Language in the following DMN Notation Elements:

* [Input Expressions]
* [Input Entries]
* [Output Entries]
* [Literal Expressions]

This documentation covers everything integration-specific about the
[FEEL Scala Engine][] (opens external link) in the Operaton DMN Engine.

{{< note title="Heads Up!" class="info" >}}
If you come from a Operatonversion <= 7.12.x and already use FEEL,
please read the documentation about the
<a href="{{< ref "/manual/user-guide/dmn-engine/feel/legacy-behavior.md" >}}">FEEL Engine Legacy Behavior</a>.
{{< /note >}}

[FEEL Scala Engine]: https://github.com/camunda/feel-scala
[input entries]: {{< ref "/manual/reference/dmn/decision-table/rule.md#input-entry-condition" >}}
[Input Expressions]: {{< ref "/manual/reference/dmn/decision-table/input.md#input-expression" >}}
[Output Entries]: {{< ref "/manual/reference/dmn/decision-table/rule.md#output-entry-conclusion" >}}
[Literal Expressions]: {{< ref "/manual/reference/dmn/decision-literal-expression/_index.md" >}}
