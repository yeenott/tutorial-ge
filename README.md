# Data Validation Tutorial with Great_expectations

### 1. quick_start.ipynb, using standalone Great_expectations functions to perform data validation. 

### 2. quick_start_pdprofiler.ipynb is an example of data validation workflow using Great_expectations modules such as 
    * Creating project directory using *init*
    * Building Datasource and Datacontext using *datasource new* 
    * Profiler using Pandas-profiler package
    * Constructure Suite using *suite new* to combine multiple expectations 
    * Datadoc reporting results
    * Setting up a Checkpoit combining workflow from running a validation, updating DataDoc, to sending a result notification using *checkpoint new*