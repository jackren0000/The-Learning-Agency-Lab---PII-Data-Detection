# The Learning Agency Lab - PII Data Detection

## Overview

The Learning Agency Lab, in partnership with Vanderbilt University, is hosting a Kaggle competition to tackle the challenge of detecting personally identifiable information (PII) in educational data. The objective is to develop automated techniques that can accurately identify and remove PII, facilitating the release of educational datasets without compromising student privacy.

## Goal

Participants are tasked with creating models capable of detecting PII within student writings. The competition aims to reduce the cost and improve the scalability of making educational datasets available for research, which is currently hindered by the risks associated with exposing student PII.

## Timeline

- **Start Date**: January 17, 2024
- **Entry Deadline**: April 16, 2024
- **Team Merger Deadline**: April 16, 2024
- **Final Submission Deadline**: April 23, 2024

All deadlines are at 11:59 PM UTC.

## Evaluation

Submissions will be evaluated based on the micro Fβ score, with a β value of 5, emphasizing the importance of recall in the model performance.

## Submission Guidelines

- Predictions must only include positive PII labels.
- Submissions must be made through Notebooks with the following conditions:
  - CPU Notebook <= 9 hours run-time
  - GPU Notebook <= 9 hours run-time
  - Internet access disabled
  - Use of publicly available external data and pre-trained models is allowed
  - Submission file must be named `submission.csv`

## Efficiency Prize Evaluation

A secondary track focuses on model efficiency. Submissions for this track are judged on runtime and predictive performance, and must meet certain eligibility criteria to qualify for the Efficiency Prize. The objective is to minimize the efficiency score, which is a composite of the model's Fβ score and runtime.

For more information on the competition, including rules, data, discussion forums, and leaderboard updates, visit the [Kaggle competition page](https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data).
