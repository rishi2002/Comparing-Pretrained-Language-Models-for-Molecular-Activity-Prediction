# Comparing-Pretrained-Language-Models-for-Molecular-Activity-Prediction
I predicted the pCHEMBL values, AlogP values, Molecular Weight and number of Lipinski's Rule of 5 Violations of a biomolecule by end-to-end training of multiple pre-trained Language models on Dopamine D2 active compounds sourced from the CHeMBL database.
<br>

• pCHEMBL represents the negative logarithm (base 10) of the standard values, pro-
viding a more balanced and standardized representation of potency across various values. It is a standardized version of the Standard Value, measuring the
molecule's bioactivity. <br>
• AlogP measures a molecule’s lipophilicity or affinity to lipids/fats versus
water. This property is crucial as it significantly influences a drug’s pharmacokinetics,
impacting its absorption, distribution, metabolism, and excretion within the body.
Compounds with balanced AlogP values are more likely to be absorbed efficiently and
exhibit favourable pharmacological characteristics.<br>
• Molecular Weight is a crucial factor in drug discovery and biopharma. It is also a
factor considered in Lipinski’s Rule of Five.<br>
• RO5 Violations The number of Lipinski’s Rule of Five violations. Lipinski’s rule
of five is a widely used rule of thumb in medicinal chemistry to evaluate drug likeness
or oral drugs.<be>
<br>
The implemented models are <br>
• RoBERTa randomly initialized, 125 million parameters <br>
• RoBERTa pre-trained, 125 million parameters<br>
• ChemBERTa pre-trained on PubChem 1M, 85 million parameters<br>
• ChemBERTa pre-trained on 10M ZINC database, 3.5 million parameters<br>
• ChemGPT pre-trained on PubChem10M Smile strings, 1.2 billion parameters<br>

Use the main.ipynb file for end-to-end training and use_pretrained.ipynb for freezing the pre-trained language model part and only training the final linear layers for regression. The chosen models can be changed in the second cell. 
