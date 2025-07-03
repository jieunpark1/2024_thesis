## Repository for M.D. of 2024
- Thesis link ➡️ [Phoneme recognition of Korean children’s English speech using self-supervised learning based domain adaptation](https://lib.hufs.ac.kr/#/search/detail/3736832?offset=1)

- Results
  ![Image](https://github.com/user-attachments/assets/95629ee7-b79f-4e59-9e23-db79c0b7f314)
---

## Code Files (uploading soon..)
### 1️⃣ fmllr 
- /mnt/hdd14/jieun/2023_ETRI_PROJECT/FMLLR_ext_materials/(set1|set2|set3|all_three_datasets) (구서버)

### 2️⃣ xvector
- /data/jieun/now_using_array/fluency_modified_two_spks_sets/set(1|2|3)/xvector_ext_model_(20|40|512)/set(1|2|3)_(advanced|intermediate|novice)_train_xvector(20|40|512).csv
- /data/jieun/now_using_array/fluency_modified_two_spks_sets/set1/real_xvec_array (신서버, 5/25)

### 3️⃣ array (instead of .wav)
- /data/jieun/now_using_array/fluency_modified_two_spks_sets/set1/real_byfluency_array (신서버, 5/22)
- csv files for making array: /data/jieun/DATA_csv/ (신서버)

### 4️⃣ model (hugging face)
- "/mnt/hdd14/jieun/2023_ETRI_PROJECT/MODEL_SAVE_dysarthric_w2v_output/20240311_k-sec_15k_+fmllr"
- 
### 5️⃣ test results
- /data/jieun/TEST_RES_dysarthric_w2v_output/0519 (신서버)

### 6️⃣ codes
- for kaldi
- ➡️ /jieun/2023_ETRI_PROJECT/2024_thesis/make_2spks_scp.py (.scp) (구서버)
- ➡️ /jieun/2023_ETRI_PROJECT/2024_thesis/make_read_fmllr.py (for read the results of fmllr - trans.1) (구서버)
- for training
- lost...😭
---
### Experimental Environment
- NVIDIA RTX A5000, RAM 24GB * 2
- NVIDIA TITAN Xp, RAM 12GB * 4
