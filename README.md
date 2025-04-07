# fastp_summarize
purpose: summarize the output .json files from fastp (https://github.com/OpenGene/fastp)

# Setting up
 1. clone repository, or just download the fastp_summarize.py and example data
```
git clone https://github.com/laurasisk/fastp_summarize
```

 2. You may have to make the python script executable 

```
chmod +x fastp_summarize.py
```
  
 3. Have all the .json output files from fastp that you wish to summarize in one directory, with no other json files 
in that directory

# Usage 
```
 python fastp_summarize.py <directory_name_with_json_files> 
```
# Outputs
This will product three summary files: results before filtering, results after filtering, and fastp results summary

# Example
```
fastp_summarize.py example_data
```
