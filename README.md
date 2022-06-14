# Apester-Home-Assignment


Hi,

during the development I had issues with the virtual box.

my two opinions for combining the "Rubicon" data from the csv and json were :

1. by join
2. by union and performing window funstion in order to trace the accurate row 
   (partition by date,advertiser order by sort - when sort is 1 for the rows from the csv and 2 from the json)

I got an error related to the java version when I tried to implement the solutions above.

so I had to solved it on another way, which are more complicated and I believe little less effective as well.

unfortunately just before the csv creation, the virtual box was entirely dead, so it is missing here.

in order to create it (and after pyspark and pandas are installed),the following steps are needed in order to create the output csv file :

1. place the source csv and json files on home directory.
2. change the directoy of the csv output file.
3. run the code.


thanks,
Gal



