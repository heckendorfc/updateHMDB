This script updates HMDB for OpenMS

It generates a HMDBMappingFile.tsv and a HMDB2StructMapping.tsv that is used by the AccurateMassSearch

#Steps to do :  
 
1. Download "**All Metabolites**" files as XML from http://www.hmdb.ca/downloads   
![image](hmdb_download.png)
2. extract into folder hmdb_metabolites  
3. delete hmdb_metabolites.xml unless it is the only file
4. execute python scripts:  
```
python generateHMDB2StructMapping.py 
python generateHMDBMappingFile.py
```
