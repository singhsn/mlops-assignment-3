# MLOps Assignment 3

Evaluation summary - 

Metric	Original	Quantized
R² Score	0.575788	0.575468
RMSE	0.7456	0.7459
File Size (KB)	0.681	2.099
Theoretical Size (bytes)	68	36
Theoretical Size (KB)	0.07	0.04
Compression Ratio	-	0.32x



 Observations
R² Score Preservation:
 The quantized model maintained almost identical performance, with a minimal R² loss of 0.000320.


Compression:
 The theoretical size was reduced from 68 bytes to 36 bytes, giving a 1.89× compression.


Model Efficiency:
 Float16 quantization provided significant compression with negligible impact on accuracy, validating its use in model size-sensitive deployments.
