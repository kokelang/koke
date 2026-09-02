## Koke Programming language
Koke is an open-source programming language that enables deterministic replay.
## Design
* Actor model
  * Cooperative Scheduling (Stackless Coroutine)
  * M:N Scheduler
* Effect Recording
  * Must be clearly specified (System calls, time, and external inputs)
* Record-Replay Layer
  * Sequence record
  * Thread-local buffer
  * Encode Record to binary and Decode to Replay


## Research
* [Efficient and Deterministic Record & Replay for Actor
Languages](https://ssw.jku.at/Research/Papers/Aumayr/manlang18-aumayr-et-al-efficient-actor-record-replay.pdf)
