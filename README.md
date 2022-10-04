# Snakemake_Notes

### Why use Snakemake?
- Preservation is easier
- Built on top of python
- Easy to implement docker, conda, and tagged versions
- Supports batch jobs and parllelization

### Snakefile
- Stores rules for building intermediate items (input, output, command)
- Inputs are outputs of other rules
- rules.[rulename].output_file can be used to refer to the output of a specific rule
- expand wildcard allows you to expand out a variable 

### Notes from Mike Love
-
