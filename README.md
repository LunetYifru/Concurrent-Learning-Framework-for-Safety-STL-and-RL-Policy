# **Concurrent Learning of Control Policy and Unknown Constraints in Reinforcement Learning**

This repository contains the code accompanying the journal submission paper on the Concurrent Learning Framework. It implements a novel approach leveraging advancements in real-time assurance monitoring, optimization, and safety in robotic systems. This project is built on Python 3.10 and utilizes a Conda environment for managing dependencies and ensuring compatibility across systems.

## Dependencies

The codebase depends on several key libraries, including modified versions of Safety Gymnasium and Omnisafe, tailored to meet the specific objectives of this research. The dependencies are as follows:

- `rtamt`
- `GPyOpt` (with `GPy`)
- Modified `Safety_gymnasium`
- Modified `Omnisafe`

## Environment Setup

To replicate the environment and run the project successfully, follow the steps outlined below. These steps assume you have Conda installed on your system. If not, please install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/individual) as per your preference.

### Step 1: Create Conda Environment

Open your terminal and execute the following command to create a Conda environment named "Concurrent Learning Framework" with Python 3.10.

```terminal
conda create -n Concurrent_Learning_Framework python=3.10

