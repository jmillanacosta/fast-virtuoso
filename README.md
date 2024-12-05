# Set up a virtuoso triplestore

## Requirements
- CLI Docker installed
- Linux system

## Steps

1. Run 

```sudo docker compose up -d```

2. Go to the conductor at [`http://localhost:8899/`](http://localhost:8899/)` the  and use the log in:
 - User: `dba`
 - Password: `CONDUCTOR_PASSWORD`

3. Upload the RDF graph via `Linked Data` > `Quad Store Upload` > `Browse`. Give it a relevant IRI.

4. Go to [`http://localhost:8899/sparql/`](http://localhost:8899/sparql/)

5. If you need to remove data, go to `Linked Data` > `Graphs` > `Graphs` and delete your added graph.

6. When you're done, ```sudo compose down``` and move on with your life.
