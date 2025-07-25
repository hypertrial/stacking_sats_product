# Stacking Sats Calculator

**Showcasing Stacking Sats - An optimized Bitcoin DCA open source beta model by [Hypertrial.ai](https://www.hypertrial.ai)**

A web application demonstrating our intelligent Bitcoin Dollar-Cost Averaging strategy that uses 200-day moving average analysis to optimize purchase timing and allocation.

## About Stacking Sats

Stacking Sats is Hypertrial.ai's open source beta model that enhances traditional DCA by:

- **Smart Timing**: Analyzes Bitcoin price relative to 200-day moving average
- **Dynamic Allocation**: Increases purchases when Bitcoin is undervalued
- **Risk Management**: Maintains your monthly budget while optimizing entry points

For the complete backtesting framework and strategy development: [stacking_sats_pipeline](https://github.com/hypertrial/stacking_sats_pipeline)

## Quick Start

```bash
npm install
npm run dev:strict  # Recommended: Development with strict TypeScript checking
```

Open `http://localhost:3000` to try the calculator.

### Development Options

- `npm run dev:strict` - **Recommended**: Runs dev server with real-time TypeScript error checking
- `npm run dev` - Standard development mode
- `npm run type-check` - Manual TypeScript type checking
- `npm run type-check:watch` - Continuous TypeScript checking

## Usage

1. Enter your monthly DCA budget
2. Get optimized daily purchase recommendations
3. See how the model adjusts allocation based on market conditions

## Build for Production

```bash
npm run build  # Runs TypeScript compilation + Vite build
npm run lint   # Check code quality and unused variables
```

## Disclaimer

This is a beta model for educational and demonstration purposes. Not financial advice. Cryptocurrency investments carry significant risk.

## License

Open source - see LICENSE file for details.