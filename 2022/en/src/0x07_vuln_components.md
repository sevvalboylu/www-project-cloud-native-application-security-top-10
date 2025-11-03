CNAS-7: Using components with known vulnerabilities
===========================================

## Overview

TBD

## Description

Open Source projects intorduce many vulnerabilities through unmaintained open source packages. Cloud native applications make use of many third party dependencies that they do not have control over, sometimes with known vulnerabilities. This may or may not introduce these known vulnerabilities to the cloud native applications, and must be avoided when there is alternatives. Developers must make sure that they do not call vulnerable methods of these vulnerable dependencies, and should update their dependency regularly to ensure security compliance. 

## How To Prevent

* Use SAST and DAST scanners to ensure your project is not affected from the known vulnerabilities. 
* Update dependencies regularly, especially if there are known exploited vulneabilities in the third party dependencies that your project utilizes.
* 


## Example Attack Scenarios

### Scenario #1

TBD

### Scenario #2

TBD

## References

### External

* TBD
