# VectorLoglessPairHMM for OpenPOWER [![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
Optimized PairHMM code for GATK 3.x

## HOW TO BUILD
Run make to build a shared library, libVectorLoglessPairHMM.so

   `make`

## HOW TO RUN
Add a command-line option -Djava.library.path=_dir_ to GATK tools that use PairHMM (e.g., HaplotypeCaller and Mutec2)
(_dir_ is the directory where libVectorLoglessPairHMM.so was placed) 
