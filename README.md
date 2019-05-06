# IBM Watson OpenScale Lab: Validating a German Credit Risk Model for Fairness and Accuracy

Version 2019-03-17 by Jukka Ruponen/IBM

**The purpose of this tutorial is to demonstrate how to configure and use OpenScale programmatically by using Python SDK.**  

This tutorial uses a slightly modified version of the Notebook, but the steps are the same as described in here:  
Documentation: https://cloud.ibm.com/docs/services/ai-openscale?topic=ai-openscale-crt-ov  
Source: https://github.com/emartensibm/german-credit  

The tutorial uses a Jupyter notebook that should be run in a Watson Studio project, using a "**Python 3.5 with Spark**" runtime environment. It requires service credentials for the following IBM Cloud services:

    Cloud Object Storage (to store your Watson Studio project)
    Watson OpenScale
    Watson Machine Learning
    (Optional) Databases for PostgreSQL or Db2 Warehouse

The Jupyter notebook will train, create and deploy a German Credit Risk model, configure Watson OpenScale to monitor that deployment, and provide seven days' worth of historical records and measurements for viewing in the Watson OpenScale Insights dashboard. You can also optionally configure the model for continuous learning with Watson Studio and Spark.

**Instructions in short:**  
Deploy the included Python Notebook to your Watson Studio project and open it.  
All instructions are provided within the notebook.  

Should you need more detailed step-by-step instructions, see the documentation [here](https://cloud.ibm.com/docs/services/ai-openscale?topic=ai-openscale-crt-ov).
