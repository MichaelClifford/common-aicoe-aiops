# AICoE AIOps organization

[![](https://prow.operate-first.cloud/badge.svg?jobs=aicoe-aiops-*)](https://prow.operate-first.cloud/?repo=aicoe-aiops%2Fcommon&type=postsubmit)

## Labels

Please check out [AICoE AIOps GitHub Organization Labels](labels.md) for available labels in this organization. Labels are defined in [labels.yaml](labels.yaml). You can apply those labels via Prow chat-ops commands like `/kind`, `/area` etc. For more detail on Prow commands please consult [command help](https://prow.operate-first.cloud/command-help).

## Git Hub organization

Git Hub organization is configured according to the [github-config.yaml](github-config.yaml) file.

---

Uses Prow ([Labels][1] and [Peribolos][2] plugins) to declaratively manage Git Hub organization and repositories.

[1]: https://github.com/kubernetes/test-infra/tree/master/prow/cmd/peribolos
[2]: https://github.com/kubernetes/test-infra/tree/master/prow/cmd/peribolos
