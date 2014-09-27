# puppetmodule-template

#### Table of Contents

1. [Overview](#overview)
2. [Module Description - What the module does and why it is useful](#module-description)
3. [Setup - The basics of getting started with skel](#setup)
    * [What skel affects](#what-skel-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with skel](#beginning-with-skel)
4. [Usage - Configuration options and additional functionality](#usage)
5. [Reference - An under-the-hood peek at what the module is doing and how](#reference)
5. [Limitations - OS compatibility, etc.](#limitations)
6. [Development - Guide for contributing to the module](#development)

## Overview

A simple Puppet module template skeleton.

## Module Description

Includes RSpec and Bundler out of the box.

## Setup

- git clone https://github.com/grahambeedie/puppetmodule-skel.git MODULE_NAME_HERE

- Rename the class declaration in init.pp to something meaningful.

- Update the .ftxtures.yml to refelect the change.

- Write your manifests, defines and tests.

### Setup Requirements

* Ruby 2.1
* Puppet 3.7.1-1
* Bundler 1.6.2 

### Beginning with template

See [Setup - The basics of getting started with template](#setup)

## Usage

See [Setup - The basics of getting started with template](#setup)

## Reference

Here, list the classes, types, providers, facts, etc contained in your module.
This section should include all of the under-the-hood workings of your module so
people know what the module is touching on their system but don't need to mess
with things. (We are working on automating this section!)

## Limitations

Untested on Ruby versions <= 2.1 and Puppet versions <=3.7.*. YMMV.


## Release Notes

N/A