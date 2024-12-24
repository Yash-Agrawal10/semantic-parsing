# Seq2Seq Model Reimplementation: Language to Logical Form with Neural Attention

This project reimplements the Seq2Seq model described in the paper **"Language to Logical Form with Neural Attention"** by Li Dong and Mirella Lapata.

The model takes in a general natural language sentence and produces a sequence that is easily machine-interpretable. It implements an LSTM-based encoder-decoder architecture with attention.

---

## Hyperparameters

- `src_embed_size`: 150  
- `tgt_embed_size`: 150  
- `hidden_size`: 150  
- `num_layers`: 1  
- `dropout`: 0.3  

---

## Results

- **Number of Epochs**: 20  
- **NLL Loss**: 0.854  
- **Per-token Accuracy**: 88.2%  
- **Exact-match Accuracy**: 76.4%  

---

## Video Link

https://drive.google.com/file/d/1btaLx7e4NP_XFREM8dOWS7NJIAjti8jY/view?usp=sharing

