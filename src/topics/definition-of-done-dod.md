# Definition Of Done

The definition of done should define measurable \(!\) criteria that has to be fulfilled before you can call an issue 'done'. It is a good place  to make sure non functional requirements are met, too.

The DoD belongs to the development team, but it is deemed a good practice to involve the Product Owner or who ever is in charge in the creation process to make sure his needs for the product are addressed in a sufficent way.

Another recommendation is to keep the list small, so people can remember it more easy.

## Example

### Unit Test\(s\) automated

All non-trivial logic is covered by unit tests.  
_**Add way to measure here \(Code Coverage?!\)**_

### E2E Test\(s\) automated

E2E tests were created or adapted as necessary. At least one happy case scenario should be covering the changed behavior \(flow from JIRA story might be a good one\). The test is visible in Scenarioo.

### Tested manually

The story was tested locally by the developer\(s\) in Chrome, Microsoft Edge and IE 11. These tests included testing of:

* all defined acceptance criteria
* all defined constraints
* all other aspects deemed necessary by the developer\(s\) to ensure the story is implemented correctly and free of bugs

### Regression Tests passed

All existing tests are still passing and none were disabled.

### No ToDos left

There are no ToDos for the story \(// ToDo: \#StoryID\) left in the Code.

### Code was reviewed and merged

* Code was reviewed and merged according to our [branching guidelines](commit-and-branching-guidelines.md).
* Findings were discussed and addressed appropriately
* Build on develop branch is green

### All Tasks closed

All subtasks of the JIRA story are closed.

### Tested by the Tester

The story was tested, approved and closed by the teams embedded Tester.

### Feature was demonstrated

The feature was demonstrated to the Product Owner and the team \(Review\) in IE 11 and accepted by the PO.

### Documentation is up-to-date

Any documentation that relates to this story is up-to-date. This includes all kind of documentation, e.g. architecture document, release documentation, and so on.

### Deployed to development environment

The feature is deployed to a development environment.

---

![](/assets/DefinitionOfALmostDone.jpg)

