* Visit https://starter.karms.biz/ (or https://start.microprofile.io/ once Quarkus is released there)
* Select MicroProfile version 3.0 (or newer)
* Select MicroProfile Server Quarkus
* Select examples you would like to see or all of them
* Unzip demo.zip
* cd service-a in one terminal and follow readme.md
* cd service-b in another terminal and follow readme.md
* Note there are 3 modes; try live hot reload :dev, JVM mode :build and also :native -Pnative
* You can download another server, this time via CLI, pick only some specs (none selected = all are selected)
* curl -O -J 'https://starter.karms.biz/api/project?supportedServer=HELIDON&selectedSpecs=JWT_AUTH&selectedSpecs=OPEN_TRACING&selectedSpecs=REST_CLIENT&artifactId=helidon'
* You can also see full CLI documentation: curl https://starter.karms.biz/api
* unzip helidon.zip, stop Quarkus service-b and run service-b from Helidon, see that Quarkus talks to Helidon
* To play more with the REST API, one can see all specs: 
* curl 'https://starter.karms.biz/api/supportMatrix' | qjf
* qjf tool is pretty-printing Json, https://github.com/Karm/qjf
* Download your favorite server, try the demos, let us know what you think on https://gitter.im/eclipse/microprofile-starter or file an issue on GitHub: https://github.com/eclipse/microprofile-starter

