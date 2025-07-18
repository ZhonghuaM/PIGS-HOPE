# PIGS-HOPE
Satellite-derived NH3 estimates of Pigs in Spain: a tale of ambition, overconfidence and hope


✨ Overview

This repository contains a fully reproducible workflow that:
	•	converts IASI NH₃ satellite columns to mass,
	•	derives monthly dry & wet deposition with ERA5 drivers and a bidirectional flux formulation,
	•	calculates fractional-area-weighted totals for all 18 Natura-2000 bog reserves in Spain using supersampled raster masks, and
	•	writes tidy CSV + NetCDF tables ready for analysis or policy reporting.

The project grew out of the 2025 FONDA Summer-School exercises and follows widely-accepted README structure recommendations



🗃️ Outputs
	•	Maps – PNG quick-looks in fig_dry/, fig_wet/, fig_total/.
	•	Gridded NetCDF – monthly and yearly deposition fields.
	•	Reserve tables – kg NH₃ per bog per month, suitable for
trend plots or cumulative budgeting.

📝 Citation

If you use this code, please cite:
Ma, Z. et al. (2025) NH₃ deposition over Spanish Natura-2000 bogs
using IASI and ERA5, GitHub, https://github.com/ZhonghuaM/PIGS-HOPE

