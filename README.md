# TFAct
Calculation of Transcription Factor Activity in Human Data

## Scripts:
1. validation_expr_data_processing.r: Preprocesses the expression (microarray) data from TF knockdown experiments in cell lines. Has three user-defined/pipeline-dependent inputs: input_path (the path to the unprocessed expression data), output_path (where to save the processed data), and run_name (used for logging and as a prefix for all file names). The script will automatically generate differential expression values, both using RUV (removal of unwanted variation) and not.
2. validation_activity_calculation.r
