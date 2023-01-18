# Compare similar DNA or Protein Sequences using Web Interfaces
URL PATH: compare_similar_sequences_ui


Here we will compare protein sequences.  The Gene EXOSC2 expresses: exosome component 2 — an exoribonuclease complex that participates in degradation and processing of cellular RNA.  It is a Ribosomal RNA-processing Protein.  Exosome component 2 is composed of a precisely-folded polypeptide chain with an amino acid sequence coded in the gene EXOSC2 of the DNA in chromosome 9 at position q34.

To compare with another protein we will use the Basic Local Alignment Search Tool (BLAST).

## EXOSC2 Gene - Exosome Component 2    2NN6
<img width="1046" alt="001-EXOSC2_2NN6" src="https://user-images.githubusercontent.com/12736699/213064294-c8057105-9882-468e-87c4-f4e9ecbd9e4d.png">
&nbsp;

&nbsp;

We obtain the FASTA for the protein showing the code for the Amino Acids, and enter this in blastp (rather than the 'n' for nucleotides).
Enter the FASTA sequence, add a "Job Title" of your choosing, and check "Align two or more sequences" as follows:
<img width="832" alt="002-enter_protein-code" src="https://user-images.githubusercontent.com/12736699/213064303-b18d5867-d682-4d16-8ad0-d09f1f9d8804.png">
&nbsp;

We want to compare this proteins sequence with a similar protein.
&nbsp;

One way to find a similar protein is to use NCBI BLAST+ and do a "Protein Similarity Search"
&nbsp;

&nbsp;

Check only the FASTA files you want, in this case only the first one, and under "Entries" click "Download" fasta.
This will download a FASTA file to the location of your choosing on your workstation or, if the information is not too great, open in the browser.
<img width="1210" alt="003-ck-one-download-fasta" src="https://user-images.githubusercontent.com/12736699/213064306-4cc7ad70-aef1-499c-81a0-290465af88bc.png">
&nbsp;

&nbsp;

All the data from the download can be entered as the "Subject Sequence" then click the "BLAST" button
<img width="937" alt="004_enter-second-fasta" src="https://user-images.githubusercontent.com/12736699/213064311-06245925-a812-48e4-9d33-6d1ce32b49a0.png">
&nbsp;

&nbsp;

Eventually, you will get a results page.  From here click the "Alignments" tab:
<img width="1332" alt="005_come-to-results-pg" src="https://user-images.githubusercontent.com/12736699/213064313-a994076c-9926-4b59-8fd0-d7def6c61fe4.png">
&nbsp;

&nbsp;

This is our result after we clicked the "Alignments" tab.   We see that the proteins are indeed similar save for the 26 amino acid gap between the two:
<img width="1264" alt="006_click-alignments-26gap" src="https://user-images.githubusercontent.com/12736699/213064317-d1bc4573-ce4a-4e19-91bd-d726a43e04a1.png">
&nbsp;

&nbsp;

There is a "graphics" link that you can take to see the same data displayed graphically:
<img width="1409" alt="007_examine_graphics" src="https://user-images.githubusercontent.com/12736699/213064320-4ce117dd-8372-4957-8c4a-d3607ce93f43.png">
