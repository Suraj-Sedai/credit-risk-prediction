# 📖 German Credit Risk Prediction

## 🎯 Business Goal
A bank wants to **reduce loan losses** by predicting whether an applicant is likely to default.  
This enables the bank to:
- Reject risky applicants 🚫
- Approve safe ones ✅

---

## 📥 Input
- **Socio-demographics**: Age, job, marital status  
- **Financial attributes**: Credit amount, duration, savings, housing, existing credit lines  
- **Loan details**: Purpose, checking account status  

---

## 📤 Output
- **Probability of default**:  
  - `1 = default`  
  - `0 = non-default`  
- **Binary prediction** for each applicant  

---

## 📊 Success Metrics

**Primary Metric**
- **ROC-AUC** → Ranking borrowers by risk  

**Secondary Metrics**
- Precision  
- Recall  
- PR-AUC → Catching high-risk borrowers  

**Business Metric**
- Reduction in **expected default losses** while maintaining loan approvals  

---

## ⚙️ Constraints
- ❌ **No target leakage** → Only use features available at application time  
- 📝 **Model must be explainable** → Banks require justification for decisions  
- 💡 **Solution should be lightweight, reproducible, and interpretable**  

---
