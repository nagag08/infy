# JFrog Pipelines extension : ping

this extension requires at least 2 [JFrog platform Access Token integration](https://www.jfrog.com/confluence/display/JFROG/JFrog+Platform+Access+Token+Integration) as an input of the step.
It will configure as many JFrog CLI as there are **JFrog platform Access Token integration**. The 1st CLI profile will have as **server-id** jpd_1, the 2nd will have jpd_2, ...
The CLI profiles will be created in the same order as provided in the integration section of the step.
