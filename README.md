# Leveraging Generative Model for De Novo Design of Broad-Spectrum Antimicrobial Peptides

The Code is avaliable in the code/ folder.

Because the full dataset is too large, we uploaded the data for reproducing the results in this paper only due to the space limit of GitHub. The full dataset will be released once the paper is accepted. 

1. The data for training the model can be downloaded from UniPort.

2. amp_seq_data.csv: the data for fine-tuning the model.
3. predict_50000.fasta: the generated 50,000 sequences.

4. The data for training the four classifiers: 
 amp_p.fasta, amp_n.fasta
 spectrum_p.fasta, spectrum_n.fasta
 toxicity_p.fasta, toxicity_n.fasta
 mic_p.fasta, mic_n.fasta

5. The data for training the regressor: micpos.xlsx

6. predict_256.xlsx: the 256 sequences after filtering and sorting.

7. predict_256_ID.xlsx: the 256 sequences and their corresponding bsa IDs.
