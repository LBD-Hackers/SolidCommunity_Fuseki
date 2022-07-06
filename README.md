# Community Solid Server - custom LBD
This is a prototype [Solid Community Server](https://github.com/CommunitySolidServer) which mirrors all RDF files to a SPARQL endpoint (Apache Jena Fuseki). 

Additional requirements: 

- Add an .env file to the root folder, pointing to a Fuseki endpoint (e.g. http://localhost:3030)
- `npm i -g env-cmd`
- install Apache