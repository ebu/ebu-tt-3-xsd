## Current status: DRAFT, work in progress

Please consider this work as non-final for the time being.

## This repository

This repository contains an XML Schema for entities defined in the EBU-TT Live (Part 3) specification,
[Tech3370](https://tech.ebu.ch/publications/tech3370).

* Copyright 2019, EBU, www.ebu.ch
* Version of XML Schema: 0.9
* Creation: 01/07/2019

The publication of this EBU-TT XML Schema for EBU-TT Part 3 is intended to support the 
implementation of the specification in EBU-Tech 3370 version 1 based on modifications to
EBU Tech 3350 v1.2.

Please note that the EBU-TT XML Schema is a helping document and NOT normative but informative.

## Cloning

This schema depends on ebu/ebu-tt-xsd which in turn depends on the ebu/ebu-tt-m-xsd repository;
those dependencies are imported via a git submodule.
If cloning from the command line make sure to include the `--recurse-submodules` option,
or after cloning run `git submodule init` and `git submodule update`.
