BCR Modeler — SPARC Galaxies

Galaxies-only BCR modeler. Runs blind first from enclosed mass, then overlays observed velocities, and builds a 3-page DEX report. PDF.

Contents

/bootstrap/ — modeler code (galaxies only)

/data/ — SPARC inputs: sparc_radii_enclosed_baryonic_mass.xlsx, sparc_observed_velocity_profiles.csv

/outputs/ — PDFs: BCR_galaxies_blind.pdf, BCR_galaxies_overlays.pdf, BCR_full_dex_report.pdf





Outputs (brief)

BCR_galaxies_blind.pdf — per-galaxy pages: BCR (solid), RAR (dashed), Baryon (dotted). No obs.

BCR_galaxies_overlays.pdf — same pages with Observed points (black dots with thin white edge; error bars if present); footer shows per-galaxy median |DEX| (BCR) and bias.

BCR_full_dex_report.pdf — 3 pages: Headline (median RMS-dex for Baryon/RAR/BCR), CDF (three curves), Histogram (three overlaid series).




“If a run goes wrong”:

Re-upload the modeler and re-run. Then tell the AI explicitly:
“Study this README line-by-line and execute the modeler exactly as specified. Run Stage 1 (blind) now from enclosed mass only; if observations exist, run Stage 2 (overlays) and build the 3-page DEX report. PDF-only outputs. Do not improvise.”

Your results should replicate the PDFs in /outputs/ (same pages, styles, and numbers). If they don’t, repeat the step above.
