# Reddit Cartography

![Visaualisation](visualisation/exports/RedditCartography.png)

## Project Description

This project aims to map and analyze the relationships between various Reddit communities (subreddits) by using scraping techniques and the Reddit API. The goal was to understand how different subreddits are interconnected through shared users. We analyzed the top 1000 subreddits and visualized the data using the GEPHI software, allowing us to uncover distinct communities and trends. This work was conducted as part of the IC05 course (Critical Analysis of Digital Data) at the University of Technology of Compiègne (UTC).

## Installation Instructions

To set up this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/reddit-mapping.git
   ```

## Data Collection Methodology

The dataset for this project was collected using one approach:

1. **Reddit API:** To manage a large dataset, we also accessed Reddit’s API to extract subreddit-user relationships. Despite limitations imposed by the Reddit API (rate limits), we gathered extensive data, amounting to 471,000 subreddit-user links across 100 subreddits.

For more details on the scraping process and API limitations, refer to our [Final Report (Fr)](Rapport_Projet_Reddit.pdf).

## Code Structure

The project is organized as follows:

- `CSV_SubReddit/`: Collected raw data about Subreddit users
- `liens_noeuds/`: Processed CSV with link and node for GEPHI 
- `Visualization/`: Graphs and visual outputs generated using GEPHI

## Visualization

We visualized the subreddit relationships using GEPHI. The visualizations were designed to highlight the main subreddit communities, such as gaming, memes, tech news, and NSFW content. The ForceAtlas2 algorithm was employed to structure the graphs, with color coding based on modularity to distinguish different community clusters.

Some of the key visualizations:
- [Top 500 Subreddits Map](visualisation\exports\RedditCartography.png)


## Results and Evaluation

The primary findings of the project reveal four main communities on Reddit:
- **Gaming/Pop Culture**
- **Memes**
- **Tech News**
- **NSFW**

We observed a strong centralization around the top subreddits and discovered significant interconnections between these communities.

For more detailed results, please refer to our [Final Report](Rapport_Projet_Reddit.pdf).
For see visualisation in High Quality, please free to contact us. 

## Contributors

- Samuel Manchajm
- Julien Pontoire
- Gaspard Petri
- Quentin Fouinat--Beal

## License

This project is released under the [MIT License](https://choosealicense.com/licenses/mit/). 

For questions or suggestions, feel free to contact us!

