# Neighbor Spoofing in US Scam Call Complaints

How often does a reported scam or unwanted call come from a number that shares the consumer's own area code? This dataset summarizes 486,639 consumer complaints across 261,367 caller numbers.

Full analysis and free number lookup: https://thescamexposed.com/robocall-checker
Publisher: The Scam Exposed (https://thescamexposed.com)

## Key findings

- 37.5% of complaints came from a caller number with the same area code as the consumer.
- Excluding toll-free callers, that rises to 45.6%.
- Medical or prescription calls had the highest share at 86.0%.
- Debt reduction calls had the lowest at 10.6%.

## Files

`neighbor_spoofing_summary.csv`

| Column | Meaning |
|---|---|
| segment | Complaint group or call topic |
| complaints_with_callee_area_code | Complaints where the consumer's area code was recorded |
| same_area_code_complaints | Complaints where the caller shared that area code (overall rows only) |
| same_area_code_pct | Share of complaints with a matching area code |

Topic rows exclude toll-free caller numbers and include topics with 3,000 or more complaints.

## Method

Source records are public consumer complaint data from US regulators, aggregated in The Scam Exposed database. Each complaint's recorded consumer area code was compared with the area code of the reported caller number. Results are weighted by complaint count.

## Limitations

- Complaints are consumer reported and not verified.
- Caller ID can be spoofed, so the caller number may not be the real origin.
- Topic is assigned once per caller number and is approximate.

## License

CC BY 4.0. Free to use with attribution: "Source: The Scam Exposed, thescamexposed.com".
