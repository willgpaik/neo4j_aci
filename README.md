# neo4j_aci
Singularity recipe for Neo4j on Centos 7 for ICS ACI clusters

Singularity recipe is not completed. Instead try local installation:
```
$ cd ~/preferred/dir
$ wget https://neo4j.com/artifact.php?name=neo4j-community-3.5.12-unix.tar.gz -O neo4j-community-3.5.12-unix.tar.gz
$ tar -xf neo4j-community-3.5.12-unix.tar.gz
$ rm neo4j-community-3.5.12-unix.tar.gz
$ cd ~/preferred/dir/neo4j-community-3.5.12/bin
$ ./neo4j start
then, open firefox and type:
http://localhost:7474/browser/
```
