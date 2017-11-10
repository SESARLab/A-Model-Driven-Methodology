Oozie files configuration are in this folder

* sequential_workflow.xml represents the workflow exposed in Figure 10(a)
* parallel_workflow.xml represents the workflow exposed in Figure 10(b)

The composition in Figure 10(c) is finally given as input to our compiler that generates the Oozie workflow in Figure 8. The workflow is then stored in the appropriate path in our platform, instantiated according to the information available in files job.xml and properties.xml associated with each of the component services, and executed by the Oozie engine.

