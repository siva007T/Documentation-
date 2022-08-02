QC-analysis
============

Quality control (QC) is a prediction of the probability of an error in base calling. It serves as a compact way to communicate very small probabilities.
A high quality scores implies that a base call is more reliable and less likely to be incorrect. In FASTQ files, quality scores are encoded into a compact form, which uses only 1 byte per quality value. In this encoding, the quality score is represented as the character with an ASCII code equal to its value + 33. There are several tools that are publically available for conducting quality control on raw FASTQ files

.. toctree::

    Feng_1
    Feng_2
    Sean_1
    Sean_2
    seanmid
