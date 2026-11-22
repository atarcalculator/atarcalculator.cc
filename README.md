# ATAR Calculators

Open-source, dependency-free HTML/JS calculators for converting Australian senior-secondary
results into an estimated ATAR (Australian Tertiary Admission Rank), one per state system.

Built and maintained by [atarcalculator.cc](https://atarcalculator.cc) — live, maintained
versions of these same calculators (plus full what-if/improvement simulators) run there.

## Calculators

| State system | Folder | Live demo |
|---|---|---|
| HSC (New South Wales) | [`calculators/hsc`](calculators/hsc/index.html) | https://atarcalculator.cc/hsc-atar-calculator/ |
| QCE (Queensland) | [`calculators/qce`](calculators/qce/index.html) | https://atarcalculator.cc/qce-atar-calculator/ |
| SACE (South Australia) | [`calculators/sace`](calculators/sace/index.html) | https://atarcalculator.cc/sace-atar-calculator/ |
| TCE (Tasmania) | [`calculators/tas`](calculators/tas/index.html) | https://atarcalculator.cc/tce-atar-calculator/ |
| VCE (Victoria) | [`calculators/vce`](calculators/vce/index.html) | https://atarcalculator.cc/vce-atar-calculator/ |
| WACE (Western Australia) | [`calculators/wace`](calculators/wace/index.html) | https://atarcalculator.cc/wace-atar-calculator/ |
| SAT to ATAR (US equivalence estimate) | [`calculators/sat`](calculators/sat/index.html) | https://atarcalculator.cc/sat-to-atar-calculator/ |
| IB to ATAR (Combined Rank) | [`calculators/ib`](calculators/ib/index.html) | https://atarcalculator.cc/ib-to-atar-calculator/ |
| Gaokao to ATAR (China) | [`calculators/gaokao`](calculators/gaokao/index.html) | https://atarcalculator.cc/gaokao-to-atar-calculator/ |
| HKDSE to ATAR (Hong Kong) | [`calculators/hkdse`](calculators/hkdse/index.html) | https://atarcalculator.cc/hkdse-to-atar-calculator/ |

Each folder is a single self-contained `index.html` — no build step, no dependencies.
Open it directly in a browser, or drop it on any static host / GitHub Pages.

## Usage

Clone the repo and open any calculator directly:

```bash
git clone https://github.com/atarcalculator/atar-calculators.git
cd atar-calculators/calculators/hsc
# open index.html in a browser
```

Or serve the whole repo with GitHub Pages and link straight to a calculator,
e.g. `https://atarcalculator.github.io/atar-calculators/calculators/hsc/`.

## Methodology and data sources

Each calculator implements the official scaling/aggregation methodology published by
that state's tertiary admissions authority (e.g. UAC for NSW, QTAC for QLD, SATAC for SA,
VTAC for VIC, TASC for TAS, TISC for WA). Scaling tables and formulas are embedded in
each calculator's source and are reviewed against the authorities' published reports.
These calculators are estimates for planning purposes only — they are not official and
are not affiliated with any tertiary admissions center.

## Contributing

Issues and pull requests are welcome — especially for scaling-table updates when a state
publishes a new year's data, or bug reports on edge cases in a specific subject's scoring.

## License

MIT — see [LICENSE](LICENSE).
