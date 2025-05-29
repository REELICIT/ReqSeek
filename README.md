# Replication Package for **ReqSeek: Transformer-Based Automatic Requirements Identification for Building Large Requirements Datasets**

📄 **Usage Restriction Prior to Paper Publication**  
This repository is provided solely as a replication package for the peer review process.
**Do not use, modify, or redistribute any content until the paper is officially published.** After publication, this repository will be archived on Zenodo with an open license.  

--- 

## Summary  
This replication package supports our paper titled: **ReqSeek: Transformer-Based Automatic Requirements Identification for Building Large Requirements Datasets**, which introduces a transformer-based approach (ReqSeek) for automatically identifying requirements in textual data. Many deep-learning methods require large datasets, but collecting labeled requirements data is challenging. Our work aims to facilitate the creation of large-scale requirements datasets for training AI models.

---


## Repository Content  
1. **[`datasets/`](./datasets/)**  
   - Contains our curated requirements datasets. 
   - Includes a tutorial on how to load and use them. 
   - 🔒 All datasets (`ARID`, `SwaRD`, `BLINDED-DATASET`) are currently shared exclusively using HotCRP submission portal for peer review.
   - 📢 We will **make them publicly available; open-source,** after the peer-review process is complete.

2. **[`ReqSeek/`](./ReqSeek/)**  
   - This is the ReqSeek model, it is our fine-tuned best-performing model (for more details refer to the paper)

   - [`using_reqseek.ipynb`](./using_reqseek.ipynb): This notebook demonstrates how to download and use `ReqSeek.`
   - **Note**: To run `ReqSeek` you might need GPU power

3. **[`RQ1/`](./RQ1/)**  
   - Setup, experiments, and evaluation for Research Question 1.  

4. **[`RQ2/`](./RQ2/)**  
   - Setup, experiments, and evaluation for Research Question 2.  

5. **[`RQ3/`](./RQ3/)**  
   - Setup, experiments, and evaluation for Research Question 3.  

6. **[`RQ4/`](./RQ4/)**  
   - Setup, experiments, and evaluation for Research Question 4.  

7. **[`RQ5/`](./RQ5/)**  
   - Setup, experiments, and evaluation for Research Question 5.  

---

## 🔒 License  
Copyright © REELICIT, 2025. All rights reserved.  
**Strictly no use, modification, or distribution permitted until paper publication.**  
Post-publication, this repository will be archived on Zenodo under an open license.  

---

For questions, contact the authors.  
*This replication package is for peer review only.*
>>>>>>> 504726b (initial commit)
