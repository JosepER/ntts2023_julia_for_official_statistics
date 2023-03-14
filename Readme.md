# Julia as a software for Official Statistics and Social Sciences

## Author
:man: Josep Espasa Reig - Data Scientist @ LIS - Cross-National Data  Center in Luxembourg :left_right_arrow: [Connect on Linkedin](https://www.linkedin.com/in/josepespasareig)

## Introduction
:wave: Welcome to the repository of my presentation for the [NTTS 2023](https://ec.europa.eu/eurostat/cros/content/NTTS2023_en) conference in Brussels!

This talk addresses the advantages and disadvantages of using Julia in the field of Official Statistics and Social Sciences. 

## Contents
Here you will find a short [summary of the presentation](#summary--tldr), the [recording of the presentation](#Presentation-and-repositories), the [slides in PDF format](https://github.com/JosepER/ntts2023_julia_for_official_statistics/blob/main/presentation/julia_for_official_stats_espasareig.pdf), the links to the [repositiories](#Presentation-and-repositories), and the [Docker images](#Presentation-and-repositories) you can use to reproduce the computations.

## Summary / TL;DR:
:question: Should Data Scientists use Julia for Official Statistics and Social Sciences tasks?

* :zap: Julia offers substantial increases in speed for most functions. These tend to range from 1.2x to ~20x improvements.
* :elephant: Julia tends to be more memory efficient than R, but the improvements are much more moderate (up to ~4.5x less memory)
* :grey_exclamation: Calling Julia functions from R creates an overhead which tends to halve the speed benefits of using Julia. 
<img src=https://user-images.githubusercontent.com/8353293/222904287-0685f33e-35a3-4796-a750-087dbf9c9a50.png alt = "Julia_R_ratios" width = "80%" height = "75%">


* The package ecosystem in Julia is less mature. DS in the field will find:
  *  :white_check_mark: great packages for general tasks such as reading and manipulating data;
  *  :large_orange_diamond: a limited range of options for more specific tasks such as computing estimates and variances with complex survey designs or imputing missing values;
  *  :red_circle: no packages for some of the most niche tasks, such as statistical matching.

## Presentation and repositories

* :video_camera: [Recording of the presentation](https://webcast.ec.europa.eu/ntts2023-day-1-mans-20230307) - :alarm_clock: Starts at 16:19:00
* :memo: [Presentation in PDF format](https://github.com/JosepER/ntts2023_julia_for_official_statistics/blob/main/presentation/julia_for_official_stats_espasareig.pdf)
* :package: [Inequality.jl Julia package](https://github.com/JosepER/Inequality.jl) for computing income and wealth inequality indicators
* :file_folder: [Repository for Julia computations](https://github.com/JosepER/ntts_2023_benchmarking_julia)
* :file_folder: [Repository for R computations](https://github.com/JosepER/ntts_2023_benchmarking_r)

## Docker images
To download the Docker images for the computations the following commands on the CLI:
`docker pull joseper/ntts_benchmarks_jl`
and 
`docker pull joseper/ntts_benchmarks_r`


