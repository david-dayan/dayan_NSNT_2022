# readme for directory "parentage_data"  
  
- This directory contains inputs and outputs for/from Cervus and Colony  
- Subdirectories are organized by offspring year, each subdirectory contains:  
    - all data required to run Cervus and Colony for a given offspring year  
    - unprocessed outputs from Cervus and Colony for a given offspring year  
    - processed Cervus and Colony pedigrees for a given offspring year  
    - final consensus pedigree for a given offspring year  
    - note that the same parents occur can occur across multiple offspring years, so all information for a given parent may be spread across multiple subdirectories  
- Input sets of parents and offspring (except for 2020) are almost exactly the same as those from Bohn, but the files and their contents might differ slightly:  
    - 2020 uses new data, so there is no corresponding input/output data from Bohn  
    - sample names have been unified (see [Prepare Input Data])  
    - offspring sample names gave precedence to carcass samples over live samples if they were likely duplicates in a previous approach, but Bohn and Kathleen decided that live samples should be given precedence. to save time, Bohn just changed the numbers AFTER THE FACT in the results, creating a bit of nightmare for replication. to avoid this problem, I changed offspring in the input files to reflect giving precendence to live samples over carcass samples when they seemingly from the same fish (see appendix b from Bohn's assigment criteria). The end result is the same individuals and sample sizes per group as Bohn's approach, but implemented from the beginning  
    - a small number of Bohn's input files did not reflect what was in the report (perhaps ad hoc editing of results to make changes without redoing analyses), went with the report numbers for my new runs
- Input parameters (colony.DAT files, cervus .crv files, logs) are different from those found in Bohn's directories and reflect the actual runs    
