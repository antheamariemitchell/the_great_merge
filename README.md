    --The Great Merge--

Combining CSVs: Useful Code Attempt 1

Goals for this script:

1. Make a chunk of code that improves workflow

2. Ensure it's written in such a way so as to be universal, variables rather than exact names so there are minimal changes required by user

3. Count number of controls as an additional bonus at the end

4. Determine if csvs are of the same length, and alphebetize

5. Check for symmetry based on sample name and remove any mismatches, then output a list of what those are is a separate file

6. Combine two CSVs based on sample name and output a separate merged file

7. Also contains a much shorter, and often times more practical python script for a simple merge of csvs by name column. This script strips out those samples that do not have matching corresponding samples in other CSVs, without clarifying which ones are being removed. This must be manually checked.