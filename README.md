
**Note:** The original full-scale project and proprietary database are in a private repository. This public repo provides a high-level description of the framework.

## Overview
This project implements a data aggregation and ranking framework for AstroDB, an astrophysics research dataset. It combines semantic and non-semantic features to improve search relevance and provides visual analytics and time-series decomposition to understand trends and patterns in the data. It is also easily extendable to other datasets, metrics, or embedding models.

## Architecture
<img width="1672" height="941" alt="AstroRank" src="https://github.com/user-attachments/assets/600258e1-0160-428b-82d5-84ca303cf213" />

## Impact

The system successfully reordered search results using structured signals, surfacing more authoritative papers that pure semantic search ranked lower. 
- Achieved consistent convergence with a final validation MSE of 0.0812, demonstrating solid generalization.
- An adaptive weight-update mechanism further refined feature importance over time, with high-signal features gaining influence and low-signal ones naturally decaying.
- Applied to astronomical literature, the system derived a confidence-weighted consensus estimate which proved to be very reliable.
