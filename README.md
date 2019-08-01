# Scholarsphere API Specification

## Description

Specification documenting the interface requirements for Scholarsphere. Currently, this is only the basic
aspects of the existing Scholarsphere 3.x application. As such, there are aspects of PCDM and linked data
inherent in the specification.

## Purpose

This will be used as the basis for building Scholarsphere 4.0.

## Status

Completely experimental. Don't base anything on this at all.

## Documentation

Documentation is generated automatically in [docs](docs/index.html)

To generate new documentation:

    npm install -g redoc-cli
    redoc-cli bundle -o docs/index.html openapi.yml
