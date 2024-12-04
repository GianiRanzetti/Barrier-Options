# Barrier Options Pricing

This repository was created for the Bocconi Minerva Investment Management Society. It provides tools to price **barrier options**, a class of exotic options where the payoff depends on the underlying asset's price crossing a predefined barrier level. The repository implements both **analytical methods** and **Monte Carlo simulations** for pricing these options, supporting all major barrier types.

## Barrier Options Overview

Barrier options are path-dependent and can be categorized as follows:

1. **Up-and-Out**: Activated only when the price rises above a set barrier.
2. **Down-and-Out**: Activated only when the price drops below a set barrier.
3. **Up-and-In**: Deactivated when the price rises above a set barrier.
4. **Down-and-In**: Deactivated when the price drops below a set barrier.

The repository supports both **call** and **put** options for each barrier type. With a focus on down options.

## Features

- Implementation of pricing all barrier option types using closed form solutions. Based on the formulas found in "Options, Futures, and Other Derivatives" by John C. Hull.
- Pricing Down-andIn & Down-and-Out barrier options through **Monte Carlo simulations**.
- Pricing Down-and-In barrier options using Importance sampling.

## Files in the Repository

- `BarrierOptions.ipynb`: Pricing scripts for barrier options.
- `Barrier Option Report.pdf`: Deliverable for the Minerva Society, provides theoretical context for the repo.
- `Papers Folder`: Collection of relevant Litterarture for those interested

## License

[MIT License](LICENSE)

---

This structure is user-friendly and provides clear details about the repository's purpose and usage.
