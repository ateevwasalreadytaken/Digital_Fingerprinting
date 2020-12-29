# Digital_fingerprinting
Digital fingerprint embedding and detection mechanisms

manipulation.ipynb currently takes an image address and username as input. A new image is saved locally 
containing transparent pixels at select scattered locations. The locations are determined on the basis of 
the ASCII values of the username characters.

Traditonal_fingerprinting.ipynb represents the notebook through which one of two different types of 
fingerprinting will take place. based on the inputted links of the original and suspected image addresses, 
similarity is checked.

If the plagiarism was lazy and no cropping had taken place, the notebook that will be run through the 
Traditional_dingerprinting.ipynb notebook will be the Fingerprint_scanner.ipynb noptebook where the original
and non-offset locations will be checked for transparency.

If cropping was done, the alternativce_fingerprinting.ipynb notebook will be run and a hash value for equal
windows of the two images: cropped and original will be compared and a score indicating similarity will be 
displayed. The two windowed images will also be saved in the execution of this notebook.

"Original" test image:
https://d37k7e86lke5eg.cloudfront.net/webp-images-live/5feaff88f5d17744297bf879-1609236360622normal.webp

"Plagiarized" simple:
https://d37k7e86lke5eg.cloudfront.net/webp-images-live/5feb041cf5d17744297bfbf2-1609237532572normal.webp

Cropped "plagiarized" version:
https://d37k7e86lke5eg.cloudfront.net/webp-images-live/5feaffaff5d17744297bf883-1609236399871normal.webp
