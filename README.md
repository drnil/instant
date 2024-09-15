# Readme for the INSTANT Neuronal Spike-Train ANalysis Toolbox

Martin Nilsson, RISE Research Institutes of Sweden (E-mail: instant@drnil.com)

## Introduction

The INSTANT Neuronal Spike-Train ANalysis Toolbox is a program that
inputs a spike train and estimates the corresponding neuronal
parameters. This program also estimates errors and performs
statistical tests of stationarity and independence. The program is
implemented in MATLAB.

The INSTANT software and data is part of the supplemental material for
the article _Nilsson and Jörntell (2021): "Channel current
fluctuations conclusively explain neuronal encoding of internal
potential into spike trains"_, DOI:10.1103/physreve.103.022407.

## Manual

A user manual for INSTANT in PDF format is available
as `instant-manual.pdf`.

## Code and installation

The source code is available as the Base64-encoded ZIP-archive
`instant.txt`. This file can be decoded under
the Microsoft Windows operating systems using the command

    certutil -decode instant.txt instant.zip
	
The source code can be loaded into MATLAB and executed.
This requires a MATLAB license. INSTANT was developed using version
2013a of MATLAB. The compatibility with later versions is not
guaranteed.

Compiled code is available as `instant.exe`. This can be executed
without any MATLAB license by first downloading and installing
the MATLAB Compiler Runtime (MCR) version 2013a (8.1), 32-bit. 
To find the MCR, go to the MathWorks web site and search for "runtime".
The URL looks like:

    https://se.mathworks.com/products/compiler/matlab-runtime.html

The MCR file is named

    MCR_R2013a_win32_installer.exe
	
Follow the installation instructions on the web page.

After installing the MCR, you can start INSTANT by double clicking
`instant.exe`. Beware that there is sometimes an error on first startup.
This is usually resolved by starting a second time.

## Spike train data input sample files

Fourteen recorded sample spike trains are available in the
Base64-encoded ZIP archive `spike-train-data.txt`. These spike trains
were recorded by Henrik Jörntell at the Department of Experimental
Medical Science at Lund University.  The file can be decoded under the
Microsoft Windows operating systems using the command

    certutil -decode spike-train-data.txt spike-train-data.zip
	
## Processed data output sample files

The output from INSTANT for all sample spike trains are collected
in the file `instant-combined-output.pdf`. In
addition, computed parameters are summarized in the file
`parameter-data.xls`.

## For more information

Please see the manual `instant-manual.pdf` for details.
