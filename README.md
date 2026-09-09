# PR rate-limit sandbox

Disposable repository for testing contributor PR limits. `PR_RATE_LIMIT_DRY_RUN=true` is configured initially: decisions are logged without comments or closures.

Workflow and mocked tests are copied from [TensorRT-LLM commit f956c4c5](https://github.com/NVIDIA/TensorRT-LLM/commit/f956c4c5acdc259b0c65be334267167de1d541a0); only the workflow's repository guard is changed for this sandbox.
