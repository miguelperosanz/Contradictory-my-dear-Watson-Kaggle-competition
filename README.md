# Contradictory-my-dear-Watson-Kaggle-competition

This is the code that I used for the Kaggle competition "Contradictory - my - dear - Watson".

It is a NLP competition where given two sentences "premise" and "hypothesis" in different languages and you have to figure out if they are contradictory, neutral or entailment. The best option is using the "joeddav/xlm-roberta-large-xnli" pretrained model, already pretrained for this task (called NLI = 
Natural Language Inference), in different languages. 
What I tried:

1) I used the pretrained model directly, without using the training data given by kaggle, achieving a 92% of accuracy.
2) I tried to use tensorflow for transfer learning fine tuning using the training data given by kaggle. I tried to run it locally on my GPU, which was impossible 
because I was running out of memory all the time, in the end I could not compare to the accuracy of system 1). A TPU is recommended for this task (kaggle notebook). However, the TPU unit from Kaggle is usually busy too.
