**Synth Bio Lang Syntax**

**ChangeLog 0.1**
* Replaced 'promoter' with 'operator' in defintion 7
* Added definition for terminator (definition 11).
* Added new definition for promoter (definition 10).
* Changed DNA format from [PROMOTER][START][GENE][STOP] to [OPERATOR][PROMOTER][START][GENE][STOP][TERMINATOR]

**Dictionary**
* **Definition 1**
	Operon: An operon is a functional unit of code/DNA. 
	The format appears like this: [OPERATOR][PROMOTER][START][GENE][STOP][TERMINATOR]
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
	Operator: An operator is a DNA sequence that binds to a specific transcription factor, 
	triggering or repressing transcription. It "checks" for the existence of a transcription factor. An operator can either be an enhancer (binds to an activator TF) or a silencer (binds to a repressor TF).
	Analogous to 'if' statement.  
* **Definition 8**
	Transcription factor: Binds to a specific promoter, triggering transcription. 
	TFs are what is being checked for following an 'if' statement. Can be an activator (presence triggers transcription) or
	a repressor (presence represses transcription).
* **Definition 9**
	Transcribe: Function that places a gene sequence, surrounded by a start and stop codon, following the promoter.
* **Definition 10** 
	Promoter: A promoter is a region of DNA following an operator. It signals the origin of transcription. A promoter must be 		included or else RNA Polymerase (enzyme responsible for transcription) will not bind to the DNA.
* **Definiton 11**
	Terminator: Region of DNA at the very end of an operon. Triggers the detachment of RNA Polymerase from the DNA.

if (transcription factor){

transcribe(gene);
    
}

=

[OPERATOR][PROMOTER][START][GENE][STOP][TERMINATOR]
