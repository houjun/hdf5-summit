# Instructions to generate and submit benchmarking job scripts
1. There is one directory for each set of experiments, e.g. summit_baseline.
2. To run the experiments, go to a directory, e.g. `cd summit_baseline`.
3. Modify the template script to specify a valid project ID on Summit.
4. Run the job script generation code, `./gen.sh`, 4 new directories each with one job script are created, e.g. node2 for the 2-node jobs.
5. On a Summit login node, run the job submission script `./submit.sh` to submit the job scripts in all 4 directoris.
6. The output will be generated under each directory, with various timing information measured in the ior application.
