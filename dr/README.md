# Disaster Recovery solution

This solution relies on :

* JFrog CLI plugin to synchronize local, remote, virtual repositories between 2 JPDs
* JFrog Pipelines as the workflow engine to execute the JFrog CLI plugins on events or scheduling

## Structure

* jfpipe_extension : 2 JFrog Pipelines extensions were created : bashV2 and ping 
* reposync : A pipeline for JFrog Pipelines to perfom repositories synchronization between 2 JPDs. It relies on the ping and bashV2 extensions.
* healthcheck : A pipeline for JFrog Pipelines to perfom a health check on multiple JPDs. It relies on the ping extension.

## Documentation

See all the documentation in the [PS Google Drive](https://docs.google.com/document/d/1tfx3djeI_nB8Wk7OwBezjoSsDvzqVvHktD9QNVgr8RA/edit)

## Customers

this repository was shared with the following customers :

Date | Customers | Comment
---|---|---
October 2022 | Infosys India | 1st implementation
