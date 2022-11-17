# Template for Warehouse ELT jobs.

* Source data files go in [raw](./raw)
* Any custom scripts go in [scripts](./scripts)
* Everything should build with a single `make` invocation.
* The README.md should create a link to or screenshot of the FOIA request
* The README shoud describe the data and have links to the generated database(s)

## Storing artifacts in a release.
Generated data should in a release. I typically, [create a release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository#creating-a-release) called nightly. 

## To Build
```bash
> pip install -r requirements.txt
> make
```
