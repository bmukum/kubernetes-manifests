### Hey Big Clau


- These are just few manifests I wrote

- It's quite simple.

- The frontend ngix deployment talks to midtier tomcat application.

- Midtier tomcat application talks to backend postgres database.

- The connection is simple at the moment.

- It uses ClusterIP services for internal communication and NodePort to expose frontend app.

- Topics like security, authentication, traffic restrictions can come later. You spoke of using service Mersh. I don't know if it can work internally in a cluster.

- But I used services to allow traffic flow. Traffic flow can be restricted using network policies which is another big topic.

- Things like password, users, data and volume mapping can come in later as well by setting up configMaps, secrets and/or persistent volumes.

- This is just a small workflow to show you how you can set up the manifest files. 

- Let me know if you want me to add something.
