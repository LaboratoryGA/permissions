# Permissions
Claromentis 7.x module which provides an alternate implementation of system permissions.

## Motivation
Claromentis has a fairly rudimentary permissions system built-in, but unfortunately, it relies on an arbitrary number to determine for which module/subsystem the permission is applicable. Since there is no central directory of these numbers, nor any way to register/request/assign a new number, it is fairly useless for modules developed outside of Claromentus UK.

This module provides a similar degree of functionality, but uses namespaces, modules, and resource markers, providing a less conflict-prone system with fine-grained control.

## Pre-requisites
This module requires the following modules be installed:
* ORM
