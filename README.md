# Azure_VM_Scale-Sets

1. Go to `Azure Portal`


2. Search and open Virtual machine scale sets


3. Click on Create


4. Create a new Resource group 

    Give name to your Virtual machine scale set name
    
    Select the closest Region
    
    Select all 3 Availability zones 
    
    Select Orchestration mode - Uniform 
    
    Select Size - Standard_B1s
    
    Click on Next and go to Networking
    
    Load balancing options - None 
    
    Click on Next and go to Scaling 
    
    Initial instance count - 2
    
    Scaling policy - Manual
    
    Now click on Review+Create
    
    Now click on Download private key and create resource

![image](https://github.com/Pavan-1997/Azure_VM_Scale-Sets/assets/32020205/df2538ce-4d73-490e-8cd1-153a03d09060)


5. Now go to Azure DevOps portal 

    Select any project
    
    Go to Project settings
    
    In Pipelines -> Select Agent pools
    
    Click on Add pool -> Select pool type - Azure virtual machine scale set -> Give name to the agent pool -> Max - 2,Min - 1 -> Select Grant access permission to all pipelines -> Click on Create
