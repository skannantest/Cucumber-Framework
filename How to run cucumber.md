Create feature file under feature package ,
Create test steps class under steps package ,
Create runner class under testRunner package.
If we want to run the test steps, we have to run the runner class under the testRunner package. 

If it is inconvenient to add more separate methods, make dryRun as true and then if we run only one test steps in the scenario. Then it will gives the methods on the console so we can copy that and use it. After create methods for all the steps, we have change dryRun as false
