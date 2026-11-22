## Published security advisories

| # | Project | Advisory | CVE | Vulnerability | Severity |
|---|---------|----------|-----|---------------|----------|
| 1 | pdfcpu | [GHSA-vwmc-mhq7-fqhc](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-vwmc-mhq7-fqhc) | — | Exponential-time validation of shared resource graphs (`validate`) | Medium 6.5 (DoS) |
| 2 | pdfcpu | [GHSA-gx4m-7r76-vpww](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-gx4m-7r76-vpww) | — | Unbounded page-slice allocation from attacker page number (`create`, `form fill`) | Medium 6.5 (DoS) |
| 3 | pdfcpu | [GHSA-2623-w998-vcr4](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-2623-w998-vcr4) | — | Uncontrolled recursion walking object graphs (crash) | Medium 6.5 (DoS) |
| 4 | pdfcpu | [GHSA-pr6x-vqwr-4hj2](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-pr6x-vqwr-4hj2) | — | Duplicate cross-reference offsets → repeated stream copies, memory exhaustion | Medium 6.5 (DoS) |
| 5 | pdfcpu | [GHSA-cphg-88q6-whwh](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-cphg-88q6-whwh) | — | Unbounded CPU/memory from attacker-chosen table dimensions (`create`) | Medium 6.5 (DoS) |
| 6 | pdfcpu | [GHSA-p2r6-9jcq-fp7v](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-p2r6-9jcq-fp7v) | — | Unbounded allocation from attacker-chosen bookmark page number (`split`) | Medium 6.5 (DoS) |
| 7 | pdfcpu | [GHSA-g5q6-53hx-f68j](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-g5q6-53hx-f68j) | — | Unbounded CPU/memory from attacker-chosen page size (`poster`) | Medium 6.5 (DoS) |
| 8 | pdfcpu | [GHSA-8pv5-h3hv-xhc9](https://github.com/pdfcpu/pdfcpu/security/advisories/GHSA-8pv5-h3hv-xhc9) | — | Exponential-time object comparison of shared reference graphs (`optimize`) | Medium 6.5 (DoS) |
| 9 | rsyslog | [GHSA-f9hg-rj32-693x](https://github.com/rsyslog/rsyslog/security/advisories/GHSA-f9hg-rj32-693x) | CVE-2026-129833 | mmanon stack buffer overflow while anonymizing embedded IPv4-in-IPv6 text | High 7.5 (overflow) |
| 10 | rsyslog | [GHSA-5pc2-f2v7-5w5p](https://github.com/rsyslog/rsyslog/security/advisories/GHSA-5pc2-f2v7-5w5p) | CVE-2026-129837 | Out-of-bounds read crashes rsyslogd when a template formats a crafted low-year timestamp as a weekday name | High 7.5 (DoS) |
| 11 | rsyslog | [GHSA-cg8j-rwxh-vrg3](https://github.com/rsyslog/rsyslog/security/advisories/GHSA-cg8j-rwxh-vrg3) | CVE-2026-129839 | `option.json` templates emit malformed JSON for quote-only or backslash-only field values | Medium 5.3 (injection) |
