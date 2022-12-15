# Algorithms-for-sequence-analysis
./hmm.py -vv(to print out the matrix) (-i x[x is number of iterrations]) baumwelch/forward/backward input/sequence_X1.fasta input/A1_prior.tsv input/E1_prior.tsv

FOR the HMM:

./hmm.py -vv backward input/sequence_X1.fasta input/A1_prior.tsv input/E1_prior.tsv

For the sequence generator:

python3 sequence_generator.py A.tsv E.tsv
