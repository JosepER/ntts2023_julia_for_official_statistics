# Julia as a software for Official Statistics and Social Sciences

## Author
Josep Espasa Reig - Data Scientist @ LIS - Cross-National Data Center in Luxembourg

[Connect on Linkedin](https://www.linkedin.com/in/josepespasareig)

## Introduction
:wave: Welcome to the repository of my presentation for the NTTS 2023 conference!

This talk addresses the advantages and disadvantages of using Julia in the field of Official Statistics and Social Sciences. 

## Contents
Here you will the slides in PDF format, the links to the repositiories, Docker images you can use to reproduce the computations and a short summary of the presentation.

## Summary / __TL;DR:__ 
:question:Should Data Scientists use Julia for Official Statistics and Social Sciences tasks?

* :zap: Julia offers substantial increases in speed for most functions. These tend to range from 1.2x to ~20x improvements.
* :elephant: Julia tends to be more memory efficient than R, but the imporovements are much more moderate (up to ~4.5x less memory)
* :grey_exclamation: Calling Julia functions from R creates an overhead which tends to halve the speed benefits of using Julia. 



* The package ecosystem in Julia is less mature. DS in the field will find:
  *  :white_check_mark: great packages for general tasks such as reading and manipulating data;
  *  :large_orange_diamond: a limited range of options for more specific tasks such as computing estimates and variances with complex survey designs or imputing missing values;
  *  :red_circle: no packages for some of the most niche tasks, such as statistical matching.

## Presentation and repositories

* [Presentation in PDF format](https://github.com/JosepER/ntts2023_julia_for_official_statistics)
* [Repository for Julia computations](https://github.com/JosepER/ntts_2023_benchmarking_julia)
* [Repository for R computations](https://github.com/JosepER/ntts_2023_benchmarking_r)

## Docker images
To download the Docker images for the computations the following commands on the CLI:
`docker pull joseper/ntts_benchmarks_jl`
and 
`docker pull joseper/ntts_benchmarks_r`


