# ISOR
Simple Iterative Sequential Outlier Removing with Dynamic Neighbors

Mistake in manuscript: 

Page 7, Table 3: There is a minor mistake for testing ISOR on NSGD-recall. We only tested 999 image pairs in the four 1000-image-pair datasets. Therefore, the NSGD-recalls are: 563/99, 918/999, 814/999 and 437/999 for ISOR (also writing 0.437437437437437 to 43.73 by mistake).

We ignored the first image pair in all four datasets. The reason is that the two images in the first image pair of CPC dataset are the same one (serial number: 00000052,00000094), and an error reported in solving this pair mainly because of the number of correspondences selected by SIFT are too large to process for our laptop. We than set the start number as 2 in my implemenation, which result in the total tested number to be 999. 
