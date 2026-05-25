# Reduced-order model of disk-defect dynamics in a nematic liquid crystal

This repository contains a pedagogical toy model for the coupled dynamics of a rotating disk colloid and its companion defect in a nematic liquid crystal.

The notebook implements an effective energy landscape for the disk orientation theta and the defect sweeping coordinate s, then simulates overdamped trajectories under forced rotation and elastic relaxation.

This is a simplified model accompanying manuscript work. It is intended as a readable scientific-computing example.

## Contents

- `toy_model_disk_defect.ipynb`: main notebook
- `synthetic_elastic_relaxation_theta_s.csv`: mock data with the same structure as the experimental data
- `requirements.txt`: Python dependencies

## Data

The experimental data used in the manuscript are not included here for the moment. The CSV file provided in this repository is synthetic and only intended to make the notebook executable.

## How to run

Clone the repository:

```bash
git clone https://github.com/Claire-Dore/disk-defect-toy-model.git
cd disk-defect-toy-model