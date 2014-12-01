# Visualizations

A collection of next-gen sequencing visualisation scripts. Click a script's
name to go to it's subdirectory which will contain a detailed `README.md`
file with examples and instructions.

* [Count Biotypes](stand_alone/count_biotypes/)
	* Uses HTSeq to plot read overlaps with different feature biotype flags
* [preseq Complexity Curves](stand_alone/preseq_complexity_curves/)
* [Subsampled Gene Observations](stand_alone/subsampled_gene_observations/)
    * Group of scripts to plot the number of observed genes at varying sample
    subsampling proportions. Can give an impression of library complexity on
    a biological level.
* [Qualimap Plots](ngi_visualizations/qualimap/)
    * Scripts to generate Coverage and Insert Size histograms. Both of these
    plots are already produced by Qualimap. These just look nicer in our
    reports and have some extra plotting options.
* [snpEff Effect Type Plot](ngi_visualizations/snpEff/)
    * Script to create bar charts of SNP Effect counts, generated by snpEff.
* [Gene Body Coverage](stand_alone/gene_body_coverage/)
* [Alignment Summaries](stand_alone/alignment_summaries/)
	* Two scripts to parse log files containing alignment stats from bowtie,
		bowtie 2 or tophat and generate overview HTML reports
* [Bismark Addons](stand_alone/bismark/)
	* [Bismark Coverage Curves](stand_alone/bismark/#bismark-coverage-curves) - Plots the proportion of cytosines meeting increasing coverage thresholds
	* [Bismark Window Sizes](stand_alone/bismark/#bismark-window-sizes) - Plots the proportion of windows passing observation thresholds with increasing window sizes

### Examples
See below for example outputs. Click an image to go to that script.

<table>
  <tr>
    <th colspan="2"><a href="stand_alone/count_biotypes/">Count Biotypes</a></th>
  </tr>
  <tr>
    <td width="50%">
      <a href="stand_alone/count_biotypes/" title="Count Biotypes">
        <img src="examples/SRR1304304_trimmed_aligned_biotypeCounts.png">
      </a>
    </td>
    <td>
      <a href="stand_alone/count_biotypes/" title="Count Biotypes">
        <img src="examples/SRR1304304_trimmed_aligned_biotypeLengths.png">
      </a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th><a href="stand_alone/preseq_complexity_curves/">preseq Complexity Curves</a></th>
    <th><a href="stand_alone/subsampled_gene_observations/">Subsampled Gene Observations</a></th>
  </tr>
  <tr>
    <td width="50%">
      <a href="stand_alone/preseq_complexity_curves/" title="preseq Complexity Curves">
        <img src="examples/complexity_curves_readcounts.png">
      </a>
    </td>
    <td>
      <a href="stand_alone/subsampled_gene_observations/" title="Subsampled Gene Observations">
        <img src="examples/subsampled_gene_observations.png">
      </a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th colspan="2"><a href="ngi_visualizations/qualimap/">Qualimap Plots</a></th>
  </tr>
  <tr>
    <td width="50%">
      <a href="ngi_visualizations/qualimap/" title="Coverage Histogram">
        <img src="examples/qualimap_coverage.png">
      </a>
      <a href="ngi_visualizations/qualimap/" title="Insert Size Histogram">
        <img src="examples/qualimap_insertsize.png">
      </a>
    </td>
    <td>
      <a href="ngi_visualizations/qualimap/" title="Genome Fraction Coverage">
        <img src="examples/genome_fraction.png">
      </a>
      <a href="ngi_visualizations/qualimap/" title="GC Distribution">
        <img src="examples/gc_distribution.png">
      </a>
    </td>
  </tr>
</table>
<table>
  <tr>
    <th colspan="2"> <a href="ngi_visualizations/snpEff/">snpEff Effect Plots</a></th>
  </tr>
    <td width="50%">
      <a href="ngi_visualizations/snpEff/" title="snpEff Effect Regions Plot">
        <img src="examples/snpEff_effect_regions.png">
      </a>
    </td>
    <td>
      <a href="ngi_visualizations/snpEff/" title="snpEff Effect Type Plot">
        <img src="examples/snpEff_effect_types.png">
      </a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th><a href="stand_alone/gene_body_coverage/">Gene Body Coverage</a></th>
    <th><a href="stand_alone/alignment_summaries/">Alignment Summaries</a></th>
  </tr>
  <tr>
    <td width="50%">
      <a href="stand_alone/gene_body_coverage/" title="Gene Body Coverage">
        <img src="examples/geneBodyCoverage.png">
      </a>
    </td>
    <td>
      <a href="stand_alone/alignment_summaries/" title="Alignment Summaries">
        <img src="examples/bowtie_align_screenshot.png">
      </a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <th><a href="stand_alone/bismark/#bismark-coverage-curves">Bismark Coverage Curves</a></th>
    <th><a href="stand_alone/bismark/#bismark-window-sizes">Bismark Window Sizes</a></th>
  </tr>
  <tr>
    <td width="50%">
      <a href="stand_alone/bismark/#bismark-coverage-curves" title="Bismark Coverage Curves">
        <img src="examples/coverageStats.png">
      </a>
    </td>
    <td>
      <a href="stand_alone/bismark/#bismark-window-sizes" title="Bismark Window Sizes">
        <img src="examples/windowSizes_roi.png">
      </a>
    </td>
  </tr>
</table>

### Contributing
If you would like to add a visualization script to this repository, please
read the [contributing notes](CONTRIBUTING.md) first. These describe the
steps required in adding your script to the repository.

### Credits
These scripts were written for use at the 
[National Genomics Infrastructure](https://portal.scilifelab.se/genomics/)
at [SciLifeLab](http://www.scilifelab.se/) in Stockholm, Sweden.
For more information, please get in touch with
[Phil Ewels](https://github.com/ewels).

<p align="center"><a href="stand_alone/http://www.scilifelab.se/" target="_blank"><img src="examples/SciLifeLab_logo.png" title="SciLifeLab"></a></p>
