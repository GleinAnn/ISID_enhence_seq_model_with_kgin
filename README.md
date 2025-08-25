# ISID_enhence_seq_model_with_kgin

Recommender systems play a crucial role in helping users navigate the vast amount of digital content. While sequential recommendation models (e.g., SASRec, BERT4Rec, FEARec) effectively capture temporal user behaviors, they often lack semantic context that could enrich or explain preferences. Knowledge Graphs (KGs) provide this missing piece by modelling items, entities, and relations, but integrating them with sequential models remains challenging.

This project introduces KGIN (Knowledge Graph-based Intent Network), a framework that enhances sequential recommendation by combining temporal dynamics with knowledge-aware reasoning. KGIN captures latent user intents through multi-hop relational paths in the KG and fuses them with sequential models via a late fusion strategy, allowing both components to independently contribute to user preference modelling.

Key Features:
- Hybrid framework: Combines sequential models with knowledge graph reasoning.
- Improved performance: Outperforms baseline sequential recommenders on benchmark datasets (MovieLens, Amazon-Books, LastFM-1b).
- Explainability: Provides interpretable insights via intent–relation patterns and semantic paths.

Dataset: https://drive.google.com/drive/folders/1s1tWk_Ha7x9xk1BELCtz3dRN3aCsu1aV?usp=drive_link
