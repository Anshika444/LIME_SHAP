# LIME & SHAP Model Explainability Demo

This project demonstrates **model explainability** using:
- [LIME (Local Interpretable Model-Agnostic Explanations)](https://github.com/marcotcr/lime)
- [SHAP (SHapley Additive exPlanations)](https://github.com/shap/shap)

We use the **Iris dataset** and a **RandomForestClassifier** to show:
- Local explanations with **LIME**
- Global and local explanations with **SHAP**

---

## 📂 Files
- `LimeShap.ipynb` → Main Python script for training the model and generating explanations.
- `lime_explanation.html` → LIME visualization (saved when running the script in terminal).
- `README.md` → This file.

---
LIME results will be printed in the console and saved as lime_explanation.html.

SHAP plots (summary_plot, force_plot) will open as static plots.

What You’ll See

LIME → Explains the prediction of one sample in terms of top contributing features.
SHAP Summary Plot → Shows global feature importance.
SHAP Force Plot → Explains the contribution of each feature for one prediction.
