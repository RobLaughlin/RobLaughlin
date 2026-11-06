# Robert Laughlin

Data analyst and data engineer working in SQL, Python, dbt, and BigQuery, with a strong probability and statistics foundation.

Tacoma, WA · Open to remote work and relocation to the Des Moines area · [rjln.dev](https://rjln.dev) · [LinkedIn](https://www.linkedin.com/in/robert-laughlin-data) · [Email](mailto:rjln.data@gmail.com)

## Now

- Analyzing sale prices on the Polk County pipeline's marts: SQL analysis, a BI dashboard, then statistical inference
- Studying applied statistics: inference, then regression
- Open to data analyst, BI, analytics engineering, and junior data engineering roles

## Projects

### [Polk County Residential Sales Pipeline](https://github.com/RobLaughlin/polk-county-ingestion-pipeline)

`Python` `SQL` `dbt` `BigQuery` `Cloud Storage` `Terraform` `Docker`

- Terraform provisions a versioned Cloud Storage bucket, a raw BigQuery dataset, and one dataset per dbt layer; the dbt profile and sources are generated from Terraform outputs.
- A Dockerized Python job downloads the Polk County Assessor's yearly sale files with retries, uploads only new or changed files (MD5 comparison), and loads 403,264 sale records (1990–2026) into BigQuery.
- 38 dbt models end in a star schema: sale-level fact tables; parcel, building, date, and code dimensions; and bridge tables for sales that cover several parcels. Building records are versioned, so each sale sees the house as it was when it sold.
- 205 dbt tests, enforced contracts on 32 models, and source freshness checks. Warning-level tests flag source-data problems, such as 249 sales whose total assessment isn't land plus building, and keep the failing rows in audit tables.
- [CS50 SQL final project](https://github.com/RobLaughlin/cs50_sql_final): a 2,000-sale SQLite sample of the star schema, with foreign keys, views, and indexes.

### [Neural Network from Scratch](https://github.com/RobLaughlin/neural-network-from-scratch)

`Python` `NumPy`

A feed-forward network with hand-written backpropagation and stochastic gradient descent in NumPy, an MNIST parser, and a Tkinter canvas for classifying hand-drawn digits. Reports roughly 95–96% accuracy on the 10,000-image MNIST test set.

### [NeoTUI](https://github.com/RobLaughlin/NeoTUI) · [neotui.dev](https://www.neotui.dev/)

`Shell` `Lua`

A local-first terminal environment combining tmux, zsh, lf, and Neovim, with isolated configuration, a version-aware installer, and LSP/DAP tooling. I use it every day.

### [Advent of Code 2022](https://github.com/RobLaughlin/aoc_2022)

`C++`

All 25 days, using Dijkstra's algorithm, BFS state-space search with pruning, union-find, cycle detection, and interval merging.

### Smaller projects

- [KNN Demo](https://github.com/RobLaughlin/KNN-Demo): vectorized k-nearest-neighbor classifier with animated 2D and 3D examples (Python, NumPy)
- [Complex Set Simulator](https://github.com/RobLaughlin/complex-set-simulator): Mandelbrot and Julia set explorer (Python, NumPy, Tkinter)
- [Shopping Cart](https://github.com/RobLaughlin/Shopping-Cart-Project): React and TypeScript storefront tested with Vitest and Testing Library ([live](https://mellifluous-lollipop-3d865a.netlify.app/))

## Skills

- **Data:** SQL (window functions, CTEs, as-of joins, row grain and join fan-out checks), dbt, BigQuery, dimensional modeling (star schemas), SQLite, MySQL, pandas, NumPy
- **Statistics:** probability (Bayes, expectation and variance, LLN/CLT), distributions, descriptive statistics, missingness and outlier audits
- **Engineering:** Python, Bash, Terraform, Docker, Git, Linux; also TypeScript and React, C++, and Go

## Education and certificates

- Coursework toward a B.S. in Data Science, City University of Seattle, 2019–2021 (100 quarter credits)
- Certificates:
  - CS50's Introduction to Databases with SQL, Harvard University (2026)
  - Machine Learning in Production, DeepLearning.AI (2026)
  - Introduction to Statistics, Stanford Online (2025)
  - Probability & Statistics for Machine Learning & Data Science, DeepLearning.AI (2025)
  - Deep Learning Specialization, DeepLearning.AI (2024)
  - Calculus: MITx 18.01.1x and 18.02.1x, verified (2020–2021); Mathematics for Machine Learning: Multivariate Calculus, Imperial College London (2021)
- Self-study: MIT OCW 6.041 Probabilistic Systems Analysis (2026), with worked problem sets

Verification links for each certificate are on [rjln.dev](https://rjln.dev/#education).
