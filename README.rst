Structured Random Model for Fast and Robust Phase Retrieval
===========================================================

This repository contains the source code for the paper submission "Structured Random Model for Fast and Robust Phase Retrieval" to ICASSP2025.

Overview
--------

Our work presents a novel model for phase retrieval, offering both speed and robustness. The implementation is based on the open-source computational imaging library `deepinv <https://github.com/deepinv/deepinv>`_.

Repository Structure
--------------------

- ``experimental/paper/scripts/``: Contains scripts for data generation
- ``experimental/paper/notebooks/``: Includes Jupyter notebooks for figure generation

Getting Started
---------------

1. Clone the repository:
   
   .. code-block:: bash

      git clone https://github.com/zhiyhucode/structured_random_phase_retrieval.git
      cd structured_random_phase_retrieval

2. Install the required dependencies:
   
   To install the dependencies, we kindly ask you to refer to the `deepinv documentation <https://deepinv.github.io/deepinv/>`_.

3. Navigate to the scripts directory to generate data, e.g.:
   
   .. code-block:: bash

      cd experimental/paper/scripts
      python pseudorandom_spectral.py

4. Use the notebooks in ``experimental/paper/notebooks/`` to reproduce the figures from the paper.

Contributing
------------

We welcome contributions to improve the code or extend the research. Please submit a pull request or open an issue for any bugs or feature requests.

License
-------

This project is licensed under the BSD 3-Clause License - see the ``LICENSE`` file for details.

Citation
--------

If you use this code in your research, please cite our paper:

.. code-block:: bibtex

   @misc{hu2024structuredrandommodelfast,
      title={Structured Random Model for Fast and Robust Phase Retrieval}, 
      author={Zhiyuan Hu and Julián Tachella and Michael Unser and Jonathan Dong},
      year={2024},
      eprint={2409.05734},
      archivePrefix={arXiv},
      primaryClass={physics.optics},
      url={https://arxiv.org/abs/2409.05734}, 
    }
