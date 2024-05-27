# Quantum-TLCM


**Authored by:**
- Susanna Caroppo
- Giordano Da Lozzo
- Giuseppe Di Battista

This repository contains the code and data used for the experiments presented in the paper "[Quantum Graph Drawing](https://link.springer.com/chapter/10.1007/978-981-97-0566-5_4)", which was accepted at [WALCOM 2024](https://www.kono.cis.iwate-u.ac.jp/~yamanaka/walcom2024/accepted.html). The experiments focus on solving the Two-Level Crossing Minimization Problem using a D-Wave hybrid solver.

## Contents

- `experimental_dataset.txt`: Contains the datasets used in the experiments.
- `Two_Layer_Crossing_Minimization.py`: Contains the scripts and source code to run the experiments.

## Requirements

To run the code in this repository, you will need:

- D-Wave Ocean SDK
- Other dependencies listed in `requirements.txt`

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/s-caro/Quantum-TLCM.git
    cd quantum-graph-drawing
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the experiments**:
    ```bash
    python run_experiments.py
    ```

## Reproducing the Experiments

To reproduce the experiments as described in the paper, follow the steps outlined in the `run_experiments.py` script. Detailed instructions and parameters used for each experiment can be found in the script comments.

## Contact

For any questions or issues, please contact:

- Susanna Caroppo - susanna.caroppo@uniroma3.it
