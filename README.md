# SPARQL query generator

This is a revival of a tool by [Benestar](https://github.com/Benestar)
that used to be hosted at https://tools.wmflabs.org/bene/sparql.
That URL is currently down, so the project was copied here to revive the tool.

Check out the live demo at **http://waldyrious.github.io/sparql-query-generator/**.

The tool is a simple web interface that helps with creating SPARQL queries for Wikidata
by filling subject-predicate-object triples.
An autocomplete dropdown feature is available to translate human-readable labels
into Wikidata codes for items and properties.

The generated query can then be ran in the [Wikidata Query Service](https://query.wikidata.org/).
