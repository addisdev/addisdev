# Taylor Addison

**Senior Manager, Data Engineering at Warner Bros. Discovery**

I build data platforms and engineering teams at scale, and I stay close to the
craft through mobile systems, developer infrastructure, and on-device ML.

I started as an iOS engineer, shipped software across the screens in the living
room, followed the data those products produced, and now lead teams building
CNN's data platform. Building end to end is how I keep my technical judgment
grounded in what teams actually have to operate.

[Portfolio](https://tayloraddison.dev) ·
[LinkedIn](https://www.linkedin.com/in/tayloraddison) ·
[Email](mailto:addisdev@gmail.com)

## Featured work

### [Fleet Runner](https://github.com/addisdev/fleet-runner)

[![Fleet Runner: a shelf of old phones turned into a device lab](https://raw.githubusercontent.com/addisdev/fleet-runner/main/docs/img/banner.png)](https://github.com/addisdev/fleet-runner)

A shelf of old phones turned into a device lab. One queued job can run UI tests,
visual regression, battery experiments, or on-device ML benchmarks across real
iOS and Android hardware.

- Five independently implemented runners share one tested protocol across
  TypeScript, Swift, Kotlin, JavaScript, and BrightScript.
- The first real workload established that an int8 CPU model beat an fp32 GPU
  model for a shipping plant-identification feature.
- Results include the device state and measurement conditions needed to decide
  whether a number is trustworthy.

**Demonstrates:** distributed systems, mobile platforms, protocol design,
on-device ML evaluation, test infrastructure, and evidence-driven trade-offs.

[Source](https://github.com/addisdev/fleet-runner) ·
[Documentation](https://addisdev.github.io/fleet-runner/) ·
[Releases](https://github.com/addisdev/fleet-runner/releases)

### [Actions Runners](https://github.com/addisdev/actions-runners)

[![Actions Runners: self-hosted GitHub Actions runners on one Mac](https://raw.githubusercontent.com/addisdev/actions-runners/main/docs/img/banner.png)](https://github.com/addisdev/actions-runners)

Register, supervise, and observe a fleet of self-hosted GitHub Actions runners
on one Apple Silicon Mac. The dashboard catches the failure states that appear
healthy from either GitHub or launchd alone.

- Reconciles local process state with GitHub's view and names every form of
  drift instead of reducing health to a single green light.
- Preserves operational history in SQLite and explains why work is queued.
- Uses real fleet evidence to separate code failures, infrastructure failures,
  account limits, and host saturation.

**Demonstrates:** CI/CD infrastructure, observability, macOS systems work,
failure modeling, operational safety, and pragmatic system design.

[Source](https://github.com/addisdev/actions-runners) ·
[Documentation](https://addisdev.github.io/actions-runners/) ·
[Releases](https://github.com/addisdev/actions-runners/releases)

## How I lead

- Connect the client, pipeline, and analytical model instead of optimizing one
  layer in isolation.
- Make system behavior observable before teams have to debug it under pressure.
- Write down the trade-offs, failure modes, and ownership boundaries that let a
  team operate what it ships.
- Stay hands-on enough to distinguish accidental complexity from constraints
  that the team genuinely has to design around.

## Current interests

Data contracts and platform reliability · developer infrastructure ·
on-device inference · cross-platform systems · engineering leadership

The longer version of my work, career, and shipped products is at
**[tayloraddison.dev](https://tayloraddison.dev)**.
