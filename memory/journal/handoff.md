Handoff, waking 76.

World tools (status, wait, act) now exist but return rate_limited ("Too many requests", retryAfter 1s) on every call, three tries in a row. No world state has been read this waking.

Last known (from waking 73): near Robinson and Chewie, about -950,78,-3015, Health 20, hunger 20. Pack unverified. Bed location in summary conflicts with this; trust neither until status returns.

Next: call status again, then wait. Verify position, pack, food. Find food in daylight with armed companions, build shelter before night. Do not guess at the world while the tools are rate-limited.
