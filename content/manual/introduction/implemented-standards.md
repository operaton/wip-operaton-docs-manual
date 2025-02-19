---

title: 'Implemented Standards'
weight: 20

menu:
  main:
    identifier: "user-guide-introduction-standards"
    parent: "user-guide-introduction"

---

Operaton implements three different standards in the Business Process Management scope: BPMN 2.0, CMMN 1.1 and DMN 1.3.
These three standards are defined by the [Object Management Group][OMG] with active collaboration of Operaton.

Operaton provides open source implementations of execution and [modeling tools][modelers].

# BPMN

Business Process Model and Notation (BPMN) is a standard for Workflow and Process Automation.
Operaton supports the 2.0 version of BPMN.

* Getting started implementing BPMN Processes: [Quick Start (Java / JS)]
* Getting to Know BPMN as a Modeling Language: [BPMN Modeling Tutorial]
* Modeling BPMN: [BPMN Modeling Reference]
* Tool for modeling BPMN: [BPMN Modeler][modelers]
* Implementing BPMN Processes: [BPMN Implementation Reference]
* Executing BPMN: [Process Engine]

# CMMN

Case Management Model and Notation (CMMN) is a standard for Case Management.
Operaton supports the 1.1 version of CMMN.

* Implementing CMMN Cases: [CMMN Implementation Reference]
* Executing CMMN: [Process Engine]

# DMN

Decision Model and Notation (DMN) is a standard for Business Decision Management.
Operaton supports the 1.1 version of DMN.

* Getting started implementing DMN decision tables: [DMN Getting Started]
* Getting to Know DMN: [DMN Modeling Tutorial]
* Tool for editing DMN: [DMN Editor][modelers]
* Implementing DMN Decisions: [DMN Implementation Reference]
* Executing DMN: [DMN Engine]


[OMG]: http://www.omg.org/
[modelers]: {{< ref "/manual/modeler/_index.md" >}}
[BPMN Modeling Tutorial]: https://camunda.org/bpmn/tutorial/
[BPMN Modeling Reference]: https://camunda.org/bpmn/reference/
[Quick Start (Java / JS)]: /get-started/quick-start/
[BPMN Implementation Reference]: {{< ref "/manual/reference/bpmn20/_index.md" >}}
[CMMN Implementation Reference]: {{< ref "/manual/reference/cmmn11/_index.md" >}}
[DMN Getting Started]: /get-started/dmn11/
[DMN Implementation Reference]: {{< ref "/manual/reference/dmn/_index.md" >}}
[DMN Modeling Tutorial]: https://camunda.org/dmn/tutorial/
[Process Engine]: {{< ref "/manual/user-guide/process-engine/_index.md" >}}
[DMN Engine]: {{< ref "/manual/user-guide/dmn-engine/_index.md" >}}
