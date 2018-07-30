# HH25_postTrunk_Trinity
RNAseq de novo assambly and analysis of chicken posterior trunk


## TRINITY, RNAseq
### SIB course in Bern 2018 with Brian Haas
Check this wiki for many complete infos https://github.com/trinityrnaseq/BernWorkshop2018

Can not run locally, need hpc. Here, baobab from unige is used.

## BAOBAB

All files are in Baobab home/HH25_Trinity/

Some specificities:

Need to write #SBATCH file. SBATCH = Slurm BATCH, specific to baobab. Starting with "#", here is not a comment. To comment the line, "##". This file type is SBATCH, and it is written in BASH language.
Edit with nano if not manage with vi.

Write the #SBATCH script in the folder where you want the output. Give it a name name.sh. For this example: runjobTrinity.sh


