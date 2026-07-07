# hapax-officium

`hapax-officium` is a source-visible internal management decision-support
runtime in the Hapax Systems portfolio.

It is published for boundary review: how a single-operator system separates
preparation, context assembly, and decision support from impermissible
management automation. It is not HR software, not a SaaS product, and not an
adoption surface.

## Claim Ceiling

This repository may be described as an internal management-support artifact
with governed read and preparation paths. It must not be described as a
general management platform, an advice engine, a supportable product, or a
system that produces feedback or evaluations of individual people.

## What To Inspect

| Area | Purpose |
|---|---|
| `axioms/` | Management-domain governance vocabulary and constraints. |
| `logos/` | Runtime and API implementation for the internal management surface. |
| `officium-web/` | Browser interface for local operational visibility. |
| `vscode/` | Local editor integration. |
| `tests/` | Regression coverage for the source-visible artifact. |

## Public Boundary

The public repository is an inspection and citation surface. It does not
create a support queue, customer intake channel, community project, or
commercial promise. Internal endpoint names, local deployment choices, and
demo data are implementation details, not public product commitments.

## License

PolyForm Strict 1.0.0. See [LICENSE](LICENSE), [NOTICE.md](NOTICE.md), and
[SUPPORT.md](SUPPORT.md).
