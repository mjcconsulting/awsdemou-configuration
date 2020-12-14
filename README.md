# AWS Demo University Configuration
Cross-Account Multi-Environment Landing Zones Framework Configuration for the AWS Demo University Role Play Exercise.

This repository contains the configuration files for the AWS Demo University Role Play Exercise.

## CaMeLz Framework
This configuration is meant to be used with the CaMeLz Framework, which consists of a set of related
repositories used to build CloudFormation-based AWS architectures which may span multiple accounts.

### Related Repositories
* [CaMeLz Templates](https://github.com/mjcconsulting/camelz-templates)
* [CaMeLz Functions](https://github.com/mjcconsulting/camelz-functions)
* [CaMeLz Documents](https://github.com/mjcconsulting/camelz-documents)
* [CaMeLz Components](https://github.com/mjcconsulting/camelz-components)
* [CaMeLz Scripts](https://github.com/mjcconsulting/camelz-scripts)

## Dependencies
This code is currently written in bash and must be run from a Linux command line. This code has so
far only been tested on a MacBook Pro running MacOS Catalina. We will confirm proper operation on
the Windows Subsystem for Linux under Windows 10, using Ubuntu 18.10, in the near future.

### Additional Dependencies
* **AWS CLI** v2
  * [Installing](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
  * [MacOS](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-mac.html)
  * [Linux](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html)
  * [Windows](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-windows.html)
* **jp** (JMESPath binary) v0.1.3
  * [Releases](https://github.com/jmespath/jp/releases)
  * [MacOS](https://github.com/jmespath/jp/releases/download/0.1.3/jp-darwin-amd64)  
    To Install jp, download the pre-built binary, move and rename to /usr/local/bin/jp, set execute
    permissions
  * [Linux](https://github.com/jmespath/jp/releases/download/0.1.3/jp-linux-amd64)
  * [Windows](https://github.com/jmespath/jp/releases/download/0.1.3/jp-windows-amd64)

### License
CAMELZ Functions is [MIT licensed](./LICENSE).
