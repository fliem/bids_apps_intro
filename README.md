
# Introduction to BIDS Apps
Franz Liem (franziskus.liem@uzh.ch)

## Description
[BIDS Apps](http://bids-apps.neuroimaging.io) are portable neuroimaging
pipelines that understand [BIDS datasets](http://bids.neuroimaging.io).
They facilitate executing standard neuroimaging pipelines,
like FreeSurfer, fmriprep, cpac, mriqc..., for processing structural and
functional MRI data.
BIDS Apps run on all three major operating systems with no need for a
complex setup and configuration and very little user input.


For more background see [Gorgolewski et al. (2017)](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005209).

For a list of available BIDS Apps see
[here](http://bids-apps.neuroimaging.io/apps/).


## What to expect
After a brief introduction to BIDS Apps and [Docker](http://docker.com)
software containers, participants will run the
[MRIQC](http://mriqc.readthedocs.io/en/latest/)
software on their laptops, to judge the quality of MRI data.

## Prerequisites
The tutorial is open to everyone with basic experience with MRI data.
No prior experience with command line tools, docker, BIDS Apps or
MRIQC is required.

## What to bring
* Laptop with Docker installed
(see guides for
[mac](https://docs.docker.com/docker-for-mac/install/),
[windows](https://docs.docker.com/docker-for-windows/install/),
[linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/))
* if possible, already download (pull) the docker container we will be
using:
    * open a terminal window/command line
    * paste the following command: `docker pull poldracklab/mriqc:0.10.4`
    * press enter and wait for the download to be finished
* [download](https://osf.io/fsyq2/download) the this BIDS-formatted
example data set (430 MB)
*  optionally, bring your own BIDS-formatted MRI data
(T1w and/or functional), for instance, the result of the
**Introduction to BIDS** tutorial)

## Slides
will be posted [here](https://github.com/fliem/bids_apps_intro).
