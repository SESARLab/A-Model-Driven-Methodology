Oozie workflows

* sequential_workflow.xml represents the Oozie workflow of the composition presented in Figure 10(a)
* parallel_workflow.xml represents the Oozie workflow of the composition presented in Figure 10(b)

The composition in Figure 10(b) is given as input to our compiler that generates the Oozie workflow used in our experiments. The workflow is then stored in the appropriate path in our platform, instantiated according to the information available in files job.xml and properties.xml associated with each of the component services, and executed by the Oozie engine.
