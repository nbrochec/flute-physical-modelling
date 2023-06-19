# Flute Physical Modeling

This repository contains a Python implementation and Max patches of the flute physical modeling algorithm developed by Cook, Karjalainen, and Välimäki. The algorithm simulates the behavior and sound production of a flute, allowing you to generate realistic flute-like sounds using digital signal processing techniques.

## Contents

The repository includes the following files:

- `python/`: This directory contains the Python implementation of the flute physical modeling algorithm. The code is organized into Jupyter notebooks, which provide an interactive environment for experimenting with the algorithm and understanding its inner workings.

- `max/`: This directory contains Max patches that utilize the Python implementation to create real-time flute simulations. The Max patches provide a user-friendly interface for controlling various parameters of the flute model and generating sounds.

## Getting Started

To use the flute physical modeling algorithm, follow these steps:

1. Clone the repository to your local machine using the command: 
   ```
   git clone https://github.com/nbrc/flute-physical-modeling.git
   ```

2. Open the Jupyter notebooks in the `python/` directory to explore the Python implementation. The notebooks contain explanations, code examples.

3. Install the necessary dependencies for the Python implementation by running the following command:
   ```
   pip install -r requirements.txt
   ```

4. Launch Max and open the Max patches in the `max/` directory. These patches provide a visual interface for controlling the flute model parameters and generating flute sounds in real-time.

## Contributing

If you would like to contribute to this project, you are welcome to submit pull requests with your improvements or bug fixes. Please make sure to follow the existing code style and provide detailed descriptions of your changes.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for both personal and commercial purposes. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

The flute physical modeling algorithm implemented in this repository is based on the research and work of Perry R. Cook, Xavier Serra, Julius O. Smith III, and others. We would like to express our gratitude for their valuable contributions to the field of physical modeling synthesis.
