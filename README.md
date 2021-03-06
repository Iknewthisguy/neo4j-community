JAR files for the neo4j Graph Database
==================================================

This gem provides a set of jar files of the Neo4j Graph Database.

To use it: `require 'neo4j-community'`

It can be used directly but the intention is to use it with [neo4j.rb](https://github.com/andreasronge/neo4j).

How to Release
==================================================

1. cd neo4j-advanced
2. git clean -df # make sure there are no local file
3. rm -rf tmp # make sure old tar file is deleted
4. mkdir tmp
5. Download tar/gz file from http://neo4j.org/download
6. cp ~/Download/neo4j-community-VERSION to tmp
7. rake upgrade
8. edit the lib/neo4j-community/version file

There should now be a gem file available in the pkg folder. 
  gem install pkg/neo4j-community-VERSION-java.gem  


License
==================================================

This gem is MIT licensed.

However the jars included are licensed by [Neo4j](http://neo4j.orb).

