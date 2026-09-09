# PR rate-limit sandbox

Disposable repository for testing contributor PR limits. `PR_RATE_LIMIT_DRY_RUN=true` was configured initially: decisions were logged without comments or closures.

Workflow and mocked tests are copied from [TensorRT-LLM commit f956c4c5](https://github.com/NVIDIA/TensorRT-LLM/commit/f956c4c5acdc259b0c65be334267167de1d541a0); the repository guard and reopening guidance are adapted, and the submission window/cooldown is shortened to five minutes for this sandbox. Tests and comment text match the five-minute window. The five-open-PR cap still applies after the cooldown expires. Enforcement is now enabled (`PR_RATE_LIMIT_DRY_RUN=false`).
