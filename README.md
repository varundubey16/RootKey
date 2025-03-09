# Password Strength Classifier and Generator

flask proj with ML to classify password strength, generate secure passwords, provide password improvement suggestions, calculate password entropy(notshown) & display live password metrics using chartjs

## Requirements

- **scikit-learn**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **flask**

**Note**- app lightweight and runs completely on the CPU but slow on low end computers, reason it uses actual rock you leaked passwords (combined) extremely large dataset and hence is computationally intensive/expensive. It trains a DT classifier when the application starts
