# Azure Case Study -1 (Storage) 

## Problem 
You work for XYZ Global Corporation, which is a Multinational company and has headquarters
all around the globe. The data for this company is generated every day and is managed by the
technicians. One of the technicians separates this data into two parts – Critical Data and NonCritical Data. 
The Critical data is the data on which they are willing to shell money out for but
not so much on the Non-critical Data. 
Now, the Critical data has to reach the clients globally,
but the non-critical data is only being used amongst local data centers.


They have deployed
their web app on the internet that helps them upload the data to their cloud storage. Theusers
are complaining that the website contentis not loading fast enough. You realize that this might
be because your website faces global traffic while the static assets like images are being served
via a single server. Also the employees are complaining that it is difficult for them to access
common files and tools, as they need to get it from each other. 


## Deep dive into problem  statement
   
   * We need to upload all static content of XYZ Global Corporation web site to azure storage.
   * Create Storage accounts for Critical and Non-Critical Data – Enable global and local
replication
   * Use the Shared Access keys to Link the web app with the Storage account where the
data has to be stored
   * Create a CDN Endpoint and configure it to serve the static files you uploaded. 
   * Create an Azure File Share and Upload all tools and files for your colleagues to
share.Connect a Linux and Windows VM Box to the File Share. 


## Problem Solution   


  

  
  



