# Perenna Labs

> **Continuous, linear payment streams on Stellar — built with Soroban.**

Lock funds once. They unlock to the recipient every second until the stream ends.

## At a glance

| Area | What it means |
| --- | --- |
| Accrue by the second | Balance is exact integer math against the ledger timestamp — no drift, no floating point. |
| Withdraw on demand | The recipient pulls whatever has accrued without closing the stream. |
| Cancellable by design | A sender can stop early; the recipient keeps everything already earned and the sender is refunded the rest. |

Repository: https://github.com/perenna-labs/perenna-contracts

``Soroban`·`· `Rust`·`· `Stellar``
