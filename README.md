# FinMark-AI-Agent-Synthetic-Simulation
Synthetic Financial Customer Simulation using AI Agents and SDV (CTGAN, HMA) — builds privacy-safe datasets to test financial products, marketing strategies, and behavioral models.
# FinMark AI Agent – Synthetic Customer Simulation

This project builds synthetic financial datasets and AI-driven simulations
to test product-market fit and marketing strategies in a privacy-safe environment.

## Phases Implemented

### Phase 1: Seed Data
- Built ~2000 young professional profiles using Faker.
- Added behavioral tables: transactions and campaign events.

### Phase 2: Synthetic Expansion with SDV
- Used CTGAN (single-table) to grow customers → ~10,000.
- Used HMA Synthesizer (multi-table) to grow customers + transactions + campaigns.
- Validated with KS tests, correlation checks, and distribution plots.

### Outputs
- Seed datasets (customers, transactions, campaigns).
- Expanded datasets (10k+ customers with behaviors).
- Reality check reports and plots.

