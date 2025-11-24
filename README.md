# iclr-insights

Insights from the ICLR Peer Review and Rebuttal Process

This is the repository for the paper: [https://arxiv.org/pdf/2511.15462](https://arxiv.org/pdf/2511.15462)

* 20 Nov. 2025: ~~Data~~ and code will be updated in the next couple of days.
* 24 Nov. 2025: Data is uploaded!

## Data

We use all the data we captured for ICLR 2024 and 2025 from [./dataset](./dataset/). Some reviewers changed their scores multiple times during the review process. Initially, we did not capture individual reviewer identities in daily snapshots; however, their scores (rating, confidence, presentation, and more) are more than enough to reconstruct reviewer profiles. We mark reviewers that we are confident about with a Tracing Score.

Tracing Score is the metric we use to track reviewer continuity over time:

* ≤ 1: Valid to use.
* ≥ 2: You should double-check these. Our manual audit shows that even those ≥ 2 are generally valid. 

Score interpretation:

* -1: No changes at all between pre- and post-rebuttal profiles.
* 0: Reviewer profile (excluding overall rating) remained unchanged across days.
* 1: Minor differences accumulated, but still a reliable match.
* ≥ 2: Multiple differences in the review profile across days. This only affects a small portion of the dataset. Please double-check before using them.
