> ## 🚚 Superseded by [KosPos](https://github.com/alkprojects/kospos)
>
> The cost-of-position math from this calculator is being lifted into **[KosPos](https://github.com/alkprojects/kospos)**, a unified position-management app for SF City and County departments. This standalone calculator stays online as a quick public lookup tool; ongoing development happens in KosPos.

---

# CCSF Job Class Calculator

Standalone employee-cost calculator for SF City and County job classes — covers FY 2025-26.

## 🔗 Live site

<https://alkprojects.github.io/CCSF-Job-Class-Calculator/>

## What it does

- Picks a job class (by code or by title)
- Applies the right SetID, retirement code, and step / range / range position
- Walks the FY 2026 pay-period calendar with PP1 + PP15 COLAs
- Calculates salary + benefits per pay period through fiscal year-end
- Shows benefit breakdown (OASDI, Medicare, retirement, H&B, etc.) for PP26 (the full post-COLA period)

Pure client-side: a single `index.html` with embedded DHR steps, ranges, and benefit lookup data.

## Reference data

The embedded data covers FY 2025-26 only. New fiscal years require updating the embedded `STEPS_LK`, `RANGES_LK`, `CALENDAR`, and COLA constants. (KosPos solves this with versioned reference data.)
