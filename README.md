# Geospatial Map Gallery
A gallery featuring cartographic projects I've made. This repository includes a jellyfish map series as well as other standalone maps covering glacier change, crime and deprivation, and malaria mapping. The maps are given as PDFs in their dedicated folders.

## Jellyfish Map Series
Jellyfish blooms are an increasingly important issue due to climate change. In warming waters, they can disrupt ecosystems, affect coastal industries, and negatively shape how people perceive the sea. However, jellyfish are not only a hazard. In some regions, they are also traded as a marine resource to be used as food. This map series aims to inform the general public, especially coastal communities and people interested in marine wildlife, about where jellyfish sightings cluster, how species records change over time, what environmental conditions may support blooms, how public attention compares with sting impact, and how jellyfish are traded as a resource.

### Map 1: Where Are the Jellyfish?
A point map with proportional symbols showing jellyfish sightings around the southwest UK region. Dominant species within large clusters are annotated.

<img width="2000" height="1414" alt="Image" src="https://github.com/user-attachments/assets/4f2b2656-b49f-47e4-9a86-88197d9bd774" />


### Map 2: Bloom and Bust
A streamgraph showing the relative abundances and changes in reported sightings of common jellyfish species in the UK between 2015 and 2025.

<img width="2000" height="1414" alt="Image" src="https://github.com/user-attachments/assets/f841ff38-f260-409e-994a-96cb1453c07c" />


### Map 3: What Feeds the Bloom?
A chlorophyll-a concentration map exploring possible environmental conditions linked to jellyfish bloom development.

<img width="1414" height="2000" alt="Image" src="https://github.com/user-attachments/assets/b9900055-089c-4189-85ab-f1f7afcb3d53" />


### Map 4: Sighting vs Stinging
A bivariate map comparing jellyfish reporting frequency with sting impact across UK counties to investigate whether jellyfishes are overly feared.

<img width="1414" height="2000" alt="Image" src="https://github.com/user-attachments/assets/a5819177-68c9-4dd1-b554-7b5a8ea31aef" />


### Map 5: Danger or Delicacy?
A flow map showing major international trade routes for edible jellyfish products, reframing jellyfish from hazards to resources.

<img width="2000" height="1414" alt="Image" src="https://github.com/user-attachments/assets/e9ec1ddc-d6c9-40cf-b844-0c58f9f78c9f" />


### Reflections and Limitations
For the most part, I am satisfied with what I’ve made. The maps convey their intended messages, and I was able to explore using new techniques and programmes. However, some improvements can be made:
- Maps 1 and 2: Relies on sighting records, which may reflect reporting efforts as much as actual abundance. Map 1 could also include stronger storytelling elements.
- Map 3: The spatial resolution of the data was very coarse. Although the gridded style makes this limitation explicit, higher-resolution datasets or more advanced processing could better resolve
coastal patterns. Investigating other factors, such as ocean currents, could also enhance the usefulness of this map.
- Map 4: Uses simplified species-based sting scores, which could be improved with more research into the biology of each species. It also uses unnormalised report counts, which may introduce bias due to differences in county size.
- Map 5: The initial plan was to map jellyfish as a resource in general. However, extracting the data from multiple HS codes proved too time-consuming, so the scope was narrowed down to the edible jellyfish trade


## Other Maps
This section includes additional standalone maps on various themes created outside the jellyfish series.

### Snow and Ice Changes at the Jakobshavn Glacier (2000-2024)
A map visualising the snow/ice changes over the Jakobshavn Glacier using NDSI changes from Landsat 7/8/9 satellite data. Analysis workflow and data sources can be found at: [landsat-glacier-ndsi](https://github.com/Anpanman11111/landsat-glacier-ndsi)

<img width="1897" height="2200" alt="Image" src="https://github.com/user-attachments/assets/13955208-de66-4522-b730-5820a1c435b7" />



### Urban Inequality in London
A bivariate map examining the relationship between recorded violent crime rates and socioeconomic inequality at the LSOA level in London. Violent crime rate is represented by “Violence against the person” records and 
standardised using mid-2024 LSOA population estimates per 1,000 residents, while Socio-economic inequality is represented using the 2025 IMD rank.

The map shows that high deprivation and high violent crime do not consistently overlap. Many of the deprived LSOAs experience comparatively lower violent crime rates. In contrast, red areas are concentrated in central London, showing that some places with higher crime are not the most deprived, suggesting that violent crimes may also be influenced by other factors such as transport hubs and commercial activity.

Data Sources:
- Population: [Office for National Statistics Lower LSOA mid-year population estimates](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/lowersuperoutputareamidyearpopulationestimates)
- Crime: [Mayor of London / Metropolitan Police recorded crime geographic breakdown](https://data.london.gov.uk/dataset/mps-recorded-crime-geographic-breakdown-exy3m)
- Deprivation: [Index of Multiple Deprivation dataset, Communities Open Data portal](https://communitiesopendata-communities.hub.arcgis.com/datasets/0fddc254c1184386bbeed27ed49bbd03_0/explore?location=52.837876%2C-2.327480%2C7)

<img width="905" height="656" alt="Image" src="https://github.com/user-attachments/assets/a25979e2-29f5-403d-bc7d-6db0a94bd7c8" />



### Changes in Malaria Detection and Hospital Distribution in the DRC (2000–2024)
A map showing the change in Plasmodium falciparum detection rates among children aged 2-10 in the Democratic Republic of Congo between 2000 and 2024, as well as the hospitals established within that time period.

Data Sources:
- Malaria incidence: [Malaria Atlas Project, *Pf* Incidence Rates](https://data.malariaatlas.org/maps)  
- Health facilities: [Healthsites.io, Democratic Republic of the Congo](https://healthsites.io/map?country=Democratic%20Republic%20of%20the%20Congo)

<img width="892" height="602" alt="Image" src="https://github.com/user-attachments/assets/f2382da0-4956-4af2-b575-9f34ded54fa2" />



## Tools used:
- ArcGIS Pro and ArcGIS Online
- Google Earth Engine
- Canva
- Flourish
