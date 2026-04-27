

# Machine Learning Module — E-Portfolio

**University of Essex Online | MSc Artificial Intelligence**
Module: Machine Learning — Resubmission, April 2026

## About this submission

The original submissions for this module were capped at 50% on resubmission following a missed extenuating circumstances deadline. The resubmission consists of three new pieces of work covering different families of machine learning algorithms — supervised CNN classification on MNIST, and unsupervised k-means clustering on Airbnb listings — and a reflective piece on the module experience. This portfolio focuses on these deeper deliverables.

## Reflective Piece

[Reflective piece (PDF)](./pdf/reflection.pdf) — reflection on the resubmission process and module learning.

## Unit 6 — Airbnb Segmentation

A k-means clustering analysis of 48,895 NYC Airbnb listings, identifying four behavioural host segments. The analysis defends a k=4 choice over the higher-silhouette k=3 because it isolates a small but strategically important commercial-operator segment, and adds a chi-square test with Cramér's V to separate statistical significance from effect size.

- [Analytical report (PDF)](./pdf/airbnb-segmentation-report.pdf)
- [Notebook (.ipynb)](./pdf/airbnb-segmentation.ipynb)

## Unit 11 — MNIST CNN

A convolutional neural network for handwritten digit recognition reaching 99.01% test accuracy. The work covers architectural reasoning (why filter count grows with depth, why 3×3 filters, why ReLU, why softmax with sparse categorical cross-entropy), and identifies a mild overfitting trend after epoch 5.

- [Presentation (PDF)](./pdf/mnist-presentation.pdf)
- [Transcript (PDF)](./pdf/mnist-essay-transcript.pdf)
- [Notebook (.ipynb)](./mnist-cnn.ipynb)

## Unit 6 vs Unit 11 — Methodological Evaluation

The two pieces cover different algorithm families and audiences. The Airbnb work is unsupervised — there is no ground truth for what makes a host commercial vs casual, so the segmentation has to make that distinction emerge from behavioural features. The MNIST work is supervised, with clear ground truth, and the methodological discipline is in architecture justification rather than category construction.

What the two pieces share is the habit of saying what the result actually means. The Airbnb segmentation does not claim to have discovered a bimodal market — it presents four behavioural segments, defends the choice of k, and triangulates its findings against prior literature (Wachsmuth and Weisler, 2018). The MNIST work does not claim 99% accuracy means computer vision is solved — it reframes the result in terms of dataset difficulty and identifies where the remaining errors cluster. The progression between the two pieces is in this methodological discipline rather than in the algorithms themselves.

## Skills Matrix and Development Plan

Self-assessment (1 = limited, 5 = strong):

| Skill | Pre-Module | Post-Module | Evidence |
|---|---|---|---|
| Critical thinking and analysis | 4 | 5 | Defending k=3 vs k=4 trade-off; reasoning about CNN architecture |
| Communication and Literacy | 4 | 5 | Executive-audience writing in Airbnb report; structured MNIST transcript |
| IT and Digital | 5 | 5 | TensorFlow/Keras CNN; pandas/scikit-learn pipeline |
| Numeracy | 3 | 4 | Chi-square, Cramér's V, architecture parameter reasoning |
| Research | 3 | 4 | Literature review (Wachsmuth & Weisler, 2018); methodological triangulation |
| Critical Reflection | 3 | 4 | Reflective piece; identifying patterns of academic engagement |
| Time management | 2 | 3 | Resubmission completed within window |
| Ethical Awareness | 3 | 4 | Regulatory/housing-affordability framing in Airbnb work |
| Problem-solving | 4 | 5 | Trade-off documentation; methodological honesty |
| Teamwork | 3 | 3 | Limited engagement with team component |

Three priorities going forward:

1. **Deeper engagement with collaborative work.** The team component of this module was not engaged with actively. In future modules, treat team components as central rather than as overhead.
2. **Methodological honesty as a habit.** Defending trade-offs explicitly and separating significance from effect size — apply the same discipline to dissertation work and to professional infrastructure proposals.
3. **Process discipline around academic deadlines.** EC dates and major deadlines as standing calendar items, not exception cases.

## Module Learning Outcomes

**LO1 — Articulate the legal, social, ethical and professional issues faced by ML professionals.** Evidenced through the Airbnb report's framing around NYC Local Law 18 and housing affordability, and reflective acknowledgement of how the dataset's age affects contemporary policy use.

**LO2 — Understand the applicability and challenges associated with different datasets.** Evidenced through the MNIST essay's framing of 99.01% accuracy in the context of dataset difficulty, and the Airbnb report's acknowledgement of the post-2023 regulatory shift.

**LO3 — Apply and critically appraise ML techniques to real-world problems.** Evidenced through defending the k=3 vs k=4 trade-off, adding chi-square and Cramér's V, identifying the overfitting trend in MNIST training curves, and architectural reasoning in the CNN essay.

**LO4 — Skills required to be effective in a development team.** Evidenced through reflective recognition that the team component was not engaged with actively, and the commitment to participate fully in future team components.
