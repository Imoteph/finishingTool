finishingTool
=============

finshingTool 


This is the command to do this post processing

python finisher.py destinedFolder mummerPath

Remark: 
Note that it is assumed that you have "contigs.fasta" , "raw_reads.fasta" in the destinedFolder and mummerPath is your path to Mummer.

Here is an example run with the pre-installed data files and softwares(e.g. Mummer, Gepard) [Please go to https://www.dropbox.com/sh/xjpt8xf5g1xf0ek/bGmZvt9Zfd to Download the EColi-Data set as test cases coz it is too big for GitHub].

1. You may run the test cases as python finisher.py EcoliTestRun/ MUMmer3.23/
2. After the processing, take the file whose name is "allInOne2.fasta" in destinedFolder and this is your output file.
3. If you want to visualize the output against the reference, you can issue the command of python viewer.py. And you will obtain dotplots [in EcoliTestRun] of
	a) each contigs against the reference 
	b) the whole new set of contigs against the reference. 
	c) the whole original set of contigs against the reference. 
4. Happy hacking ...

