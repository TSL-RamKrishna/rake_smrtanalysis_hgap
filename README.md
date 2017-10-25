## Introduction

A script for Pacbio data denovo assembly with HGAP3. Users will need to provide a list of bax.h5 files from all SMRTcells. See a sample list of bax.h5 file.

## Requirement

1) ruby rake
2) smrtanalysis v2.3p5

## usage:

1) rake -f rakefile inputfofn=listOfBaxH5.txt     #by default the project folder HGAP_Assembly will be created.
2) rake -f rakefile projectdir=NewHGAP inputfofn=listOfBaxH5.txt
