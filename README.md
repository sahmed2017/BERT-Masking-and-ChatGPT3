# BERT-Masking-and-AI
Code for comparing and assessing the accuracy of BERT Masked Language Model on AI Generated and real essays.

The identification of AI generated plagiarism remains an open problem in the field of automatic essay assessment. This code explores whether MLMs (Masked Language Models) could be used to determine whether a particular essay was AI generated or not. The main question was whether bert-base-uncased would have any descrepancy in accuracy when identifying masked words in AI generated essays and real ones.

# Set-up

1. Load the bert-base-uncased model
2. Source essays. Real ones were taken from https://www.ieltsadvantage.com/2023/01/15/ielts-writing-task-2-sample-essays/ and AI generated ones from Chat GPT-3.
3. Randomly MASK 25% / 50% / 75% of the words in the essay
4. Set to 7 iterations and average the total

# Results

As the results were very similair, BERT word masking could not be used to determine whether an essay was written through AI. 

<img width="1363" alt="Screenshot 2023-06-06 at 12 28 21 AM" src="https://github.com/sahmed2017/BERT-Masking-and-AI/assets/118930981/9935291d-ce57-4c40-8eae-fcb3edb2edb3">
