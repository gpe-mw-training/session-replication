Session Replication
===================
OpenShift supports scalable applications. Scaling enables your application to react to changes in HTTP traffic and automatically allocate the necessary resources to handle the current demand. The OpenShift Enterprise infrastructure monitors incoming web traffic and automatically adds an additional gear of your web cartridge online to handle requests. 

For scaled applications, the JBoss App Server cartridge leverages the clustering support already available in the JBoss App Server. As a result, when your application uses web session data, the JBoss App Server cartridge will automatically replicate the data. As a developer, you simply configure your web application to use the distributable tag.

This repo contains sample files for testing session replication. 
