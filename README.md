# json-to-tsv

**TODO:**
* add scripts to repo
* make list of versions into links to the scripts

***

Small script that takes a JSON and outputs it as tab-separated-values.

It creates the headers by grabbing the keys of the first object in the JSON, meaning the script doesn't care how many key-value-pairs are in the objects, nor what they are named, it will simply change it to tsv.

Two version is available.
1. For local runs
2. As Azure Function 

***
*Limitations*
* Only able to handle a flat JSON structure, no nesting allowed.


***
