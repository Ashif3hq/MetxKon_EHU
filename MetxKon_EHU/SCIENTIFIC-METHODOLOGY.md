# Scientific methodology

This document will record the equations, assumptions, units, processing decisions and validation cases used in MetxKon Lab.

## Data and metadata
Each imported test should preserve:
- Original file and data
- Test identifier and specimen identifier
- Units for all measured quantities
- Specimen geometry, where relevant
- Test conditions and instrument information, where available

## Processing principles
- Never silently overwrite raw measurements.
- Clearly distinguish measured values from calculated values.
- Document any filtering, smoothing, baseline correction or resampling.
- Make units explicit and conversions traceable.
- Report assumptions and limitations alongside results.

## Validation
Each calculation should have documented reference cases and automated tests before being presented as validated.
