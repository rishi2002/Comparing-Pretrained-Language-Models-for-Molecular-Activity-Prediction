# Comparing-Pretrained-Language-Models-for-Molecular-Activity-Prediction
I predicted the pCHEMBL values, AlogP values, Molecular Weight and number of Lipinski's Rule of 5 Violations of a biomolecule by end-to-end training of multiple pre-trained Language models on Dopamine D2 active compounds sourced from the CHeMBL database.

I predict the following properties:
• pCHEMBL represents the negative logarithm (base 10) of the standard values, pro-
viding a more balanced and standardized representation of potency across various values. It is a standardized version of the Standard Value, measuring the
molecule's bioactivity. <br>
• AlogP measures a molecule’s lipophilicity, or its affinity to lipids/fats versus
water. This property is crucial as it significantly influences a drug’s pharmacokinetics,
impacting its absorption, distribution, metabolism, and excretion within the body.
Compounds with balanced AlogP values are more likely to be absorbed efficiently and
exhibit favourable pharmacological characteristics.<br>
• Molecular Weight is a crucial factor in drug discovery and biopharma. It is also a
factor considered in Lipinski’s Rule of Five.<br>
• RO5 Violations The number of Lipinski’s Rule of Five violations. The Lipinski’s rule
of five is a widely used rule of thumb in medicinal chemistry to evaluate drug likeness
or oral drugs.<br>
