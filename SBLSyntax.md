**Synth Bio Lang Syntax**


* **Definition 1**
	Operon: An operon is a functional unit of code/DNA. 
	The format appears like this: [PROMOTER][START][GENE][STOP]
* **Definition 2**
	If: An if statement checks for the existence of a transcription factor in the cell.
	It denotes the creation of a promoter.
* **Definition 3**
	Then: A then statement follows an if statement and describes which gene is transcribed. 
	It denotes the creation of a protein-coding gene sequence surrounded by Start and Stop codons.
* **Definition 4**
	Start codon: Must exist at the beginning of every protein-coding gene sequence. 
	Marks the location translation begins.
* **Definition 5**
	Stop codon: Must exist at the end of every protein-coding gene sequence.
	Marks the location translation end.
* **Definition 6**
	Gene: A gene is a sequence of protein-coding DNA. Codes for protein IF promoter 
	has been activated. Analogous to 'then' statement.  
* **Definition 7**
	Promoter: A promoter is a DNA sequence that binds to a specific transcription factor, 
	triggering transcription. It "checks" for the existence of a transcription factor.
	Analogous to 'if' statement.
* **Definition 8**
	Transcription factor: Binds to a specific promoter, triggering transcription. 
	TFs are what is being checked for following an 'if' statement.
* **Definition 9**
	Transcribe: Function that places a gene sequence, surrounded by a start and stop codon, following the promoter.



if (transcription factor){

transcribe(gene);
    
}

=

[PROMOTER][START][GENE][STOP]
