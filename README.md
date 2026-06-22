# GG-Boost-Foundation-Model-Embeddings-for-Immunotherapy-Response-Prediction
Foundation Embeddings for Immunotherapy Response Prediction: Improving Cross-Cancer Generalization of ICI Response Prediction Using Pretrained Cell Embeddings.

This was an research project by myself and @yasnaj. I contributed the GenePT files.

We developed GG-Boost, a computational pipeline for predicting patient response to immune checkpoint inhibitor therapy from single-cell RNA sequencing data, improving on the PRECISE framework (Pinhasi & Yizhak, 2025). Raw gene expression features were replaced with pretrained foundation model embeddings from Geneformer and GenePT as input to an XGBoost classifier to evaluate whether shared embedding spaces improve cross-cancer generalizability over raw expression features. We conducted cross-cancer transfer of GG-Boost to an independent basal cell carcinoma (BCC) cohort, finding that GenePT embeddings outperformed PRECISE's 11-gene signature baseline.
