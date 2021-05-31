# Columnar-Data-Format-files
Row format :
CSV : Low overhead
      No Flexibility
JSON : High Overhead
       High folexibility
       
 In Row format, we need to read the whole file to perform all types of aggrgations, count.
 Unnecessary reading of whole file takes place. We need to read the file on whole to perform the aggregation. 
 Therefore, we need to read the whole file to perform the aggregation.
 Total memory waste in reading whole lot of files.
 
 
 But, in columnar format- the columns are stored in separate blocks, which can be accessed through the data.
 For instance, if we want to read the data, we can read only that column and store it.
 
 Encoding in Column Format:
 Using Repeated
 Using Dataload
