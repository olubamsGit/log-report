An Apache-style access log is available at `/app/access.log`.

Parse the log and write a JSON report to `/app/report.json` with exactly these three fields:

- `total_requests` — integer count of all log lines
- `unique_ips` — integer count of distinct client IP addresses
- `top_path` — string of the URL path that appears most often in requests

Success criteria:
1. `/app/report.json` exists and is valid JSON.
2. `total_requests` is the correct integer count of requests in the log.
3. `unique_ips` is the correct integer count of unique IP addresses.
4. `top_path` is the correct most-requested URL path string.
