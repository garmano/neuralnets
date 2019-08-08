# neuralnets
Tool for analysing multilayer perceptrons using phidelta diagrams

Understanding the inner behaviour of multilayer perceptrons (MLPs) during and after training has been a goal of many researchers for decades. However, advances in this research topic have been hindered by the propensity to acknowledge that this behaviour
cannot be analysed either by humans or by performance evaluation algorithms. In fact, relevant patterns emerge upon training, which are typically related to the underlying problem difficulty. The occurrence of these patterns can be highlighted by means of phidelta diagrams, a 2D graphical tool originally devised to support the work of researchers on classifier performance evaluation and on feature assessment. In particular, according to the assumption that MLPs are powerful engines for feature encoding, hidden layers have been inspected as they were in fact hosting new input features. Interestingly, there are problems that appear difficult if dealt with using a single hidden layer, whereas they turn out to be easier upon the addition of further layers. A training strategy inspired by some foremost recommendations of deep learning has also been devised and implemented, which shows an increase of accuracy with respect to classical backpropagation.

In this project MLPs have been implemented from scratch, including several tools devised to facilitate the run of experiments; see in particular "batch_runner.py", together with some useful batch files (e.g., "easy-commands.batch"). There is no need to describe the syntax of a batch file, as it is quite self-explaining. See also the file "batch-reporter.py", which can used to generate summary files concerning multiple experiments (obtained by means of the batch_runner).

Some exemplar datasets have also been included, the vast majority of them having been downloaded from the machine learning repository at UCI.

A summary file (see "datasets.info") is used to give the loader all information on the available datasets (the file "datasets-info.readme" gives information about the corresponding syntax).

Please note that all datasets have been binarized, as phidelta diagrams need binary problems. 

For any question concerning how to use this software please contact me by email (email address: armano__at__unica.it).

   Giuliano Armano

PS To the time of this writing (i.e., August 2019), an implementation of this software using Pandas and Keras is under way.
