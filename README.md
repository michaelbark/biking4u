# biking4u

[![Build Status](https://travis-ci.org/michael-simons/biking2.svg?branch=public)](https://travis-ci.org/michael-simons/biking2) [![Test coverage](https://sonarcloud.io/api/project_badges/measure?project=eu.michael-simons%3Abiking2&metric=coverage)](https://sonarcloud.io/dashboard?id=eu.michael-simons%3Abiking2) [![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=eu.michael-simons%3Abiking2&metric=alert_status)](https://sonarcloud.io/dashboard?id=eu.michael-simons%3Abiking2)

## Abstract

This is a project where i try out Java 8, Spring / Spring Boot and AngularJS. 

## NOTE

You'll need [GPSBabel][5] to build this project without errors and to use the tracks / log database. Errors running the `TracksControllerTest` are the result of a missing `gpsbabel` binary in the path.

    biking4u.gpsBabel = path/to/gpsbabel/binary

GPSBabel is available for all major operating systems, including windows. So please check if it's available on your platform if biking2 doesn't compile for you.

