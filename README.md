# 1000G_vcf_to_r_sq
<code>
usage: 1000G_vcf_to_r_sq.py [-h] [-i in-file] [-o out-file] [-r r2-cutoff]

Process 1000G vcf to get R-square values.
The first line is used as y.
The rest lines are used as X. Get R-square values of X and y

optional arguments:
  -h, --help    show this help message and exit
  -i in-file
  -o out-file
  -r r2-cutoff
  
Example:
> python 1000G_vcf_to_r_sq.py -i sample_data/input_1_by_1000.vcf -o sample_data/output_cutoff0.2 -r 0.2

Output
> head sample_data/output_cutoff0.2
chr     pos     id      r2
11      438611  rs188272071     0.9999994
</code>
