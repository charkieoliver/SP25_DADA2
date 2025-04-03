These scripts serve as a record of the processing work done for the spring 2025 amplicon sequencing run. 
They can be easily adapted to fit other amplicon sequencing runs. 

Troubleshooting tips for errors while demultiplexing:
If the demultiplexing step reuturns errors, or outputs very low sequence counts try these steps:

1. Reverse complement the barcodes
2. Check that the barcodes are 12 bases long
3. Add an A to the end of the barcode sequence
4. Check for incompatible characters in the barcodes, such as spaces
5. Check for duplicate names in the barcodes, often "Blank" or a number. Rename them to something else. 
