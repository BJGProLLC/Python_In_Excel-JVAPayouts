# Python_In_Excel-JVAPayouts
Python in Excel for Joint Venture Accounting Payout Statement processes.  

In Joint Venture Accounting, payout statements are a common reporting requirement when joint venture partners decide to go non-consent. 
The payout statement is designed to keep track of gross net revenues less uplifted expenditures during a given period. Once gross net revenues exceed uplifted expenditures, the joint venture partner is deemed to have “paid out” and now has the right to have it’s working interest re-instated back into the joint venture deck.

Whilst the payout statement is a simple mathematical model, the complications with payout statements in the JV world is volume, especially for onshore oil wells in the North American region. 
It’s not uncommon where the operator is required to calculate payout statements for at least 50 onshore oil wells with multiple non-consent partners for each oil well.

With this type of repeatable process and managing volume, payout statements are ideal candidate to automate using Pythin In Excel.

This payout workflow demonstrates the basic inputs requires, value mappings, calculations and table joins to create a single payout statement that provides a payout balance for each period. 
A basic workflow design like this can easily be used to automate repeatable processes and save the joint venture accounting analyst time in preparing these payout statements and helps to re-focus time to other value add activities (i.e. analysis vs manual data preparation/wrangling).

Happy to get feedback from the community on suggestions/improvements.

Happy Analyzing!

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of logic sequences in this simply payout model. You can use the branch pop up menu in github to switch to a specific branch and take a look at the python code at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the logic sequences in the payout model. The naming convention is `Dataset#_Logic#`. As an example, the branch named `02_Dataframes` corresponds to the second second sequence in the logic sequence, e.g., the second sequnece in Python would be to load the dataset(s).  


### Python Developer
Bernardo Garcia Jr
