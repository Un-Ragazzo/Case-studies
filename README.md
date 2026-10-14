# Portfolio

Public case studies, runnable experiments, UI prototypes, demos, and code samples, organized so the explanation and the working output can be found together.

## Browse the collection

| Content | Where to go |
| --- | --- |
| Runnable tools, prototypes, and examples | [Demos](demos/README.md) |
| Problem, contribution, decisions, and results | [Case studies](case-studies/README.md) |
| Email signature generator | [Implementation](demos/email-signature/index.html) |

```text
.
├─ README.md
├─ demos/
│  ├─ README.md
│  └─ email-signature/   # existing generator, imported with its Git history
└─ case-studies/
   └─ README.md
```

Keep each new runnable output's source, assets, and instructions together under `demos/<name>/`. Link it to a case study when the problem and decisions need explanation.

## Publication rule

- Private work originates in the relevant private workspace.
- Publish here only after removing private, company, client, credential, and internal-context information.
- Treat this repository as a downstream public output, not the upstream private working copy.
- Do not automatically sync changes from here back into a private workspace.
- Ground case study claims in evidence and distinguish my contribution from team results.

## Source and hosting

This collection imports Open-workbench's public Git history and preserves the email signature generator's contents under `demos/email-signature/`. [Open-workbench](https://github.com/Un-Ragazzo/Open-workbench) keeps its existing `email-signature/` copy and repository name for compatibility with the established GitHub Pages URL.

New public source work belongs here. Deliberately update the compatibility copy in Open-workbench when publishing a generator update to that existing URL. Hosting a new output is a separate step from adding its source here.

The target repository was the empty `Case-studies` repository. **Portfolio** is its intended name; GitHub links use `Case-studies` until the rename is completed. This source consolidation does not enable GitHub Pages or establish a new live URL for this repository.
