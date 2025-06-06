# MatLab--project
Non-inverting operational amplifier in MATLAB

# MATLAB Project – Signal Processing and Simulation

## Overview

This repository contains MATLAB scripts and functions developed for academic purposes, primarily focused on signal processing, filtering, and mathematical modeling. The project demonstrates core concepts such as Fourier transforms, time-domain simulations, filter design, and system analysis.

It was developed as part of university coursework at the Technical University of Cluj-Napoca and is designed for educational use and experimentation.

## Features

- Custom signal generation (sine, square, composite)
- Time-domain and frequency-domain analysis
- Implementation of low-pass, high-pass, and band-pass filters
- Plotting and visualization with MATLAB’s graphical tools
- Clear documentation and modular code

## Requirements

- MATLAB R2021a or newer (older versions may also work)
- Signal Processing Toolbox (for certain scripts)

## Folder Structure

```
/MatLab--project
├── main.m                  # Main script to run all demos
├── signal_generator.m      # Function to create test signals
├── fft_analysis.m          # Fourier transform-based analysis
├── filter_design.m         # Custom FIR/IIR filter design
├── plot_utils.m            # Utility functions for plotting
└── figures/                # Generated plots and figures
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AlexandruGabrielBrabete/MatLab--project.git
   ```

2. Open MATLAB and navigate to the project directory.

3. Run the main script:
   ```matlab
   main
   ```

   This will execute a series of demos including signal generation, FFT, filtering, and visualizations.

## Notes

- You can edit `main.m` to selectively run parts of the project.
- For exporting plots, ensure the `figures/` folder has write permission or change the output path.
- Comments in the code explain each step of the signal processing workflow.

## License

This project is provided for academic and educational purposes. Distribution and reuse allowed with proper attribution.
