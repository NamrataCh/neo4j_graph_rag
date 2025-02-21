# neo4j_graph_rag
The repository contain base example of creating graph RAG using Neo4j, langchain, ollama open source model

You need to setup Neo4j Desktop Application on your machine by:
  - First download and install the application from https://neo4j.com/deployment-center/?desktop-gdb
  - Create a local DBMS
  - Install apoc plugin to the db
  - copy apoch_core.jar from ../lab/ to ../plugins/ folder for the databse
  - update neo4j.conf with:
      - dbms.security.procedures.unrestricted=apoc.*
        
