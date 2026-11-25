# ChronosDet — VLDB Artifact

> Draft scaffold. Code, datasets, dependencies, and reproduction commands are
> not packaged yet. All TODO items must be completed before submission.

## Paper and artifact information

- Paper title: TODO
- Authors / contact: TODO
- Paper URL / DOI: TODO
- Artifact repository / archive DOI: TODO
- Artifact version / source commit: TODO
- License and third-party notices: TODO

## Overview

This artifact will package the ChronosDet implementation and experiments for
rug-pull detection. The existing project includes HEBG, HTFG, Fusion, evaluation,
ablation, efficiency, and real-world inference components.

TODO: Add a short method summary and specify which paper results are supported.

## Directory layout

```text
ChronosDet_artifacts_VLDB/
├── README.md       # Overview and reviewer entry point
├── environment/    # Dependencies and installation instructions
├── src/            # Implementation
├── script/         # Reproduction entry points
├── config/         # Configuration templates
├── dataset/        # Data access, sample data, and fixed splits
├── results/        # Reference results and generated outputs
└── docs/           # Detailed reproduction guide and paper mapping
```

Each directory currently contains only its README.

## Requirements and installation

TODO: Record tested OS, Python, PyTorch/DGL/CUDA versions, hardware, storage,
and installation commands in [environment/README.md](environment/README.md).

## Quick start

TODO: Provide one small example, its exact command, expected output, and runtime.

1. Install the documented environment.
2. Obtain the sample data and configuration templates.
3. Run the sample command and compare its output with the reference result.

These steps are an outline; executable commands will be added later.

## Reproducing paper results

TODO: Finalize the supported experiments and map them to paper tables/figures
in [docs/README.md](docs/README.md). Candidate groups from the source project:

- HEBG / HTFG branch training and Fusion evaluation.
- Ablation and sensitivity experiments.
- Efficiency measurements.
- Real-world inference and observation analysis.

For each supported experiment, document inputs, exact commands, seeds/splits,
expected metrics, runtime, and output paths.

## Completion checklist

- [ ] Finalize paper metadata, artifact scope, license, and release version.
- [ ] Copy the required implementation and portable scripts/configurations.
- [ ] Pin and verify the environment on a clean machine.
- [ ] Add sample/full-data access instructions, splits, and checkpoints as needed.
- [ ] Add and verify the quick start and paper reproduction commands.
- [ ] Add reference results, acceptable variation, and runtime estimates.
- [ ] Check the release for credentials, private endpoints, and local paths.
