# public-tree-map

Public Tree Map uses open datasets to document publicly owned park + street + landmark trees in Santa Monica, California. Please see below for more information about the data sources and project.

We primarily use:
- Node.js
- React + Foundation
- SQLite

## Protocol for pull requests + code review

- Please review open issues and link your pull request to the relevant issue.
- Please create new branch!
- In your pull request, please list and explain all proposed changes to the code base (additions, deletions). If you reuse code from elsewhere, please make sure you've attributed it.
- Please apply all relevant labels to your pull request.
- Please request a review (either from a specific person or from the slack channel).
- Reviewers: please review all proposed changes, write comments and questions in line notes. Please review all updates made at your request.
- Reviewer and requester: please confirm with each other that the PR is ready to merge. Please make sure that the PR branch name documents the new changes.

## Running locally

Running this requires Node.js and [yarn](https://yarnpkg.com/en/docs/install).

1. Install the Javascript requirements:

```bash
yarn install
```

2. Build the project and start the server:

```bash
yarn start
```

3. Navigate to `localhost:5000` in your browser.

**Optional**: Run `yarn watch` to automatically compile the javascript
whenever a file changes.

## Related projects/inspiration
- [A Very Detailed, Interactive Map of Chicago’s Tree Canopy (Atlas Obscura)](https://www.atlasobscura.com/articles/chicago-tree-canopy-map-2017)
- [Arnold Arboretum map explorer](https://arboretum.harvard.edu/explorer/?utm_source=topnav&utm_medium=nav&utm_campaign=top-menu-map)
- [Canopy](https://github.com/seeread/canopy) and descriptive [blog post](http://www.datakind.org/projects/out-on-a-limb-for-data) from DataKind
- [Canopy Tree Plotter](https://pg-cloud.com/Canopy)
- [The effects of urban trees on air quality - USDA 2002 PDF](https://www.nrs.fs.fed.us/units/urban/local-resources/downloads/Tree_Air_Qual.pdf)
- [i-Tree](https://www.itreetools.org/)
- [Increased home size and hardscape decreases urban forest cover in Los Angeles County’s single-family residential neighborhoods PDF](http://johnwilson.usc.edu/wp-content/uploads/2018/03/Increased-home-size-and-hardscape-decreases-urban-forest-cover-in-Los-Angeles-Countys-single-family-residential-neighborhoods.pdf)
- [Jill Hubley's NYC street tree map](https://github.com/jhubley/street-trees)
- [Melbourne - Urban Forest Visual](http://melbourneurbanforestvisual.com.au/)
- [Minimum Requirements for an Arborist Report - City of Atlanta PDF](https://www.atlantaga.gov/home/showdocument?id=20151)
- [NYC Parks' New York City Street Tree Map](https://tree-map.nycgovparks.org/)
- [The Need to Standardize At-planting Data PDF](https://urbanforestry.indiana.edu/doc/publications/2015-need-to-standardize.pdf)
- [Pasadena Beautiful Foundation's Endangered Trees List](http://www.pasadenabeautiful.org/green-links/endangered-trees-list/)
- [Rancho Santa Ana Botanic Garden - app (Guru LLC)](https://itunes.apple.com/us/app/rancho-santa-ana-botanic-garde/id1389785599?mt=8)
- [RegisTree](http://www.vision.caltech.edu/registree/)
- [Santa Monica's Top 15 Tree Speices PDF (2010)](http://csmgisweb.smgov.net/docs/mapcatalog/trees.pdf)
- [TreeMapLA](https://www.opentreemap.org/latreemap/map/)
- [Urban Tree Growth & Longevity (UTGL) Working Group - Urban Tree Monitoring Protocols Field Guide](http://www.urbantreegrowth.org/field-guide.html)
- [West Coast Arborists (WCA)](https://westcoastarborists.com/services) - see the description of ArborAccess, WCA's GPS tree inventory service for their clients
- [We calculated how much money trees save for your city - The Conversation](http://theconversation.com/we-calculated-how-much-money-trees-save-for-your-city-95198)
