# Task C — Research Reflection

> **BAFAD Accelerated Research Track · Fall 2026**
> Complete **after** finishing Tasks A and B.

---

## Instructions

Write your responses directly in this file (replace the placeholder text).
Aim for **150–200 words total** across both questions.
Be specific — reference your actual experience with the data and code.

---

## Question 1 — Connecting the Work to Research

*After completing Tasks A and B, how does hands-on data exploration relate to the research problem described in **Anomaly Detection in Tactical Sensor Streams** (the document you read before the Canvas quiz)?*

Consider: What patterns did you observe in the SMAP data? How might those patterns complicate or inform the design of an autoencoder-based anomaly detector?

**Your response (75–100 words):**

Completing Tasks A and B helped me understand how data exploration connects to anomaly detection. In the SMAP data, I noticed that the channels did not all behave the same and that some values had different ranges and distributions. These differences could make anomaly detection more difficult because unusual behavior in one channel may be normal in another. An autoencoder-based model would need to learn these normal patterns first so it can recognize when new data behaves differently from what is expected.

---

## Question 2 — Self-Assessment of Readiness

*What specific gaps in your current knowledge — Python skills, statistics concepts, or ML background — do you expect to encounter if you join the research group? What is your plan for addressing them?*

Be honest. There are no wrong answers — this helps us plan the onboarding schedule.

**Your response (75–100 words):**

I still have areas to improve in Python, statistics, and machine learning. Translating the R analysis into Python showed me that I need more practice with pandas, grouping data, and understanding Python syntax. I also want to become more comfortable interpreting statistical results without relying heavily on examples. My machine learning background is still developing, especially with concepts such as autoencoders and anomaly detection. I plan to improve by practicing Python regularly, reviewing statistical concepts, and working through examples until I can complete similar tasks more independently.

---

*Submission: commit this file to your fork and include it in the GitHub repo URL you submit on Canvas.*
