# paleopresto.github.io

Paleoclimate reconstructions are among the most widely used scientific products from the paleoclimate community. They constitute statistical inference based on thousands of field and laboratory measurements: a single chart like the “Hockey Stick” temperature reconstruction of the past 1,000 years synthesizes what is known about past climate variations in a form that is easily digestible within and beyond the geosciences: in climate science of course, but also the paleogeosciences at large, and even in the social and life sciences. However, PRs are infrequently updated and commonly lag many years behind the latest data and methods. Furthermore, the lack of a central clearinghouse for PRs means that they are difficult to find. PRs also involve subjective choices that have not been exhaustively explored, and are opaque to most users. In this Catalytic Track proposal, we propose to take advantage of our experience in paleoclimate informatics to develop a Paleoclimate Reconstruction “Storehouse” (PReSto) that will 

1. Draw from the most up-to-date, curated paleoclimate data;
2. Apply an array of published methods to produce continuously-updated reconstructions; and 
3. Provide broad access via a responsive web front end, allowing to easily visualize and compare published reconstructions, investigate unexplored combinations of data and methods, and generally lower friction to develop or use PRs in research and education.

![PReSto concept][https://github.com/paleopresto/paleopresto.github.io/raw/main/PReSto_concept.png]

## Key Components

### Data

We have developed [lipdverse.org](https://lipdverse.org) as a simple source of version controlled paleoclimate datasets that supply data to PReSto reconstruction algorithms. lipdverse is open access and broadly useful beyond the PReSto project, contributing to data and methodological transparency and open science. 

#### Recommender system

### Analytical pipelines

We are building analytical pipelines that automatically update reconstructions for a handful of test cases. Starting with:

1. Data assimilation for the Common Era
2. Reconstructions of Holocene Temperature variability

Details, codebases and results for these pipelines will be updated as they come online.

### Front End

A web-based front end that provides ready access to reconstructions and data visualization is under development. Stay tuned.

### Education and outreach

Later in the project, we're planning workshops to train data stewards to properly digitize and describe paleoclimate datasets for applications such as PReSto and trainings for early-career researchers to use this cyberinfrastructure to further their scientific objectives. Furthermore, we're working to develop resources for K-12 and tribal college teachers in Northern Arizona, and design and offer one-day educational workshops for teachers throughout the region. The workshop will be centered around familiarizing teachers with PReSto, including how to use the platform to explore case-studies that place key historical junctures in the context of environmental change. 
