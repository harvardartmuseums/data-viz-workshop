# Workshop recap:

- What data do museums have?
-  Data about objects
-  -   Dates, titles, processed data like colors...
 - Data about data
  - Who entered a data point and when, how complete is a record...
 - Data about related entities
  - Artists' birth and death dates, places' latitudes and longitudes...
 - Data about the museum itself
  - Building data, visitor data...

- What kinds of data can't we share?
 - Data impacting privacy
 - Data impacting the museums' security
 - Data we don't have&mdash;all data comes from research

- How do we distribute the data we can share?
 - Our public-facing API
  - Request your own key here: [http://www.harvardartmuseums.org/collections/api](http://www.harvardartmuseums.org/collections/api)
  - Read more about how to format requests here: [https://github.com/harvardartmuseums/api-docs](https://github.com/harvardartmuseums/api-docs)
 - Interfaces we've built on the API&mdash;like our collections search [http://www.harvardartmuseums.org/collections](http://www.harvardartmuseums.org/collections)

- What is an API?
 - A communication tool between computers
  - Your computer asks ours for information about the collections
  - Ours sends information back in a predetermined format

- What are some examples of projects you can build with our API?
 - Art Explorer
  - Enables user to view data related to collections objects in various ways, including color, activity (pageviews, etc.), and face recognition data
  - View: [http://apps.harvardartmuseums.org/art-explorer/](http://apps.harvardartmuseums.org/art-explorer/)
  - Source: [https://github.com/harvardartmuseums/art-explorer](https://github.com/harvardartmuseums/art-explorer)
 - Spectrum Explorer
  - Enables user to view museums' date-specific color, both for today and scheduled out into the past and future
  - View: [http://apps.harvardartmuseums.org/spectrum-explorer/](http://apps.harvardartmuseums.org/spectrum-explorer/)
  - Source: [https://github.com/harvardartmuseums/spectrum-explorer](https://github.com/harvardartmuseums/spectrum-explorer)
 - Museum Explorer
  - Enables user to browse object data by location within the museums
  - View: [http://apps.harvardartmuseums.org/museum-explorer/](http://apps.harvardartmuseums.org/museum-explorer/)
  - Source: [https://github.com/harvardartmuseums/museum-explorer](https://github.com/harvardartmuseums/museum-explorer)
 - Suns Explorer
  - Displays title and artistically presented color data for randomly selected objects in the collection
  - View: [http://apps.harvardartmuseums.org/suns-explorer/](http://apps.harvardartmuseums.org/suns-explorer/)
  - Source: [https://github.com/harvardartmuseums/suns-explorer](https://github.com/harvardartmuseums/suns-explorer)
 - Solar Systems
  - Displays collections of objects sorted by classification, year, etc., as solar systems, with subcategories as orbiting planets of various sizes
  - Source: [https://github.com/harvardartmuseums/Viz-CollectionSolarSystems](https://github.com/harvardartmuseums/Viz-CollectionSolarSystems)
  - To view, open with Processing ([https://processing.org/](https://processing.org/)) 
 - The Clock
  - Displays data about the collections in an abstract and visually compelling manner
  - View video of project in operation: [https://vimeo.com/154085159](https://vimeo.com/154085159)
  - Source: [https://github.com/harvardartmuseums/theClock](https://github.com/harvardartmuseums/theClock)
  - To view, open with Processing ([https://processing.org/](https://processing.org/))  
 - Exquisite IIIF Corpse
  - Uses IIIF to produce jumbled images composed of strips of images in the collections
  - View: [https://exquisite-iiif-demo.herokuapp.com/corpse](https://exquisite-iiif-demo.herokuapp.com/corpse)

- How can you get started on a project using our API?
 - Get set up with the API
  - Request your own key here: [http://www.harvardartmuseums.org/collections/api](http://www.harvardartmuseums.org/collections/api)
  - Read more about how to format requests here: [https://github.com/harvardartmuseums/api-docs](https://github.com/harvardartmuseums/api-docs)
 - Start testing API queries with a modified Suns Explorer app
  - [http://apps.harvardartmuseums.org/suns-JSON-viewer/index.html](http://apps.harvardartmuseums.org/suns-JSON-viewer/index.html)
 - Use our projects as a starting point
  - [https://github.com/harvardartmuseums](https://github.com/harvardartmuseums)


 
# Resources:

- API links
 - Request a key: [http://www.harvardartmuseums.org/collections/api](http://www.harvardartmuseums.org/collections/api)
 - Documentation: [https://github.com/harvardartmuseums/api-docs](https://github.com/harvardartmuseums/api-docs)

- Suns Explorer with an API query editor and sample JSON viewer
 - [http://apps.harvardartmuseums.org/suns-JSON-viewer/index.html](http://apps.harvardartmuseums.org/suns-JSON-viewer/index.html)

- Harvard Art Museums Projects discussed
 - Art Explorer: [http://apps.harvardartmuseums.org/art-explorer/](http://apps.harvardartmuseums.org/art-explorer/)
 - Spectrum Explorer: [http://apps.harvardartmuseums.org/spectrum-explorer/](http://apps.harvardartmuseums.org/spectrum-explorer/)
 - Museum Explorer: [http://apps.harvardartmuseums.org/museum-explorer/](http://apps.harvardartmuseums.org/museum-explorer/)
 - Suns Explorer: [http://apps.harvardartmuseums.org/suns-explorer/](http://apps.harvardartmuseums.org/suns-explorer/)
 - Solar Systems: [https://github.com/harvardartmuseums/Viz-CollectionSolarSystems](https://github.com/harvardartmuseums/Viz-CollectionSolarSystems)
 - The Clock: [https://vimeo.com/154085159](https://vimeo.com/154085159)
 - Exquisite IIIF Corpse: [https://exquisite-iiif-demo.herokuapp.com/corpse](https://exquisite-iiif-demo.herokuapp.com/corpse)
 - Sources for these and other projects: [https://github.com/harvardartmuseums](https://github.com/harvardartmuseums)

- External examples
 - A visualization of cultural capitals as represented by birth and death places of notable figures
  - [https://www.fastcodesign.com/3033877/infographic-of-the-day/the-history-of-cultural-migration-mapped](https://www.fastcodesign.com/3033877/infographic-of-the-day/the-history-of-cultural-migration-mapped)
 - The Rijksmuseum's highres images and metadata available through Rijksstudio
  - [https://www.rijksmuseum.nl/en/rijksstudio](https://www.rijksmuseum.nl/en/rijksstudio)
 - A visualization of the different dimensions of objects in the Tate Britain
  - [http://www.ifweassume.com/2013/11/the-dimensions-of-art.html](http://www.ifweassume.com/2013/11/the-dimensions-of-art.html)
 - A list of other museums' APIs
  - [http://museum-api.pbworks.com/w/page/21933420/Museum%C2%A0APIs](http://museum-api.pbworks.com/w/page/21933420/Museum%C2%A0APIs)

- Relevant tools
 - Processing: [https://processing.org/](https://processing.org/)
 - D3: [https://d3js.org/](https://d3js.org/)
 - JSON validator and formatter: [http://pro.jsonlint.com/](http://pro.jsonlint.com/)
 - Postman REST client/API tester: [https://www.getpostman.com/](https://www.getpostman.com/)
