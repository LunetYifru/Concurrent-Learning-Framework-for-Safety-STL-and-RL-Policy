# **Concurrent Learning of Control Policy and Unknown Constraints in Reinforcement Learning**

# **Concurrent Learning Framework**

This repository contains the code accompanying the journal submission paper on the Concurrent Learning Framework. It implements a novel approach leveraging advancements in real-time assurance monitoring, optimization, and safety in robotic systems. This project is built on Python 3.10 and utilizes a Conda environment for managing dependencies and ensuring compatibility across systems.

## Dependencies

The codebase depends on several key libraries, including modified versions of Safety Gymnasium and Omnisafe, tailored to meet the specific objectives of this research. The dependencies are as follows:

- [`rtamt`](https://github.com/nickovic/rtamt.git)
- [`GPyOpt` ](https://github.com/SheffieldML/GPyOpt.git)
- Modified [`Safety_gymnasium`](https://github.com/PKU-Alignment/safety-gymnasium.git)
- Modified [`Omnisafe`](https://github.com/PKU-Alignment/omnisafe.git)

## Environment Setup

To replicate the environment and run the project successfully, follow the steps outlined below. These steps assume you have Conda installed on your system. If not, please install [Anaconda](https://www.anaconda.com/products/individual).

### Step 1: Create Conda Environment

Open your terminal and execute the following command to create a Conda environment named "Concurrent Learning Framework" with Python 3.10 and activate environemnet.

```terminal
conda create -name Concurrent_Learning_Framework python==3.10
conda activate Concurrent_Learning_Framework
```

### Step 2: Install Dependencies

With the environment activated, install the required libraries using pip. Here's how to install each:

#### rtamt

To install `rtamt`, run the following command. Ensure to replace `<rtamt git repository URL>` with the actual URL of the rtamt repository:

```terminal
pip install "git+rtamt git repository URL>](https://github.com/nickovic/rtamt.git"
```

#### GPyOpt and GPy

`GPyOpt` can be installed directly via pip, which will also install `GPy` as a dependency:

```terminal
pip install GPyOpt
```

#### Safety Gymnasium and Omnisafe

For the modified versions of Safety Gymnasium and Omnisafe, we first install the currently available versions of these packages. 
```terminal
pip install safety_gymansium
pip install omnisafe
```

### Step 3: 
Replace the `Omnisafe` and `Safety_gymnasium` packages installed by the modified versions provided in the folders given in this repository. These should be placed in the "Site-packages" of your Conda environment to ensure proper integration. 
 
## Running the Project

To run the project, navigate to the project's root directory followed by the case study you are interested in running and `run<nameofcasestudy>.py` in the appropriate directory. For example, to run Safe Navigation Circle (SNC) Experiment, in the appropriate directory, run:
```terminal
python runSNC.py
```
## License

[MIT License](LICENSE)

## Contact

For any queries regarding this project, please contact lay0005@mix.wvu.edu and we'll get back to you as soon as possible. 



