#### A portion of this HW assignment was completed for extra credit per instructions from the Professor, found here: https://github.com/fedhere/PUI2016_fb55/tree/master/HW12_fb55.  This included developing the SQL query to download the data in the desired manner (counts by zipcode), which is as follows:

#### SELECT COUNT (cartodb_id), zipcodes 
#### FROM nycasthmasdismissals
#### GROUP BY zipcodes

#### This query summed the record counts by zipcode.  A NYC zipcodes shapfile was then downloaded, and these two files were merged via GeoPandas.  


#### The remainder of the assignment was not completed, as this was not required for the extra credit.
