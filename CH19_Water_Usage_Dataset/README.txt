# CH19 – Water Usage Insight Practice Dataset

This is a **synthetic practice dataset generated for learning and assessment preparation**. It is not an official AquaTrack Utilities dataset and the values are not real customer records.

Files:
- meter.csv: date, connection, usage (daily meter readings; includes deliberate data-quality issues and anomalous usage patterns)
- connections.csv: connection, type, locality, household_size_band
- billing.csv: connection, billing_cycle, charge
- weather.csv: date, temperature, rain
- maintenance.csv: maintenance_id, connection, leak_report, repair_date

Suggested tasks:
1. Inspect missing values, duplicates, inconsistent connection types, negative usage, and unmatched maintenance records.
2. Clean and merge datasets carefully.
3. Explore locality/type usage, weather relationships, spikes, peak periods, and before/after repair patterns.
4. If you train an ML model, define and document how the anomaly target labels are created. Do not report performance until measured on a held-out test set.
