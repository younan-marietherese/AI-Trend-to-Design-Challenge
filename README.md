This project implements an end-to-end AI-powered fashion design pipeline that detects trends from product images and generates new fashion designs.

Objective

To recognize fashion trends from product datasets and automatically create new designs using generative AI.

Workflow

Data Preparation – Downloaded a fashion dataset with product images & metadata.

Trend Detection – Extracted embeddings, applied clustering to group similar looks.

Prompt Generation – Created short descriptive prompts for each cluster.

Design Generation – Generated new designs using a generative model.

Evaluation & Feedback – Scored outputs with yes/no feedback and refined weaker designs.

Final Output – Delivered a polished design per trend cluster with prompts, scores, and process logs.

Tech Stack

Python (data handling & workflow automation)

Image Embeddings & Clustering (trend detection)

Generative AI Models (design creation)

Feedback Loop (iterative refinement)

Project Structure

Trend-to-design-AI.ipynb → Main notebook with full pipeline

Outputs → Generated fashion designs & logs

Results

Meaningful fashion clusters extracted from product images.

AI-generated designs aligned with trend clusters.

Feedback-based iterative refinement improved design quality.

🤝 Acknowledgment

Developed by Marie Therese Younan as part of the Trend-to-Design AI Challenge.
