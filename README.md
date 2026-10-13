# Ben Tomasik

Platform engineer. I build the paved road — CI/CD, Kubernetes, developer platforms — and
write down why.

Currently leading Platform Engineering DevOps at **Carrier**, where my team runs the internal
developer platform: a CircleCI orb platform serving tens of thousands of builds a month, a
Backstage service catalog, EKS with ArgoCD/Kargo GitOps, and the CI/CD paved road a few
hundred services deploy through.

Previously web operations at national-publisher scale (Meredith) and infrastructure lead at a
connected-devices company (Telkonet). Ansible since 2016, AWS since before that, here since 2011.

### Worth reading here

- **[gha-wkfl-release-management](https://github.com/tomislacker/gha-wkfl-release-management)**
  — Floating release tags for GitHub Actions. Shell under `bats`, SHA-pinned actions, 7 ADRs,
  and a fail-closed `job.workflow_sha` check that stops `actions/checkout` silently running
  unpinned code on a consumer's runner.
- **[selfhosted-ollama-and-monitoring](https://github.com/DomesticatedRaptor/selfhosted-ollama-and-monitoring)**
  — Homelab as IaC: 13 Ansible roles, Terraform, Prometheus/Grafana/Loki, WireGuard, and a
  local LLM stack. Includes a pre-commit hook that fails the build when my Ansible and Terraform
  cert domains drift apart, because that failure is otherwise invisible for 90 days.
- **[embedded-frosty-monitor](https://github.com/tomislacker/embedded-frosty-monitor)** —
  Diagnostic data logger for frozen-drink machines: ESP32 firmware reading current clamps,
  accelerometers, thermocouples, and an optical drip counter as a seal-wear proxy, with a
  tested Python analysis package and the AWS IoT side wired up in Terraform.
- **[bedrock-pr-review](https://github.com/tomislacker/bedrock-pr-review)** — AI code review on
  AWS Bedrock. GitHub, Bitbucket, and Azure DevOps behind one SCM interface, a two-leg async
  Lambda webhook, 32 test files, 17 ADRs.
- **[openscad-pigpen](https://github.com/tomislacker/openscad-pigpen)** — An SVG logo becomes a
  printable two-layer plaque: Inkscape → potrace → OpenSCAD → STL, fully generated, with the
  STLs committed so GitHub renders them in 3-D.

### Elsewhere

- Upstream: [Backstage](https://github.com/backstage/backstage/pull/32183),
  [cfn-lint](https://github.com/aws-cloudformation/cfn-lint/pull/1599), Ansible's AWS modules,
  pyroute2 — about three dozen merged PRs to projects I don't own.
- [LinkedIn](https://www.linkedin.com/in/bentomasik/)

*Most of my work since 2022 lives in private repos, which is why this account looks quieter
than it is. The 2013–2021 history is public and representative of how I work.*
