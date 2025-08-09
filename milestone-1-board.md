# Milestone 1 – WeatherApp (MVP with Open-Meteo)

## 📌 Board Snapshot with Progress

### 🟢 To Do / Planned
| Order | Issue | Labels | Progress |
|-------|-------|--------|----------|
| 1 | Set up Nuxt 3 baseline with TailwindCSS, Pinia, ESLint/TypeScript | backend, frontend, setup | 0% |
| 2 | Set up Continuous Integration (GitHub Actions) | ci, automation, setup | 0% |
| 3 | Base UI components with TailwindCSS `@apply` and `@utility` | frontend, ui, styling | 0% |
| 4 | Server routes: `/api/search` and `/api/forecast` with configurable cache TTL | backend, api, caching | 0% |
| 5 | City search and favorites management | frontend, state-management, feature | 0% |
| 6 | Daily and hourly weather charts with ECharts | frontend, charts, visualization | 0% |
| 7 | Compare view for two locations | frontend, feature, comparison | 0% |
| 8 | Error handling, loading states, and skeleton screens | frontend, ux, error-handling | 0% |
| 9 | Testing setup (unit, component, and e2e) | testing, automation, ci | 0% |

---

### 🟡 In Progress
| Order | Issue | Labels | Progress |
|-------|-------|--------|----------|
| – | *(none yet)* | | |

---

### 🔵 Done
| Order | Issue | Labels | Progress |
|-------|-------|--------|----------|
| – | *(none yet)* | | |

---

## 📋 Issue Checklists & Status

### 1 – Set up Nuxt 3 baseline with TailwindCSS, Pinia, ESLint/TypeScript
- [ ] Initialize Nuxt 3 project  
- [ ] Install TailwindCSS and configure according to theme colors  
- [ ] Add Pinia store setup in `plugins`  
- [ ] Configure ESLint + TypeScript  
- [ ] Add example page using Tailwind and Pinia  

**Progress:** 0% (0/5)

---

### 2 – Set up Continuous Integration (GitHub Actions)
- [ ] Add `.github/workflows/ci.yml` with lint → typecheck → build jobs  
- [ ] Ensure `package.json` has scripts: `lint`, `typecheck`, `build`  
- [ ] Ensure ESLint/TS config doesn’t fail on a clean scaffold  
- [ ] Document CI badges/links in README  

**Progress:** 0% (0/4)

---

### 3 – Base UI components with TailwindCSS `@apply` and `@utility`
- [ ] Create `assets/css/main.css` with `@layer components` and `@utility`  
- [ ] Define base button styles (`btn-primary`, `btn-secondary`)  
- [ ] Define card, input, and label styles  
- [ ] Test styles in an example page  

**Progress:** 0% (0/4)

---

### 4 – Server routes: `/api/search` and `/api/forecast` with configurable cache TTL
- [ ] Create `getCache` and `setCache` utilities  
- [ ] Implement `/api/search` with validation and caching  
- [ ] Implement `/api/forecast` with validation and caching  
- [ ] Add `stale-while-revalidate` logic  
- [ ] Add unit tests for both routes  

**Progress:** 0% (0/5)

---

### 5 – City search and favorites management
- [ ] Create search input component  
- [ ] Integrate API search with debounce  
- [ ] Display search results dropdown  
- [ ] Add favorites list UI  
- [ ] Persist favorites in `localStorage`  

**Progress:** 0% (0/5)

---

### 6 – Daily and hourly weather charts with ECharts
- [ ] Install and configure ECharts plugin  
- [ ] Create reusable `BaseChart` component  
- [ ] Implement daily forecast chart  
- [ ] Implement hourly forecast chart  
- [ ] Connect charts to API data  

**Progress:** 0% (0/5)

---

### 7 – Compare view for two locations
- [ ] Add compare mode toggle  
- [ ] Allow adding a second location  
- [ ] Fetch and display both forecasts  
- [ ] Update charts to display two datasets  

**Progress:** 0% (0/4)

---

### 8 – Error handling, loading states, and skeleton screens
- [ ] Implement skeleton loader components  
- [ ] Display API error messages in UI  
- [ ] Add retry button on error states  

**Progress:** 0% (0/3)

---

### 9 – Testing setup (unit, component, and e2e)
- [ ] Install Vitest + @vitejs/plugin-vue + @vue/test-utils + jsdom  
- [ ] Add `vitest.config.ts` and sample unit test  
- [ ] Add Playwright (or Cypress) with one smoke test  
- [ ] Update CI to run `npm run test:unit`  
- [ ] Document how to run tests locally in README  

**Progress:** 0% (0/5)
