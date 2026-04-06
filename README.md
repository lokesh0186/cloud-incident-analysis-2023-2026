# Cloud Incident Analysis Artifact (2023–Q1 2026)

Artifact package for the paper:

**"A Comparative Analysis of Major Public Cloud Incidents from Official Provider Records (2023–Q1 2026)"**

Submitted to IEEE IC2E 2026.

## Files

- `artifact_incident_records.csv` — Main corpus, one row per official provider record (70 records total)
- `artifact_source_index.csv` — Provenance-oriented source index aligned by observation_id

## Notes

1. The study preserves the provider-public record model rather than inferring provider-internal incident deduplication.
2. Some Google Cloud rows are derived from product history pages rather than direct incident pages.
3. Duplicate source_url values are expected for Google Cloud product history page entries.
4. Manuscript tables were reconciled against the main corpus fields in the final artifact.

## License

MIT License
