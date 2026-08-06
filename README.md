# CROSS comprehensive reproduction package

This private repository distributes the comprehensive reproduction package for the CROSS experiments.

## Release package

Download the ZIP archive from **Releases** (tag: `v2026.08.06`). The archive is stored as a GitHub Release asset because its size exceeds the 100 MiB Git object limit.

- Archive: `CROSS_comprehensive_reproduction_20260806.zip`
- Size: 1,695,585,265 bytes (about 1.58 GiB)
- SHA-256: `0b5cd8aef1fc7f1812117b5ce97e990a75248eb4554167e11384268e33035e49`
- Payload manifest SHA-256: `70a83e3c78b1b8a1e2a4a4ba16f43ac62ade1de0d8cefa89ad00d1179e72832b`

## Included materials

- Frozen model artifacts and metadata for 28 model bundles
- Per-epoch trajectory outputs for all 28 runs (483,840 rows)
- Reproduction scripts and environment specifications
- Protocol locks, manifests, source maps, provenance, and validation reports
- Documentation covering scope, trajectory fields, trust boundaries, and provider attribution

## Recommended workflow

1. Download the Release asset.
2. Verify the archive SHA-256 before extracting.
3. Read `REPRODUCTION_SCOPE.md`, `TRAJECTORY_DATA_DICTIONARY.md`, and `SECURITY_AND_TRUST.md`.
4. Create the documented environment and run `run_reproduction.ps1` or `reproduce.py`.
5. Compare generated outputs against the included manifests and reference trajectories.

## 中文说明

这是 CROSS 实验的全面复现包，补充了最小复现包中缺失的逐历元轨迹、冻结模型、完整清单、来源映射、环境说明和验证材料。请从 Releases 下载压缩包，并在解压前核对 SHA-256。

## Access

The repository and Release are private. Share access only with authorized collaborators.
# CROSS
