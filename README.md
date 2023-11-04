# GUIMemoryProfile

This is a Streamlit web app which utilizes memory_profiler Python module to help developers visualize memory usage and locate memory leaks.

# Contents

<a href=https://github.com/ShreeluSantosh/GUIMemoryProfile/edit/main/README.md#how-it-works>How it works</a><br>
<a href=https://github.com/ShreeluSantosh/GUIMemoryProfile/edit/main/README.md#modules-and-libraries-used>Modules and Libraries used</a><br>
<a href=https://github.com/ShreeluSantosh/GUIMemoryProfile/edit/main/README.md#how-to-run>How to Run</a>

# How it works

The developer can upload a Python file to the web app. The file is analyzed and executed in a sandbox environment to get more insights into full-time memory usage. 

Currently, there are two tools available:

- Line-by-line Memory Usage
![Screenshot 2023-11-04 125043](https://github.com/ShreeluSantosh/GUIMemoryProfile/assets/94289402/32189f88-1d92-43ee-9150-ba54ecf282c2)

- Plotting memory usage over time
![Screenshot 2023-11-04 125125](https://github.com/ShreeluSantosh/GUIMemoryProfile/assets/94289402/963f5265-06d9-4e37-8731-b46fddf0e613)

I plan to add more new features in near future!

# Modules and Libraries used:
- streamlit
- streamlit_extras
- memory_profiler
- matplotlib
- os
- subprocess

# How to Run

- Clone the repository
~~~
https://github.com/ShreeluSantosh/GUIMemoryProfile.git
~~~
- Install the required modules from requirements.txt
~~~
pip install -r requirements.txt
~~~
- Run the root file (Introduction.py)
~~~  
streamlit run Introduction.py
~~~
