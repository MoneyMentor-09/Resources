# Money Mentor - Sprint 1 Code Coverage Report

## 1. Tool & Setup

Language: TypeScript (React)

Tests: Vitest + Testing Library

Coverage Tool: Vitest Coverage (V8 provider), Istanbul HTML report output

## 2. Coverage Metrics (REQUIRED)

| Metric | Percentage |
|---|---|
| Line coverage | 96.22% |
| Branch coverage | 88.33% |
| Function / Method coverage | 95.65% |
| Statement coverage | 96.22% |

## 3. Scope of Coverage

Included:
- Components exercised by automated tests in this sprint (`src/components/AboutUs.tsx`, `src/components/Accessibility.tsx`, `src/components/Footer.tsx`, `src/components/SignUp.tsx`).

Excluded:
- Third-party libraries (`node_modules`) and generated artifacts (`build/`, `coverage/`) by default tooling behavior.
- Unexecuted app modules not reached by the current test suite (not loaded during test run).

## 4. Coverage Trend

Baseline sprint — no prior comparison.

## 5. Weak Areas (Honest Reflection)

- `src/components/Accessibility.tsx` (lowest): lower branch coverage due to multiple conditional rendering/accessibility-path branches not all exercised yet.
- `src/components/SignUp.tsx`: complex form validation and interaction branches increase branch surface area; a few branches remain untested.
- `src/components/AboutUs.tsx` / `src/components/Footer.tsx`: currently high coverage, but risk remains around future content/structure changes without broader integration tests.

## 6. Evidence

<!-- - Coverage report: [coverage/index.html](coverage/index.html) -->
- Link to screenshot of coverage summary: [Testcoverage_screenshot](testcoverage/Testcoveragescreenshot.png)

## 7. Statement of Integrity

"This coverage was generated from automated tests executed during this sprint."
