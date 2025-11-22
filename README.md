
# **Mamba-CMER**

**Yiwen Tong, Jing Mu, Wenxin Chang, Huilin Zeng**
*“Mamba-CrossMod: A Multimodal Emotion Recognition Framework Based on Selective State Space Model”*

---

## **Requirements**

```
pandas==2.2.2
numpy==2.0.2
torch==2.9.0
librosa==0.11.0
seaborn==0.13.2
opencv-python==4.12.0
transformers==4.57.1
einops==0.8.1
scikit-learn==1.6.1
```

---

## **Training**

1. **Install the third-party library `mamba-ssm`:**

   ```bash
   pip install mamba-ssm
   ```

2. **Download the MOSI dataset**
   Ensure the dataset contains the following files:

   * `Raw.zip`
   * `MOSI-label.csv`
   * `aligned_50.pkl`

3. **Set the dataset path**
   Modify `data_path` in **Mamba-CMER.ipynb** to match your local dataset directory.

4. **Run the training notebook**
   Execute **Mamba-CMER.ipynb** to start training the model.

---

