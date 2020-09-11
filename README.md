# Business Intelligence Data Challenge

Our challenge is set in the context of e-commerce or online markting, have a look at our
website under 'Attribution'. Usually when you sell something in the internet, the user/customer 
comes multiple times (e.g. visits) to the site, often also via different channels (e.g. Email, Facebook, Google, etc.),
before he or she buys something (a conversion or transaction).

## Datasets

**table_A_conversions.csv**:
* example list of conversions/ sales/ transaction
* Conv_ID - transaction ID
* Conv_Date - transaction date
* Revenue - value of transaction
* User_ID - an ID of a customer

**table_B_attribution.csv**:
* list of attribution results for conversions
* Conv_ID - transaction ID (link to table A)
* Channel - marketing channel
* IHC_Conv - attributed conversion fraction by the IHC model

Note, that the attributed conversion fraction (IHC_Conv), i.e. it is the fraction of the 
given conversion which is attributed to a certain channel, sums up to 1.0 for every conversion.


## Task

Obviously, we want you to analyze the data and show us what you can learn from it.

But we also want you to visualize your findings try to get "useful" insights out of it and present them in a nice
PDF.

### some hints, (non-exhaustive) list of points you might consider in your analysis:

* General overview over the time period (interesting KPIs are: revenue, number customers, fraction of return customer)
* Performance and impact of different channels and how it changes over time
* Most influential channels for every user
* Cohort analysis
* Customer journey statistics
* Do we see a development within customers?
* Some customer segmentation


### Deliverable & Remarks:
* Well commented and easy to follow code for analysis
* If possible some insightful (!) charts with explanations (Use Qlik or Datastudio)
* PDF (max 3-4 pages!) with brief explanation of steps taken and the summary of results

### Please use only Qlik or Datastudio
* Including some visualization with this tools is a big plus.


### Good luck and we are very excited to see your solutions! 


### Note: We don't expect you to build THE solution or report here.
Our goal here is:
* See how you approach such a problem
* Get an idea of your programming skills and tools you can use
* Test your rational thinking in such a problem case
* See how you can summarize and present results
