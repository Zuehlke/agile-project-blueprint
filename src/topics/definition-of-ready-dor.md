# Definition Of Ready \(DoR\)

The DoR defines the state in which a story has to be before the story can be implemented during an iteration. In contrast to the DoD the DoR is an optional artifact. It can help the team to get a common understanding of the content of the story. 

## The DoR as an excuse

The [Agile Manifesto](http://agilemanifesto.org/) states:

> Customer collaboration over contract negotiation

Often a DoR is used to decline a story. This is not the idea of the DoR. The criterias of the DoR should not be too strict, implementation details should be discussed with the PO or the customer instead of just pushing it back to the backlog.

## Example

### A Story is created in JIRA

The JIRA ID is used to reference the story, where ever necessary.

### It must be valuable

The story got approved by the Product Owner during the planning or in rare cases during the sprint.

### The Story has a Summary

The stories must have a summary matching the following pattern:  
As _**Persona**_ I want _**Feature**_, so I can _**Value**_.

_Example:  
As a manager I want to create a report, so I can figure which department has to improve its performance._

### Constraints are defined

Constraints can be limitations for input fields, a set of roles that can use the feature, etc.

### Acceptance Criteria is defined

All criteria that must be matched for the story to be completed must be defined.  
At least one acceptance test scenario \(flow\) is defined step by step \(happy case\).

_Example:  
The user opens the machines overview and selects the delete action for a machine in the list.  
A toast message confirms that the action is triggered.  
The user opens the machines overview again and the machine is in the state deleting._

### The Team has estimated the Story

The story was estimated by the Team.

