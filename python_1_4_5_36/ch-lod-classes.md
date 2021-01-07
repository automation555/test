# Carnegie Hall Linked Open Data - Classes

## OVERVIEW

Below are classes used in the Carnegie Hall (CH) data set. The table also includes a brief usage note per class and the vocabulary from which the class is sourced. 

## CLASSES USED
|Class|CH Usage|Vocabulary|
|:----|:---|:----------|
|[Event](http://purl.org/NET/c4dm/event.owl#Event)|Used in CH dataset to classify Events.|[Event Ontology](http://purl.org/NET/c4dm/event.owl)|
|[Event](http://schema.org/Event)|Used in CH dataset to classify Events|[Schema.org](http://schema.org/)|
|[E7_Activity](http://erlangen-crm.org/160714/E7_Activity)|Used in CH dataset to classify Events|[Erlangen CRM / OWL](http://erlangen-crm.org/160714/)|
|[Product](http://purl.org/NET/c4dm/event.owl#Product)|Used in CH dataset to classify sub-events, i.e. work performances|[Event Ontology](http://purl.org/NET/c4dm/event.owl)|
|[subEvent](http://schema.org/subEvent)|Used in CH dataset to classify sub-events, i.e. work performances|[Schema.org](http://schema.org/)|
|[MusicalWork](http://d-nb.info/standards/elementset/gnd#MusicalWork)|Used in CH dataset to classify musical works; a sub-class of Work|[GND Ontology](http://d-nb.info/standards/elementset/gnd)|
|[Work](http://d-nb.info/standards/elementset/gnd#Work)|Used in CH dataset for non-musical creative works, e.g. plays.|[GND Ontology](http://d-nb.info/standards/elementset/gnd)|
|[MusicalWork](http://purl.org/ontology/mo/MusicalWork)|Used in CH dataset to classify musical works|[Music Ontology](http://purl.org/ontology/mo/)|
|[MusicComposition](http://schema.org/MusicComposition)|Used in CH dataset to classify musical works; a sub-class of CreativeWork|[Schema.org](http://schema.org/)|
|[CreativeWork](http://schema.org/CreativeWork)|Used in CH dataset to classify non-musical creative works, e.g. plays.|[Schema.org](http://schema.org/)|
|[Bag](http://www.w3.org/1999/02/22-rdf-syntax-ns#Bag)| Used in CH dataset to classify placeholder "works", e.g. "Selections not included in program" or "No program issued", which are needed in source data to associate performers with events for which no program information is available.|[RDF Schema](http://www.w3.org/1999/02/22-rdf-syntax-ns#)|
|[Person](http://xmlns.com/foaf/0.1/Person)|Used in CH dataset to classify people|[Friend Of A Friend (FOAF)](http://xmlns.com/foaf/0.1/)|
|[Agent](http://xmlns.com/foaf/0.1/Agent)|Used in CH dataset to classify performing groups and organizations, e.g. orchestras, string quartets, etc.|[Friend Of A Friend (FOAF)](http://xmlns.com/foaf/0.1/)|
|[MusicArtist](http://purl.org/ontology/mo/MusicArtist)|Used in CH dataset to classify performing groups and organizations, e.g. orchestras, string quartets, etc.|[Music Ontology](http://purl.org/ontology/mo/)|
|[Instrument](http://purl.org/ontology/mo/Instrument)|Used in CH dataset to classify musical instruments|[Music Ontology](http://purl.org/ontology/mo/)|
|[PerformingGroup](http://schema.org/PerformingGroup) |Use in CH dataset to classify performing ensembles|[Schema.org](http://schema.org/)|
|[Role](http://schema.org/Role) |Use in CH dataset to classify roles, e.g. actor, conductor, magician, etc.|[Schema.org](http://schema.org/)|
|[Venue](http://dbpedia.org/ontology/Venue)|Used in CH dataset to classify the Carnegie Hall building, as well as each constituent venue|[DBpedia Ontology](http://dbpedia.org/ontology/)|
|[EventVenue](http://schema.org/EventVenue)|Used in CH dataset to classify the Carnegie Hall building, as well as each constituent venue|[Schema.org](http://schema.org/)|
|[ArchitecturalStructure](http://dbpedia.org/ontology/ArchitecturalStructure)|Used in CH dataset to classify the Carnegie Hall building|[DBpedia Ontology](http://dbpedia.org/ontology/)|

----------------------------
Go to: [DATA STRUCTURE](/data-structure.md) | [README](/README.md) | [SPARQL ENDPOINT](http://data.carnegiehall.org)
