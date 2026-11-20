# Filament ambient occlusion evidence

Images for the issue and pull request about the Filament render options removed in
fb0521eaafec70dc7ecc989297c845c6c95d7e38. Each image shows one of eight views of the same
box-on-plane model, rendered at 640x480 with the Vulkan backend through SwiftShader on CPU,
with the numbers for all eight views under it.

- `a_4.0.0_vs_4.0.1.png`: the 4.0.0 and 4.0.1 PyPI wheels with no `filament.*` keys declared.
- `b_fix_threshold_0.5_vs_4.0.0.png`: main with the fix and `filament.ao.bilateral_threshold` = 0.5, vs the 4.0.0 wheel.
- `c_fix_default_vs_main.png`: main with the fix vs main without it, no keys declared.
- `c_fix_default_vs_main_3538515.png`: the same comparison for the one-option fix on main 3538515.
