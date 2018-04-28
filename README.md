# disambiguation-of-verbal-shifters
This repository contains the dataset created for the LREC 2018 paper "Disambiguation of Verbal Shifters" by Michael Wiegand, Sylvette Loda and Josef Ruppenhofer.

# data format
The directory Data contains the gold standard. It consists of 2000 labeled sentences. Each sentence contains a mention of an ambiguous shifter. The dataset comprises 20 different ambiguous shifters. For each shifter there are exactly 100 sentences in which it occurs.

The directory Data contains two subdirectories:

The subdirectory Text includes files with raw text. There are 20 files. Each file contains the sentences with a particular ambiguous shifter. The filename represents the name of that shifter. In those files, each line corresponds to one sentence. The sentences have been randomly extracted from the North American News Text Corpus (LDC95T21). Therefore, each sentence should always be considered in isolation.

The subdirectory Annotation contains the annotation of the ambiguous shifters in context. The organization of the subdirectory follows the structure of the subdirectory Text, that is, there are 20 files. Each file contains the annotation of a particular ambiguous shifter. The filename represents the name of that shifter. In those files, each line encodes the class label of the sentence in its equivalent file in the subdirectory Text.
There are two class labels:
"s" means that in the respective sentence the ambiguous shifter functions as a genuine shifter, whereas "n" means that in the respective sentence the ambiguous shifter does not function as a shifter.

# license
This dataset is free to use for research purposes.
If you use it for your research, please acknowledge this software by citing Wiegand et al. (2018). 
(Full bibliographic information, see reference below.)

If you intend to use this dataset for commercial purposes, please contact the owner of this resource (see contact information).


# acknowledgments
This work was partially supported by the German Research Foundation (DFG) under grants RU 1873/2-1 and WI 4204/2-1.



# contact information 
Please direct any questions that you have about this software to Michael Wiegand at Saarland University.

Michael Wiegand	      email: Michael.Wiegand@lsv.uni-saarland.de


# reference
Michael Wiegand, Sylvette Loda and Josef Ruppenhofer: "Disambiguation of Verbal Shifters", LREC, 2018.