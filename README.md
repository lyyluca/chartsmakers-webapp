# ChartsMakers

ChartsMakers is a lightweight, privacy-first web utility that allows users to create standard statistical and data charts instantly in their browser. No signups, no paywalls, and zero server-side data collection.

## The Problem
Most online chart makers require account registration, charge subscription fees for high-res exports, or upload raw data to their servers. This is highly problematic when dealing with sensitive, proprietary, or academic datasets.

## Features
- **100% Privacy**: All data parsing and image rendering happen entirely client-side. Your data never leaves your browser.
- **Diverse Chart Types**: Support for Histograms, Box Plots, Scatter Plots, Pie Charts, Dot Plots, Sankey Diagrams, and Cleveland Dot Plots.
- **Easy Customization**: Adjust dimensions, margins, colors, and fonts in real-time.
- **High-Res Export**: Download your finished charts instantly as crisp, high-resolution PNGs or clean SVGs.

## Tech Stack
- Frontend: React.js, Tailwind CSS
- Data Parsing: PapaParse
- Mathematical Scaling: D3.js (modular packages)
- Image Processing: HTML5 Canvas API

## How to Use
1. Visit [chartsmakers.com](https://chartsmakers.com).
2. Select your desired chart type from the sidebar.
3. Paste your raw data or upload a CSV file.
4. Customize the colors, axis labels, and sizing.
5. Click "Save Image" to export your chart instantly.