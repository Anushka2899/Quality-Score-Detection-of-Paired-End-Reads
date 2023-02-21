# Quality-Score-Detection-of-Paired-End-Reads

The project involved working with two paired-end run NGS file in the fastq format. The main aim of the project was to analyse the paired end-run files to check the quality score of each read out of the 10000 reads present in each file with each read being 250 bp long. Quality score is the most common metric used to assess the accuracy of a sequencing platform. It indicates the probability that a given base is called incorrectly by the sequencer.

The quality score was detected in two ways- 

Firstly, all the reads were checked for the ith position and the number of bp at the ith position with qs greater than 30 were counted. 

Secondly, each individual read of 250 bp long was counted for a specific number between 0 to 250 and the bp with quality score greater than 30 were counted.

For each of the python functions performing each task, matplotlib.py was used to plot each read and the corresponding quality score according to the ith position and the specific value between 0 to 250.
