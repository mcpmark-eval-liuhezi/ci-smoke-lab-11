# ci-smoke-lab-11
Throwaway sandbox repo for CI + contribution flow smoke test

## Build artifact

The CI pipeline (`demo.yml`) is triggered manually with `workflow_dispatch` and writes a short text file
(`build/demo-build.txt`) that is uploaded as a build artifact named **demo-build**.
