# Import of taxonomic treatment data into Wikidata

## Goal
Add [taxon treatments](https://www.wikidata.org/wiki/Q32945461) to Wikidata from [taxon: (Q16521)](https://www.wikidata.org/wiki/Q16521) using at least the [Plazi ID: P1992](https://www.wikidata.org/wiki/Property:P1992) or creating [taxon treatment: Q32945461](https://www.wikidata.org/wiki/Q32945461) in Wikidata. 

## State of work
* 20220529 Treatments [examples](https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Fw.wiki%2F5A3h&data=05%7C01%7C%7C8594dd4f57e946a22b9508da416c7902%7Cbe0003e8c6b9496883aeb34586974b76%7C0%7C0%7C637894231403416246%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=OTsefzL4pzMmg%2F0wr9lqib%2FGxfk6OcN03DQaWXar0rY%3D&reserved=0) in Wikidata using bot (manually triggered). All the [treatments in Wikidata](https://nam04.safelinks.protection.outlook.com/?url=https%3A%2F%2Fw.wiki%2F5A3i&data=05%7C01%7C%7C8594dd4f57e946a22b9508da416c7902%7Cbe0003e8c6b9496883aeb34586974b76%7C0%7C0%7C637894231403416246%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C3000%7C%7C%7C&sdata=Ls59ZUZ6khfRYiWeCcAteut2faNF5URPGMIo165MMLs%3D&reserved=0)

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
