# Developing an Image Analysis Pipeline for Insights into Symbiodiniaceae Growth and Morphology 

### Project Overview 
Welcome to the repository for the master's degree project on Symbiodiniaceae cell microscopy data, conducted using a custom-built mother machine device. Originally developed by Wang et al. in 2010, the mother machine is a microfluidic instrument designed for high-throughput tracking of individual cell lineages across multiple generations. It features a series of horizontal growth traps connected to a main trench, where a continuous flow of growth media regulates cell growth in controlled conditions.

#### Overview of the Pipeline 
![image](https://github.com/michaelkin1/Master_Thesis_Michael_Kinsella_Symbiodinium_Pipeline/assets/128709384/b4a14b42-aad2-4d32-bc40-fed69e6053e6)

### Project Goals
This project establishes the foundational framework for a JupyterLab pipeline dedicated to segmenting population-wide growth and morphological features of Symbiodiniaceae cells. As development progresses, this pipeline will evolve into a robust tool enabling future researchers to analyze Symbiodiniaceae cells under diverse environmental conditions.


### Thesis Paper
For a comprehensive understanding of this project, please refer to the master's thesis document:

- [Link to Master's Thesis on DiVA](https://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-534140)


The thesis provides detailed insights into the methodologies, experimental setup, results, and conclusions of the study on Symbiodiniaceae cells and the JupyterLab pipeline development.


### How to Use This Repository

#### Setup 
We recommend using Anaconda Navigator for managing the Python environment required for this project. Here’s how you can get started:

**Download Anaconda:** If you haven't already, download and install Anaconda from [Anaconda's official website](https://www.anaconda.com/products/distribution).

#### Cloning Repositroy and Setup for Pipeline
Start by creating a folder where you want your cloned files to be created. 

In the terminal/command prompt enter the following: 

1. Navigate to you new folder :

   ```bash
   cd path/to/your/desired/directory

2. Clone the repository:

   ```bash
   git clone https://github.com/michaelkin1/Master_Thesis_Michael_Kinsella_Symbiodinium_Pipeline.git
   cd Master_Thesis_Michael_Kinsella_Symbiodinium_Pipeline

3. Create the environment with dependencies:
  
    ```bash
    conda env create -f environment.yml
    
4. Activate your environment:
   
    ```bash
    conda activate symbiopipeline

Now open Anaconda NAvigator, choose your new 'symbiopipeline' environment, install and launch JupyterLab and follow the instructions in the notebook. 


