
Headergen is a Jupyter Notebook extension designed to help convert undocumented notebooks into well-documented ones by generating and managing headers automatically.

Prerequisites

Before you begin, make sure you meet the following requirements:

Python 3.x installed on your system.

Jupyter Notebook version 6.x.x. Jupyter Notebook version 7.x is not supported for now.

Installation

To install and use the headergen-extension Jupyter Notebook extension, follow the instructions below:

Step 1: Install the Extension

To install the extension from PyPI, simply run the following command:

pip install headergen-extension

This will install the extension and all necessary dependencies directly from PyPI.

Step 2: Enable the Extension

After installing, you need to install and enable the extension in your Jupyter Notebook environment. Run the following command:

jupyter nbextension install headergen_extension --py --sys-prefix
jupyter nbextension enable headergen_extension --py --sys-prefix

Step 3: Start Jupyter Notebook

Once everything is installed and enabled, start Jupyter Notebook by running:

jupyter notebook

This will open the Jupyter interface in your browser.
