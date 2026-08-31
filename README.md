# INFO664: Datasets Exploration


## [The Metropolitan Museum of Art Open Access CSV] (https://www.metmuseum.org/hubs/open-access)
The Met museum has come under scrutiny in recent years for their lack of addressing how Native American artists and artworks are represented throughout the collection. While there is definitely room for improvement nationwide for documentation of indigenous communities, practices, artists and artworks, many of the inconsistencies and losses of information we see today are due to the long history of colonization and active efforts to erase their histories. The terms and names currently used throughout the Met's collection are often phrased in funny ways due to varying levels of certainty. 

I want to use the Met API to observe the terms and languages used to describe indigenous art and artists of North America throughout their collection. How many objects in the collection represent indigenous artists and communities? What North American tribes and communities are represented? What terms are used to describe them? Are there any that standout as outliers? Using sources like Native Governance Center Terminology Style Guide, guidance from the University of British Columbia Indigenous Knowledge Organization Guide, and other sources. 

## [NYPL] (https://github.com/NYPL-publicdomain/data-and-utilities#items)
I am particularly interested in the Billy Rose Theater Division and its collections.

### Collections included in collections.csv from Billy Rose Theater Division:
1. Billy Rose Theatre Collection photograph file (2589a880-c52c-012f-2cb4-58d385a7bc34)
2. Billy Rose Theatre Division scrapbooks (45013f40-c555-012f-c94a-3c075448cc4b)
3. Billy Rose Theater Collection clipping file (2e21da80-c608-012f-bfe9-58d385a7bc34)
4. Billy Rose Theatre Collection scripts (3bac87f0-c616-012f-383b-58d385a7bc34)
5. Billy Rose Theatre Division cabinet file (c6de8d10-c62a-012f-20bb-58d385a7bc34)
6. Billy Rose Theatre Collection program file (cbe6b360-c6c2-012f-6462-58d385a7bc34)
7. Billy Rose Theatre Collection Iconography file (e629bfc0-c6cb-012f-92cd-3c075448cc4b)
8. Billy Rose Theatre Division posters (a123ed80-9a3f-0130-3e73-58d385a7b928)
9. Billy Rose Theatre Division book file (4a455820-d761-0130-968a-58d385a7bbd0)
10. Billy Rose Theatre Division periodicals file (5e5490e0-2bd3-0132-f353-58d385a7b928)

Despite all of these Collection UUIDs being included in the CSV, here is very little included in the Digital Collections from this Division. This is likely not useful for my interests. and there is not enough data to build something out of it.

## [Whitney Museum of American Art] (https://whitney.org/open-access)
### Artists
The Artists CSV from the Whitney museum contains names, Begin Dates (assuming birth), End Dates (assuming death dates), Getty ULAN IDs, and WikiData IDs. These IDs allow my the chance to bring in data from those sources and look other information when present like where they wre born and died.

The Whitney Museum of American Art contains artworks by artists who were born all over the world, hold a variety of different citizenships, and come to the collection for a variety of reasons. If I choose to investigate this dataset, I would want to explore how diverse the artists within their collection are. In a time where the definition of what it means to be American is so heavily contested through a culture war that is affecting the interpretation of American identity, and growing political extremism, I want to use their Artists dataset to investigaste the Whitney's interpretation of what is American Art.

Information like birth location and death location of the artist can be easily found through Getty ULAN and WikiData, but information such as their parents, when they resided or worked within the United States and how long they were in the United States, and public citizenship information will be harder to find. Following through with this dataset will require a lot of additional relevant datasets to round it out and make it usable. 

### Artworks
Similarly, The Artworks CSV can be observed for a multitide of angles to examine what American Art means to the Whitney Museum. 