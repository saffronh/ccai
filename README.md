# Collective Constitutional AI
This repo contains files illustrating the data processing for the Collective Constitutional AI project.

### Links:
- Collective Intelligence [blog post](https://cip.org/blog/cip-and-anthropic-launch-collective-constitutional-ai)
- Anthropic (technical) [blog post](https://www.anthropic.com/index/collective-constitutional-ai-aligning-a-language-model-with-public-input)

The Jupyter notebook attached (`ccai_data_processing.ipynb`) takes
- [Pol.is](https://pol.is) export files (`comments.csv` and `participants-votes.csv`)
- A list of participant IDs to remove (`ids-to-toss.csv`) given spammy inputs (criteria described in the notebook)

And outputs `clean_comments.csv` and `clean_votes.csv` for turning into the Constitution.

## Notes
- Group 0 here = group A in the Pol.is report (and group 1 = group B).
