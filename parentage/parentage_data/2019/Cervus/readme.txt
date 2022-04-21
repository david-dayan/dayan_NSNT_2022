# readme

There are multiple subdirectories for this Cervus year because we needed to reduce the final number of candidate parents to a size that can fit into internal cervus data structures.

sires/dams only subdirectories include analyses conducted on ALL sires OR ALL dams. These analyses used the full allele frequency data, but their own simulations. The results were used to identify sires or dams that have more than 1 mismatch with all offspring. 

The final dataset used for downstream analysis is under the subdirectory "filtered_parents" . This parentage analysis uses only candidate parents with <= 1 mismatch with at least one offspring in sires/dams only analyses. This parentage analysis uses the full allele frequency data (all parents all offspring), but it's own simulation file (final empirical number of dams and sires).
