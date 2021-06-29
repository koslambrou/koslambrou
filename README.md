### Hi there 👋, I'm koslambrou, a Haskeller, Nix contributor and free software enthusiast from Quebec.

Currently working full-time as a Software Engineer at <a href="https://iohk.io">IO Global</a> and part time as a Linked Open Data Engineer at <a href="https://www.cinematheque.qc.ca">Cinémathèque québécoise</a>.

### A little more about me in RDF...
```turtle
@prefix gh: <https://github.com/> .
@prefix foaf: <http://xmlns.com/foaf/spec/> .
@prefix db: <https://dbpedia.org/resource/> .
@prefix dbo: <https://dbpedia.org/ontology/> .

gh:koslambrou a foaf:Person ;
  dbo:language db:Haskell_(programming_language) ;
  dbo:language db:Python_(programming_language) ;
  dbo:language db:Javascript ;
  dbo:language db:Nix_package_manager ;

  # Semantic web technologies
  dbo:language db:Resource_Description_Framework ;
  dbo:language db:SPARQL ;
  dbo:language db:SHACL ;
  dbo:language db:Web_Ontology_Language ;

  gh:tool db:React_(JavaScript_library) ;
  gh:tool db:Redux_(JavaScript_library) ;
  gh:tool db:Node.js ;
  gh:tool db:Express.js ;
  gh:tool db:Apache_Spark ;

  gh:os db:NixOS ;
  gh:os db:Debian ;

  gh:realisation "http://data.cinematheque.qc.ca" ;
  gh:realisation "http://data.cinematheque.qc.ca/dataviz/polyscc" ;
  gh:realisation "https://www.antoinebeland.com/inf8808" ;
.
```

### Gitlab

See my <a href="https://gitlab.com/koslambrou">Gitlab account</a> for other projects I'm contributing.
