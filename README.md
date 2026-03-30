## ICML 2026 Rebuttal Supplementary materials


This anonymous repository provides additional results required by reviewers for our ICML 2026 Submission.


### Computation Cost Comparison

The figure below compares performance over training time. We set a fixed number of training steps and visualize the time cost for both Flow-GRPO and our TP-GRPO. TP-GRPO surpasses standard Flow-GRPO in most wall-clock time intervals and achieves a higher performance upper bound, confirming that the benefits of our short- and long-term reward modeling justify the additional sampling cost.


![time-cost-comparison](./time-cost-comparison.png)


### Additional Qualitative Comparisons

The figure below shows qualitative comparisons requested by Reviewer CQzP. These results align with Figure 5 in our paper, with evaluation scores provided below each generation (red: best; blue: second-best). Both our method (with and without the consistency constraint from Definition 5.1) consistently outperform the baseline methods.

![qualitative comparison](./qualitative-comparison.png)