# vericoding-lean-benchmark

Typically,
1. Run `lake update` to update the `lake-manifest.json` file.
2. Run `lake build benchmark/*` to build all the files.

If you see compile problems in the dependencies, 
1. Delete .lake folder and lake-manifest.json to be sure.
2. Run `lake build benchmark/*` to build all the files.