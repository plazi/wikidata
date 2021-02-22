# Import of taxonomic treatment data into Wikidata

## Goal
Add [taxon treatments](https://www.wikidata.org/wiki/Q32945461) to Wikidata from [taxon: (Q16521)](https://www.wikidata.org/wiki/Q16521) using at least the [Plazi ID: P1992](https://www.wikidata.org/wiki/Property:P1992) or creating [taxon treatment: Q32945461](https://www.wikidata.org/wiki/Q32945461) in Wikidata. 

## Workflow
1. Liberate taxonomic treatment data from taxonomic publications
2. Run Quality Control to assure the data is fit for use to create the entries in Wikidata
3. Use bots linked to the existing Plazi workflow to automatically to create the entries
4. Add taxon treatment ID to Plazi stats

## Level of granularity of depositions
1. add Plazi ID to an existing taxon, or create a taxon, link it to a higher taxon and link from the taxon via the Plazi ID to the respective treatment in TreatmentBank (via the persistent http URI) or Biodiversity Literature Repository via the taxon treatment DOI (eg. )
2. add a taxon treatment to Wikidata, linked to taxon, including the publication, taxon instance, taxon, rank, figures

## Increase in complexity of the upload
1. Start with species that have been described very recently and do with high probability not exist in Wikidata
2. Work backwards throug the backlog of new species taxon treatments
3. Add treatments that annotate existing treatments, make synonymies

## Data availability
1. Every year, an estimated of ca 17,000 new species are descrived. Plazi extracts ca 50% from lierature, that is about 20-25 new species.
2. An estimate of ca 1.9M species have been described. Plazi has about 160,000 that could be added.
3. Besides treatments for sp. nov. there are in total 500,000 treatments that either are for new taxa or extend the knowledge of species, or synonymize species. The annual input of new taxonomic treatments is rapidly growing.

## Future developments
1. 
