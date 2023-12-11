# Remove Multiprocessing dependency from WikiExtractor.py
Modify the original [WikiExtractor.py](http://medialab.di.unipi.it/wiki/Wikipedia_Extractor) so that it could be executed on windows.

Multiprocessing is not applied which means that the computational performance is not at its best.

Usage: python -m WikiExtractor.py enwiki-20231201-pages-articles-multistream1.xml-p1p41242.bz2 --output C:/output/

Caveat: did not test on other use cases. 


[Wikipedia database backup dump](https://dumps.wikimedia.org/)
