# Spladder_v1
Patient based splice site events identification tool 

Two major division: 1. splice-site alignment 2. Functional Annotation


# Splice-Site Alignment 

Set up enviornment for run:

      Download and run:
        Miniconda or anaconda -v 3
      
      Add Bioconda channels:

        conda config —add channels defaults
        conda config —add channels conda-forge
        conda config —add channels bioconda
    
      Set up an environment:
        
        
        conda create -n "name" snakemake hisat2 stringtie samtools python=3.6 
        conda activate "name"
        conda install -c bioconda subread


