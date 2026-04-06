Title: B2B Marketing Mix Model (MMM) & Funnel Optimizer

Overview
A data-driven optimization tool designed to solve the "Capital Allocation Problem" in B2B Demand Generation. Unlike linear spreadsheets, this optimizer accounts for channel saturation and diminishing returns, providing a more realistic projection of MQL, SQL, and Opportunity volume based on varying budget levels.


Core Logic & Architecture

Non-Linear Yield Curves: Built using an exponential saturation function to model how different channels (Search, Social, Programmatic) scale. Each channel has a unique "decay" rate and "ceiling" based on historical performance data.

Greedy Allocation Algorithm: The engine performs iterative marginal analysis. It allocates the budget in $1,000 increments to the channel offering the highest incremental Opportunity yield at that specific spend level.

Full-Funnel Modeling: Integrates unit economics (CAC/CPO) across the entire lifecycle, from top-of-funnel spend to bottom-of-funnel Pipeline Value ($ACV).


Key Features

Dynamic Reallocation: Toggling a channel "Off" triggers an immediate re-optimization, shifting that budget to the next most efficient active channel.

Marginal Efficiency Visualization: Chart.js integration highlights the "bend in the curve" where increasing spend leads to inefficient CPOs.

Executive Metrics: Real-time calculation of Blended Cost per Opp and Total Pipeline Value.


Tech Stack

Frontend: Tailwind CSS for high-fidelity UI.

Visuals: Chart.js for dynamic yield curve rendering.

Icons: Lucide-JS.

Logic: Vanilla JavaScript (Greedy Optimization Engine).
