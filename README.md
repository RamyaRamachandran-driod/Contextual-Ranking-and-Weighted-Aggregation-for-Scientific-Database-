
**Note:** The original full-scale project and proprietary database are in a private repository. This public repo provides a high-level description of the framework.

## Overview
This project implements a data aggregation and ranking framework for AstroDB, an astrophysics research dataset. It combines semantic and non-semantic features to improve search relevance and provides visual analytics and time-series decomposition to understand trends and patterns in the data. It is also easily extendable to other datasets, metrics, or embedding models.

## Architecture
[![](https://github.com/[RamyaRamachandran-driod]/[C]/blob/[branch]/image.jpg?raw=true)](https://github.com/RamyaRamachandran-driod/Contextual-Ranking-and-Weighted-Aggregation-for-Scientific-Database-/blob/main/AstroRank.png)


## Pipeline Components:
- **Query Processing & Metadata**: Extracts relevant metadata for weighting and alignment.
- **Embedding Generation**: Converts text to semantic embeddings (transformer-based).
- **Similarity Scorer**: Combines embeddings, neural model outputs, and semantic metadata for relevance scoring.
- **Ranking**: Aggregates 9 metrics into a final ranked list.
- **Visualization & Time-Series Decomposition**: Provides charts and trend analysis to surface insights from the aggregated data.

