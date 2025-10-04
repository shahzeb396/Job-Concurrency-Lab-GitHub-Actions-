# 🚀 Concurrency Control in GitHub Actions

This workflow ensures that **only one deployment job runs at a time**, preventing multiple deployments from overlapping.

## 🧠 Purpose
When multiple developers push code simultaneously, deployment jobs can overlap — causing **race conditions** or inconsistent environments.  
By using **concurrency control**, we make sure **only one deployment runs at a time**, and any new one cancels the previous in-progress job.
