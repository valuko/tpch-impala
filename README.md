# Impala TPC-H Benchmark suite
TPC-H Benchmark suite for Impala. 

## Setup tools
Use the TPC-H data generation tool to generate the data
Create the Impala database `tpch_300` and load the generated data into it

## Usage
Run `./run.sh` to run the benchmark

## Other notes
tpch_impala_original dir contains the original benchmark queries from the source repository. You can re-run them if any issues are noticed with the queries in tpch_impala

The repository also contains Hive TPC-H queries. `run.sh` can be modified to also run the Hive queries also

## Further Resources
Refer to Impala_tpch_README.md for more guide
