# MozillaApacheDataset-sample

Small sample of the [20-MAD dataset](https://github.com/M3SOulu/MozillaApacheDataset) containing:
* All the commits for Hadoop and Zookeper for Apache;
* All the commits for the \emph{releases-comm-central} repository for Mozilla;
* All the issues and issue comments for the Thunderbird product for Mozilla;
* All the issues and issue comments for the Hadoop, HDFS and Zookeeper products for Apache.

The sampled issue tracker products were chosen based on the sets of
source code repositories in order to have a sufficiently large amount
of issues and issues comments linked to commits. Respectively for
Mozilla and Apache, the sample contains respectively over 28k and 71k
commits, 52k and 32k issues, 410k and 367k comments, and 1.2M and 1.9M
natural language sentences. Including the NLP data, the sample totals
around 250MB as a set of Parquet files, 350MB as a set of compressed
CSV files and all the files can be loaded in memory using less than
2GB of memory.
