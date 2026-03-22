## Approach
- Parse `f:\trae_workspace\test_20251116\results.txt` to collect all N1–N6 values per draw
- Compute frequency per number (1–49) and apply recency weighting (e.g., exponential decay) to favor recent appearances
- Exclude the most recent draw’s numbers to diversify upcoming picks
- Constrain combinations: 7 unique numbers, mixed low/mid/high distribution, target 3–4 odd vs. 3–4 even
- Use weighted sampling without replacement to build three combinations that satisfy constraints

## Implementation Steps
1. Read and normalize the table (skip headers, parse columns N1–N6)
2. Build counts and recency-weighted scores
3. Define constraints: range buckets (1–16, 17–33, 34–49), odd/even balance
4. Generate 3 combinations via weighted sampling and validate constraints
5. Output the three combinations to the console (and optionally save to a text file)

## Options
- Toggle exclusion window (exclude last 1–3 draws)
- Adjust odd/even target and bucket distribution
- Switch weighting from exponential decay to linear or none