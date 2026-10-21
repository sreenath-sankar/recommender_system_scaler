# Recommender system

A collaborative-filtering recommender built three ways on a user–item ratings dataset, to compare the approaches.

## Approaches

1. Item-based, Pearson correlation
2. Item-based, cosine similarity
3. Matrix factorisation with `cmfrec`

Each section covers building the model, generating top-N recommendations for a user, and discussing where the approach breaks down (sparsity, cold start).

## Files

- `rs.ipynb` — EDA and all three recommenders
- `rs.pdf` — rendered notebook

Libraries: pandas, scikit-learn, scipy, cmfrec.
