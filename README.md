Community Solid Server - SPARQL forwarding

This is a prototype Solid Community Server which mirrors all RDF files to a SPARQL endpoint (Apache Jena Fuseki).
How to set up?

    git clone https://github.com/LBD-Hackers/SolidCommunity_Fuseki.git
    Run npm install
    Add an .env file to the root folder, with the variable "SPARQL_STORE_ENDPOINT" pointing to a working Fuseki endpoint. For example: SPARQL_STORE_ENDPOINT=http://localhost:3030
    Download and run Apache Jena Fuseki: .\fuseki-serve (Windows)
    Run npm run start:file
    Visit the Solid Server in your browser, and follow the steps indicated there to create your first Solid Pod. A database will be automatically created on the Fuseki instance.
    Done!
