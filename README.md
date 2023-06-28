This repo contains code for the analysis done in Section 3 of https://arxiv.org/abs/2306.11428

**Disclaimer**: This code is for a highly specfiic scientific analysis and is not intended for wide-scale use. It was also written at a time when I 
was still learning Python and so is quite messy and inefficient in places. I will try to detial it's use here.

### Code contents

*des_functions.py* contains functions which carry key parts of the analysis, such as cutting the DES shape catalogues and creating the matched
catalogue, as well as carrying out correlation function calculations and jackknife re-sampling. Analysis itself is done in the notebooks. Key 
notebooks essential to the results presented in the paper are labelled with ANALYSIS. Other notebooks contain various tests and experiments with
which aided me in learning to use certain packages etc.

### Internal data

Unfortunately, a lot of the data generated in this analysis is stored outside the repo. However, I am happy to share it on request.

### External data

The key external data used are the DES Y1 catalogues, which can be found here: https://des.ncsa.illinois.edu/releases/y1a1/key-catalogs

