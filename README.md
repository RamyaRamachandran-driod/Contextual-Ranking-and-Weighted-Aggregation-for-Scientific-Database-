
**Note:** The original full-scale project and proprietary database are in a private repository. This public repo provides a high-level description of the framework.

## Overview
This project implements a data aggregation and ranking framework for AstroDB, an astrophysics research dataset. It combines semantic and non-semantic features to improve search relevance and provides visual analytics and time-series decomposition to understand trends and patterns in the data. It is also easily extendable to other datasets, metrics, or embedding models.

## Architecture
<img width="1672" height="941" alt="AstroRank" src="https://github.com/user-attachments/assets/600258e1-0160-428b-82d5-84ca303cf213" />

## Pipeline Components:
- **Query Processing & Metadata**: Extracts relevant metadata for weighting and alignment.
- **Embedding Generation**: Converts text to semantic embeddings (transformer-based).
- **Similarity Scorer**: Combines embeddings, neural model outputs, and semantic metadata for relevance scoring.
- **Ranking**: Aggregates 9 metrics into a final ranked list.
- **Visualization & Time-Series Decomposition**: Provides charts and trend analysis to surface insights from the aggregated data.

