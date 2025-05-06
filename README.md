# binf2010-scripting-assignment-solved
**TO GET THIS SOLUTION VISIT:** [BINF2010-Scripting assignment Solved](https://www.ankitcodinghub.com/product/binf2010-scripting-assignment-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97348&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;BINF2010-Scripting assignment Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
BINF2010 – Scripting assignment

“Glue” programming and scripting are important skills in bioinformatics, allowing the automation of complex and repetitive tasks when analysing large datasets. This assignment is worth 15% of the total mark for the course and requires you to write a script to automate a “pipeline” of bioinformatics tasks.

Two options for the assignment are presented. Option 1 involves writing a bash shell script while option 2 involves a scripting language such as Perl or Python. Students who are doing or have done COMP2041 Software Construction and are familiar with Perl should be doing Option 2. If you have or are taking COMP2041 and you choose Option 1 your mark will be capped at 65%.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>Option 1: Bash shell script
Write a bash shell script that retrieves all the reviewed mammalian protein sequences from UniprotKB that correspond to a specific gene name (specified as argument 1 when running the script) then creates a multiple sequence alignment out of these sequences then builds a phylogenetic tree from this multiple sequence alignment.
</li>
</ul>
<ul>
<li>Your submission should consist of one file named uniTree.sh</li>
<li>The script should be invoked using the command ./uniTree.sh GENE
where GENE is a gene code in UniprotKB, found in the Gene name [GN] field. Example gene names include INS and EGF.

The output of the script should be a phylogenetic tree file in Newick format (nested parentheses) suitable for input into a tree visualisation program such as Dendroscope. The file should be named GENE.tree (where GENE is the gene name specified at the command line). The leaves of the tree should be labelled with only the species name as much as the program allows you to (in some cases you may get multiple proteins from the same species in which case you may need to add a number to the name in the tree). An example output for EGF is on Moodle. However, note that because the databases are constantly updated, the example output may not be exactly as your program will generate it.
</li>
</ul>
• The script should perform the following suggested steps:

o Retrieve from UniprotKB all the sequences with the specified gene

name in their GN field that also are of Mammalian origin (field OC= Mammalia [40674]) and have been reviewed for inclusion into SwissProt (field Reviewed set to Yes). The sequences should be retrieved in one file in fasta format. You probably will need to make use of the Uniprot RESTful API (http://www.uniprot.org/help/programmatic_access) for this, together with the UNIX command wget.

o Edit the header of the fasta sequences so that they contain only the species name. If there are multiple sequences from the same species (for example a protein with multiple isoforms) you can add a number to the species name – eg Mus musculus1 and Mus musculus2.

o Runamultiplesequencealignmentprogram(egclustalw)to align the sequences and create a multiple sequence alignment

o Run another program to build a phylogenetic tree out of the multiple sequence alignment. Clustalw with the –tree option is probably the easiest option for this as phylip programs are quite

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
tricky to script and require writing a “batch file” (but do not simply use the clustalw guide tree created during multiple sequence alignment (.dnd file) as the tree as it is not a true phylogenetic tree).

o Rename the tree file if necessary.

o Delete any intermediary files created by the script, keeping only

the final tree output (and any other files that were already there when you started the program).

Option 2: Perl or Python script

Select this option if you are already familiar with a scripting language, for example if you are doing or have done COMP2041

Write a Perl or Python script that

<ol>
<li>takes as input a bacterial genome sequence in fasta format</li>
<li>searches it for ORFs</li>
<li>selects the 3 longest ORFs of length ≥ 150bp/50aa (if there are not 3
ORFs that long, selects only the ones over the minimum length)
</li>
<li>translates them into protein</li>
<li>searches the PDB database for matching proteins with at least 40%
identity using the RSCB PDB Search API (https://search.rcsb.org/index.html#search-api), retrieving only the highest-scoring hit
</li>
<li>Formats the results into a table in CSV format</li>
</ol>
The table should have up to 3 data rows (for the 3 longest ORFs) plus one header row with the following headers:

<ul>
<li>Start: the start position of the ORF on the sequence</li>
<li>End: the end position of the ORF on the sequence (note: for ORFs on the
reverse strand, the end position index will be smaller than the start

position)
</li>
<li>Strand: FORWARD or REVERSE</li>
<li>BLAST hit: the PDB identifier of the top hit matching the translated ORF
in the PDB database. If there is no similar sequence with at least 40%

sequence identity then this field should just contain “-“ (no quotes)
</li>
<li>E-value: the e value for the top BLAST hit, provided it is equal or lower
than 1. If it is &gt;1 then the field should contain “-“ (no quotes)

The lines in the CSV file should be sorted by start position. An example input and output (geobacter.fasta, geobacter.csv) are provided in Moodle. However, note that because the databases are constantly updated, the example output may not be exactly as your program will generate it.
</li>
</ul>
<ul>
<li>Your submission should be a single file named geneannot.pl or geneannot.py</li>
<li>The script should be invoked at the command line using the command ./geneannot.pl filename.fasta (or ./geneannot.py</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
filename.fasta) where filename.fasta is the name of a nucleotide

sequence file in fasta format containing a segment of a bacterial genome

<ul>
<li>Your script should work with nucleotide sequences of length of up to
20,000 nucleotides (it can work with longer sequences if you want to but

you should assume a test sequence of up to 20 kbps).
</li>
<li>Script should quit gracefully if the input sequence is invalid or not in fasta
format.
</li>
<li>Script output should be in CSV format and go to standard output so it can
be redirected if necessary. For example:
</li>
</ul>
o ./geneannot.pl foo.fasta will display the CSV output on

the screen.

o ./geneannot.pl foo.fasta &gt; bar.csv will save the

output to a file named bar.csv • Suggested steps for the script:

o Submit the input sequence to an ORF detection program of your choice (as long as it is installed in binftools)

o For each of the 3 longest ORFs identified longer than (or equal to) 150bp, its protein translation should be submitted using the Protein Sequence Search API at RSCB PDB.

o Parse both the ORF detection and the RSCB search outputs to extract the required information into a table in the specified format

o Sort the ORFs by start position

o Delete any intermediary files created by the script, keeping only

the final CSV output (and any other files that were already there when you started the program).

</div>
</div>
</div>
