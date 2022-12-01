# JFrog Pipelines : Repository synchronization

This pipeline will perfom the following steps :

1. Ping source and target JPDs
2. Check if the source JPDs had an outage in the last 2 hours
3. If no outages, create local, remote, virtual repositories (in this order) in the target JPD + generate an inventory (YAML file) per type of repository (local, remote, virtual).
