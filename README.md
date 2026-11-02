# geoskill-forest-fire-burn-severity

> Compute forest fire burn severity from pre/post-fire NIR and SWIR imagery using differenced Normalized Burn Ratio (dNBR). Classifies severity into unburned, low, moderate, and high categories. Use when the user wants to assess burn severity, map fire damage, or generate burn severity reports.

See [SKILL.md](SKILL.md) for full usage, inputs and outputs.

## Quick start

```bash
python scripts/forest_fire_burn_severity.py \
  --pre-nir pre_nir.tif --pre-swir pre_swir.tif \
  --post-nir post_nir.tif --post-swir post_swir.tif
```

## License

MIT
