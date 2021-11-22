# Pong and Tornado
Per our understanding, the pong code and tornado server and linked together in the current versions. To faciliate better user interfacec integration, we'd like to explore the possibility of separating these two components.

If it's possible, we would like to split the creation of pong data (and generation of client-side code) and the web-server management. That way, integration with cbioportal and other tools would become far simpler. At the moment, we are using an approach to launch personalized tornado servers for each job, which can be brittle.
