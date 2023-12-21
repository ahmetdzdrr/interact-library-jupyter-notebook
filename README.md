# Use Interact Library in Jupyter Notebook

Explore the power of interact library in Jupyter Notebook! Enhance your data visualization and analysis using interactive widgets with this repository.

## **Table of Contents**

- [Introduction](#introduction)
- [What is Interact?](#what-is-interact)
- [Installation](#installation)
- [Usage Code](#usage)

## **What is interact?**
The `interact` library is a powerful tool for creating interactive widgets in Jupyter Notebooks using Python. It enables users to build interactive and dynamic interfaces for data visualization and analysis.

## **Installation**
To use the interact library, make sure you have the required dependencies installed. You can install them via pip using the provided requirements.txt file.

1. Clone this repository:
   ```python
   git clone https://github.com/yourusername/interact-library-jupyter-notebook.git

2. Navigate to the project directory:
   ```python
   cd interact-library-jupyter-notebook

3. Install the required dependencies:
   ```python
   pip install requirements.txt

## **Usage Code**
Here's a simple example of how to use `interact` in a Jupyter Notebook:

```python
from ipywidgets import interact

@interact
def example_function(x=(0, 10, 1)):
    print(f'Selected value: {x}')
    # Add your interactive code here
