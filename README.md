# Collective Constitutional AI
This repo contains files illustrating the data processing for the Collective Constitutional AI project. (TODO: Link blog post here).

The Jupyter notebook attached (`ccai_data_processing.ipynb`) takes
- [Pol.is](https://pol.is) export files (`comments.csv` and `participants-votes.csv`)
- A list of participant IDs to remove (`ids-to-toss.csv`) given spammy inputs (criteria described in the notebook)

And outputs `clean_comments.csv` and `clean_votes.csv` for turning into the Constitution.
