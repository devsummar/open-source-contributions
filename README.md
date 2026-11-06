# 🌍 My Open Source Contributions

A running log of my contributions to open-source projects: what I fixed, why it mattered, and where each PR stands.

**Summar Kumar** · IT Analyst, MIET Jammu · [@devsummar](https://github.com/devsummar)

## Pull requests

| Date | Project | Issue | What I did | PR | Status |
|------|---------|-------|------------|----|--------|
| 2026-11-06 | [xarray](https://github.com/pydata/xarray) | [#7699](https://github.com/pydata/xarray/issues/7699) | `drop_sel` now accepts the same label forms as `.sel`, including partial datetime strings that previously raised; added regression tests | [#11861](https://github.com/pydata/xarray/pull/11861) | 🟡 In review |
| 2026-11-03 | [Kestra](https://github.com/kestra-io/kestra) | [#20210](https://github.com/kestra-io/kestra/issues/20210) | Pebble `date` filter now keeps full nanosecond precision for 19-digit epoch timestamps, which were silently shifted by hundreds of milliseconds; added regression tests | [#22201](https://github.com/kestra-io/kestra/pull/22201) | 🟡 In review |
| 2026-11-03 | [Kestra](https://github.com/kestra-io/kestra) | [#21017](https://github.com/kestra-io/kestra/issues/21017) | Replaced Bootstrap utility classes in `Secrets.vue` with scoped CSS using `--ks-*` design tokens; removed unused utility classes from design-system `_utilities.css` | [#22183](https://github.com/kestra-io/kestra/pull/22183) | 🟢 Merged |
| 2026-10-18 | [Vue.js Docs](https://github.com/vuejs/docs) | [#3406](https://github.com/vuejs/docs/issues/3406) | Right-clicking the navbar logo now opens the official Vue brand assets, so people stop saving the logo directly | [#3482](https://github.com/vuejs/docs/pull/3482) | 🟡 In review |
| 2026-10-18 | [Nuxt Test Utils](https://github.com/nuxt/test-utils) | [#541](https://github.com/nuxt/test-utils/issues/541) | `mockNuxtImport` now returns the mock, removing the need for `vi.hoisted` workarounds; added unit, type and example tests | [#1864](https://github.com/nuxt/test-utils/pull/1864) | 🟡 In review |
| 2026-10-18 | [MDN Web Docs](https://github.com/mdn/content) | [#42516](https://github.com/mdn/content/issues/42516) | Documented the WebAuthn `mediation: "conditional"` option for `CredentialsContainer.create()` and fixed the `conditionalCreate` capability description | [#46191](https://github.com/mdn/content/pull/46191) | ⚪ Closed |
| 2026-10-18 | [statsmodels](https://github.com/statsmodels/statsmodels) | [#8842](https://github.com/statsmodels/statsmodels/issues/8842) | Fixed exposure handling in the truncated and zero-inflated count models, where exposure was logged twice and gave nan or wrong estimates; added tests | [#10505](https://github.com/statsmodels/statsmodels/pull/10505) | 🟡 In review |

**Status key:** 🟡 In review · 🟢 Merged · 🔵 Changes requested · ⚪ Closed
