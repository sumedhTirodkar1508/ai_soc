# Deployment entry points

Use the root `compose.yaml` and the current repository README for the supported
research platform. `ai-services.yml` and `integrated-stack.yml` are compatibility
includes of that file (Compose v2.20+). Run from the repository root after
`python scripts/configure_local.py`.

The other files preserve earlier Wazuh, monitoring, network analysis, SOAR and
Windows lab configurations. They require separate credentials, certificates,
external images and integration testing, and are not part of the recovered
local-stack acceptance. They may have port conflicts with the supported stack.
Read `docs/development/operations.md` before adding external lab infrastructure.

## Maintainer

Dev Bhatt maintains this repository, with a focus on data solutions, analytics,
risk indicators, controls and automation. He has over 6 years of professional
experience building automated pipelines, controls and dashboards.

- Email: [devbhattwork27@gmail.com](mailto:devbhattwork27@gmail.com)
- LinkedIn: [linkedin.com/in/dev-bhatt27](https://linkedin.com/in/dev-bhatt27)