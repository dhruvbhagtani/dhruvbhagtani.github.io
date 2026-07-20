# WindBorne Application Responses

## 1. Role Preference

Applied Research, followed by Model Evaluation, then General.

## 2. ML Idea I Changed My Mind About

I initially used K-means to identify regimes linking ocean oxygen, carbon, and heat. Although it separated the data statistically, the boundaries did not align well with physically meaningful transitions. I moved to binary space partitioning to split the ocean into more interpretable regimes.

## 3. Sidequest / Initiative

Alongside my doctoral work, I contributed to scientific software efforts involving COSIMA Recipes, Oceananigans, and regional MOM6 workflows. I am now developing a side project that trains a ResNet on Oceananigans simulations to predict barotropic streamfunctions across forcing regimes.

## 4. Accuracy That Fails Forecasts

A model can reduce average error by smoothing gradients, extremes, or localized structures. I have seen this in ocean-oxygen products: some CMIP6 models agree better with observations overall because they are smoother, yet reproduce variability less realistically. Better scores can mean worse forecasts for decisions tied to extremes.

## 5. LLM Workflow

I initially used LLMs for one-off code generation, which often produced locally plausible answers without understanding the full workflow. I now use them more as coding agents: I provide the task, relevant files, constraints, and tests, then have them inspect, implement, and verify changes while I retain control of scientific validation.

## 6. Optional

Rather than a single account, I would point to the M2LInES project: https://m2lines.github.io/. Their work on scientific ML for coupled climate modeling is closely aligned with my interests in interpretable ML, ocean dynamics, and improving physical parameterizations.
