Data Center Operation Optimisation
========================
## Introduction

**Data center operation management** is a combination of complex and challenging tasks.

In this scenario, there is one decision-maker responsible for managing four data centers. Each data center can contain two types of servers: CPU servers and GPU servers. The decision-maker’s goal is to maximize profit while adhering to a key constraint: each data center has a fixed slot capacity. To achieve this goal, the decision-maker can take one of four actions at each discrete time step: buy a server, move a server between data centers, maintain the current server setup, or dismiss a determined server.


[![Medium][medium-shield]][medium-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Tayerquach/data_center_operations">
    <img src="https://cdn-images-1.medium.com/max/800/0*TuT_VSZs6hE1b9cU" alt="Logo" width="300" height="180">
  </a>

  <h3 align="center">Mathematical Optimisation Problems</h3>

  <p align="center">
    Cracking Complex Challenges with Mathematics and Coding.
    <br />
    <a href="https://medium.com/@quachmaiboi/optimizing-data-center-operation-part-1-8c21cf4f9378"><strong>Explore Articles »</strong></a>
    <br />
    <br />
  </p>
</div>
<p align="right"></p>

# Built With [![Python][Python.py]][Python-url]

I use python to solve each and every problem because of those reasons:
* **For everyone**: Python is a popular programming language which is accessible to beginers and experienced programmers. 

* **Rich ecosystem of libraries**: Python has a various libraries and packages specifically designed for quantitative analysis and computing such as: NumPy, SciPy, Pandas ...

* **Data Visualisation**: Libraries like Matplotlib, Seaborn, and Plotly enable the creation of high-quality visualizations, including plots, charts, and graphs, to represent data patterns, trends, and relationships, aiding in the interpretation and communication of quantitative results.

...

We run code in [![Jupyter][jupyterlab.ipynb]][jupyterlab-url] which is a web-based user interface for Project Jupyter.
<!-- GETTING STARTED -->
# Getting Started
## Environment setup
1. Install Python (<a target="_blank" href="https://wiki.python.org/moin/BeginnersGuide">Setup instruction</a>)
2. Install Python packages
```console 
pip install -r requirements.txt 
``` 

## Problems lists
1. **`data_center_operation_part1`**: 
   - Using four actions: **buy**, **move**, **hold**, and **dismiss** to maximize profit.

2. **`data_center_operation_part2`**: 
   - Adding **price strategies** to improve utilization and increase profit.


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Most codes are inspired from this [github](https://github.com/gowen100/Jane-Street-Solutions). Thank you so much for giving me a chance to practice quantitative problems.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
[Python.py]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/

[jupyterlab.ipynb]: https://shields.io/badge/JupyterLab-Try%20GraphScope%20Now!-F37626?logo=jupyter
[jupyterlab-url]: https://justinbois.github.io/bootcamp/2020_fsri/lessons/l01_welcome.html

[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://www.linkedin.com/in/boi-mai-quach-0196b6109/

[medium-shield]: https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white
[medium-url]: https://medium.com/@quachmaiboi
