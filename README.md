# Predicting Startup Success

An RNN-based machine learning system that predicts U.S. tech startup success (defined as achieving Series B funding or acquisition) using sequential funding event data. The model processes a startup's funding history and characteristics to estimate its probability of future success.

## Overview

This MVP project implements a sequential deep learning approach to startup success prediction, focusing on:

- Sequential modeling of funding rounds using RNN/LSTM architecture
- Early-stage startups (Seed to Series A)
- U.S.-based technology companies
- Binary classification (success/failure prediction)

### Key Features

- Temporal analysis of funding events
- Integration of static and dynamic features
- Handling of class imbalance (~15% success rate)
- Time-based validation approach

### Data Sources

Primary data from publicly available sources:
- Crunchbase dataset snapshots
- Kaggle startup datasets
- U.S. startup ecosystem data

## Project Structure

### Data and Models
- `/data` - Preprocessed datasets and features
- `/models` - Trained model checkpoints and configurations
- `/notebooks` - Jupyter notebooks for analysis and training

### Documentation
- `Search_report.pdf` - Detailed analysis report
- `requirements.txt` - Python dependencies
- `LICENSE` - Project license information

## Getting Started

### Prerequisites

To run this project, you'll need:

- Python 3.x
- Required Python libraries (requirements.txt will be provided)
- Basic understanding of data science and machine learning concepts

## License

This project is licensed under the terms provided in the LICENSE file.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Authors

- Tenzin Jampa

## Acknowledgments

Special thanks to all contributors and data providers that made this analysis possible.
