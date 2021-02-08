---
layout: ontology_detail
id: cryoem
title: Cryo Electron Microscopy ontology
jobs:
  - id: https://travis-ci.org/I2PC/cryoem
    type: travis-ci
build:
  checkout: git clone https://github.com/I2PC/cryoem.git
  system: git
  path: "."
contact:
  email: coss@cnb.csic.es
  label: Carlos Oscar Sorzano
  github: cossorzano
description: Cryo Electron Microscopy ontology is an ontology that describes data types and image processing operations in Cryo Electron Microscopy of Single Particles
domain: imaging
homepage: https://github.com/I2PC/cryoem
products:
  - id: cryoem.owl
  - id: cryoem.obo
usages:
    - user: http://scipion.i2pc.es/
      description: Scipion software uses cryoem ontology to describe its objects and protocols
      examples:
        - url: http://workflows.scipion.i2pc.es/
          description: Workflows from Scipion based on cryoem ontology

tracker: https://github.com/I2PC/cryoem/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Cryo Electron Microscopy ontology describes data types and image processing operations in Cryo Electron Microscopy of Single Particles.

The objects and protocols described in this ontology are the ones used in the cryo em image processing framework Scipion.

More info can be found at http://scipion.i2pc.es/