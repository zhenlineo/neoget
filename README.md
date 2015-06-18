Neo4j Download script
=====================
```
Usage: neoget [<options>] [<version> [<version> ...]]

Download tool for Neo4j server packages.

Action Options:
  -d  download the latest or specific Neo4j packages (default)
  -l  show a list of available Neo4j versions
  -h  display this help text

Alpha Release Options:
  -a  select the latest alpha release for download

Edition Options:
  -c  use Neo4j Community edition (default)
  -e  use Neo4j Enterprise edition

List Options:
  -f list only archive file names
  -u list full download URLs (default)
  -v list only versions

Environment:
  NEO4J_DIST - base URL for downloads (default: http://dist.neo4j.org)

Report bugs to nigel@neotechnology.com
```

Download Latest Release
-----------------------
```
neoget
```

Download Latest Enterprise Release
----------------------------------
```
neoget -e
```

Download Specific Release
-------------------------
```
neoget 2.1.8
```

Download Latest Alpha Release
-----------------------------
```
neoget -a
```

List Releases
-------------
```
neoget -l
```
