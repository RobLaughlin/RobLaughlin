# Robert Laughlin

Data analyst and analytics engineer working in SQL, Python, dbt, and BigQuery, with a strong probability and statistics foundation.

Tacoma, WA · Open to remote work and relocation to Iowa · [LinkedIn](https://www.linkedin.com/in/robert-laughlin-9008b0323/) · [Email](mailto:robertlaughlin253@gmail.com)

## Now

- Building a public Polk County residential-sales pipeline: ingestion → BigQuery → a documented dbt star schema
- Studying applied statistics: inference, then regression
- Open to data analyst, BI, analytics engineering, and junior data engineering roles

## Projects

### [Polk County Ingestion Pipeline](https://github.com/RobLaughlin/polk-county-ingestion-pipeline) (in progress)

`Python` `SQL` `dbt` `BigQuery` `Cloud Storage` `Terraform` `Docker`

- Terraform provisions a Cloud Storage bucket and a BigQuery dataset; dbt profile and source configuration are generated from Terraform outputs.
- A Dockerized Python job downloads the Polk County Assessor's yearly residential-sale CSVs with retries, uploads only new or changed files (MD5 comparison), and loads them into a raw BigQuery table.
- Next: dbt staging models and a star schema with key, relationship, and row-count tests.

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

- **Data:** SQL (window functions, joins and row grain, as-of logic), dbt, BigQuery, pandas, NumPy
- **Statistics:** probability, random variables and distributions, LLN/CLT, descriptive statistics and EDA
- **Engineering:** Python, TypeScript and React, C++, Terraform, Docker, Git, Linux

## Education

- Coursework toward a B.S. in Data Science, City University of Seattle (100 quarter credits)
- Self-study: MIT 6.041 Probabilistic Systems Analysis (worked problem sets), MITx 18.01.1x and 18.02.1x calculus (verified certificates), Stanford Introduction to Statistics, DeepLearning.AI Deep Learning Specialization
