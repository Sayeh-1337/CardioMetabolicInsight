# Cardiometabolic Risk Analysis

This project conducts an exploratory data analysis on risk factors for heart attacks and diabetes.

## Tutorial Video
Watch this YouTube video for a tutorial and overview explanation of the data analysis:

[Cardiometabolic Risk Analysis Tutorial](https://youtu.be/ro-0rbS6to4)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Anaconda distribution installed to create virtual environments and manage packages. You can download it from [here](https://www.anaconda.com/products/distribution).

### Setting Up

1. **Clone the repository**

    Open your terminal and clone this repository by running:

    ```bash
    git clone https://github.com/Sayeh-1337/CardioMetabolicInsight.git
    ```

2. **Create a Conda virtual environment**

    Navigate into the cloned project directory and create a new Conda environment by running:

    ```bash
    cd CardioMetabolicInsight
    conda create --name env_name python=3.x
    ```

    Replace `env_name` with your preferred name for the virtual environment, and `3.x` with your preferred Python version (e.g., `3.7`).

3. **Activate the virtual environment**

    Activate the created virtual environment by running:

    ```bash
    conda activate env_name
    ```

    Replace `env_name` with the name of the virtual environment you created.

4. **Install required packages**

    Install the required packages by running:

    ```bash
    conda install pandas numpy matplotlib seaborn scikit-learn plotly scipy sweetviz
    ```

5. **Launch Jupyter Notebook**

    Start Jupyter Notebook by running:

    ```bash
    jupyter notebook
    ```

    This will open a new tab in your web browser where you can navigate to the notebook file (`analysis_script.ipynb`) and open it.

## Running the Notebook

Follow the instructions in the notebook to run the cells and perform the analysis.

## Built With

* Python
* Jupyter Notebook
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-Learn
* Plotly
* SciPy
* Sweetviz

## Authors

* **Sayeh-1337**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.