# RNAseqNormalisation
<b>Methods for normalising RNAseq datasets</b>

To enable inter-sample measurements of absolute RNA amount, equal amount of bacterial RNA was spiked into each sample according to the ERCC spike-in Mix

recommendations (Jiang et al., 2011).

Immediately after collection, 1μl of SMART-Seq v4 lysis buffer (0.2U/μl RNase inhibitor) and 1 μl of ERCC Mix1-2 (final dilution 1x10-6) were added to the

cells prior to freezing. Two different ERCC mixes containing the same 96 transcripts at different ratios were added.

After sequencing,raw reads from the ERCC mixes were counted and normalised to tpm. In order to evaluate the degree of correlation between two ERCC mixes,

the expected versus the calculated fold-change ratio was plotted (tpm > 1). The correlation ranged from 0.951 to 0.993.

A calibration curve was generated based on ERCC rpkm values and the respective known concentration. For each sample, a standard equation was calculated.


