# Smart_Retention
CEE 4800 Final Project - Modeling Smart Retention Basins

This code can be used to model any retention basin of any size using regional precipitation data. It evaluates the benefit of implementing 
a smart retention basin system that uses a water level sensor and pump to intelligently manage stormwater in the event of a large precitpitaton event. It compares this system to a null model that only uses a weir to control outflow.

This code is specifically run on Washington Park lake in Albany, NY

Files in this repository: 

- Precip_data.csv : Precipitation Data from Albany Airport from 2003-2013
- Urban Stormwater Code.ipynb : Modeling Code

Instructions:

- Clone this repository:

    - git clone <repository_url> cd <repository_name>
    - Install the required Python libraries (if not already installed):
    - pip install -r requirements.txt
    - Note: The requirements.txt file should contain dependencies such as numpy, pandas, matplotlib, and scipy.

- Open the Jupyter Notebook:
    - jupyter notebook Urban Stormwater Code.ipynb
    - Follow the instructions in the notebook's markdown cells. Each section provides detailed guidance on running specific parts of the model and understanding the output.

Contact: For any questions or issues, please contact Romir Anand (ra493@cornell.edu)

