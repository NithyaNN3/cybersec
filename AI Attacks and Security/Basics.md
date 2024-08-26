## AI Systems
- Basic idea is that AI Systems has data + model = prediction/actionable insights
- **Loss functions** to validate if a given inference is correct. Adjust weights accordingly if it's not so that the same model can be used for unlabeled data (e.g. predicting images, etc)

### ML as a service
- Like Amazon S3 that holds data for training an ML model which can then be deployed for on a Cloud service

## Attacks
Data poisoning during training phase - by inserting malicious data during the training phase, into clean data

### Types of Attacks
 1. Evasion Attacks - malicious noise insertion skews results. This allows attackers to evade. This is after the training phase
 2. Poisoning Attacks - poisoning the ML model itself
 3. Backdoor Attacks - injection of a "trigger" from the backdoor

## Defense methods
1. **Before Training** - distillation of data by removing potential perturbations before training the model; regenerating clean data instead of removing the suspicious parts
2. **During Training** - Architecture optimisation; Attention mechanism (reduce impact of malicious data); Adversarial training (injecting adverse data so that the model is aware of it beforehand); Robustness certification (certify that the model can handle adversity)
3. **After Training** - Machine unlearning (a forgetting mechanism)


