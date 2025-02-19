---

title: 'Terminate Events'
weight: 90

menu:
  main:
    identifier: "bpmn-ref-events-terminate-event"
    parent: "bpmn-ref-events"
    pre: "End a scope."

---

A terminate event ends the complete scope it is raised in and all contained inner scopes.

It is useful if you have a parallel token flow in a process and you want to consume all tokens available in the same scope immediately.

A terminate event on process instance level terminates the complete instance. On subprocess level the current scope and all contained processes instances will be terminated.

<div data-bpmn-diagram="../bpmn/event-terminate"></div>


# Terminate Event Definition

A terminate event is modeled as an end event with an additional definition element to mark the termination:

```xml
<process id="someProcess">
  <!-- ... -->
    <endEvent id="EndEvent_2" name="Tweet rejected">
      <terminateEventDefinition id="TerminateEventDefinition_1"/>
    <endEvent>
  <!-- ... -->
</process>
```


# Operaton Extensions

<table class="table table-striped">
  <tr>
    <th>Attributes</th>
    <td>
      <a href="{{< ref "/manual/reference/bpmn20/custom-extensions/extension-attributes.md#asyncbefore" >}}">camunda:asyncBefore</a>,
      <a href="{{< ref "/manual/reference/bpmn20/custom-extensions/extension-attributes.md#asyncafter" >}}">camunda:asyncAfter</a>,
      <a href="{{< ref "/manual/reference/bpmn20/custom-extensions/extension-attributes.md#exclusive" >}}">camunda:exclusive</a>,
      <a href="{{< ref "/manual/reference/bpmn20/custom-extensions/extension-attributes.md#jobpriority" >}}">camunda:jobPriority</a>
    </td>
  </tr>
  <tr>
    <th>Extension Elements</th>
    <td>
      <a href="{{< ref "/manual/reference/bpmn20/custom-extensions/extension-elements.md#inputoutput" >}}">
        camunda:inputOutput</a>
    </td>
  </tr>
  <tr>
    <th>Constraints</th>
    <td>&ndash;</td>
  </tr>
</table>

## Additional Resources

* [Terminate Events](http://camunda.org/bpmn/reference.html#events-termination) in the [BPMN 2.0 Modeling Reference](http://camunda.org/bpmn/reference.html)
