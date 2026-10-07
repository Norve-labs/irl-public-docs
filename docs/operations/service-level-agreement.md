# IRL — Service Levels

**Version:** 2.0
**Effective:** 2026-10-05

IRL is currently offered free of charge, so there is **no paid SLA and no
service credits**. This page states plainly what you can and cannot rely on.

## Self-hosted IRL

You run it, so availability is yours. The engine is built for it:

- Every authorize and bind is a synchronous call that fails closed: if IRL is
  unavailable, a well-behaved client (such as the IRL Gateway) sends no order.
- Unbound traces remain visible in `/irl/pending` and `/irl/orphans` for
  reconciliation after an outage.
- Published baseline latency and throughput figures are in
  [benchmarks/results.md](https://github.com/norve-labs/irl/blob/main/docs/benchmarks/results.md). Measure on your own
  hardware before relying on any number.

## The public sandbox (irl.macropulse.live)

Best effort, for evaluation. It may be reset or rate-limited without notice.
Don't route real orders through it.

## Hosted IRL for teams

Not offered yet. If you need a managed deployment with an uptime commitment,
retention guarantees or compliance reporting, tell us what you need:
https://github.com/norve-labs/irl-gateway/issues or hello@macropulse.live.
Any future paid offering will publish its own SLA.
