# Investigating Netflix Movies
<br />
<p align="center">
  <a href="https://github.com/jgome284/Investigating-Netflix-Movies">
    <img src="images\netflix.jpg" alt="Logo" width="465" height="262">
  </a>

  <h3 align="center">Foreword</h3>

  <p align="center">
    A project demonstrating data exploration and visualization techniques to draw insights into whether movie duration times have decreased on Netflix.
    <br />
    <a href="https://github.com/jgome284/Investigating-Netflix-Movies/issues">Report Bug</a>
    ·
    <a href="https://github.com/jgome284/Investigating-Netflix-Movies/issues">Request Feature</a>
  </p>
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents
<div style='text-align:'>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#environment">Installation</a></li>
        <li><a href="#dependencies">Dependencies</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project
[Investigating Netflix Movies](https://github.com/jgome284/Investigating-Netflix-Movies)

What started in 1997 as a DVD rental service has since exploded into the largest entertainment/media company by market capitalization, boasting over 200 million subscribers as of January 2021. Netflix has a large number of movies and series available on it's platform that are ripe for analysis. In [this notebook](notebook.ipynb), data visualization and exploration techniques are used to test the hypothesis that movie durations on netflix have decreased.

<!--
You can include tables or images to summarize your results when and if appropriate.
-->

<!-- GETTING STARTED -->
## Getting Started

To recreate this project locally, you can clone this repository via HTTPS as follows.

```sh
git clone https://github.com/jgome284/Investigating-Netflix-Movies.git 
```
### Environment
Virtual environments are a great way to keep your system-wide Python installation clean and organized. Each virtual environment is isolated from the others, so changes you make to the packages in one virtual environment will not affect the packages in another virtual environment. This can help to prevent conflicts between packages that are used by different projects.

**Create**

 You can create a virtual environment named my_env to manage this projects dependencies, for example. To do so, run the following command:
```sh
python3 -m venv my_env
```

**Activate**

To activate the virtual environment, run the following command:
```sh
source my_env/bin/activate
```

**Deactivate**

To deactivate the virtual environment, run the following command:
```sh
deactivate
```

### Dependencies
Python version 3.9.6 was used to run this analysis. To install additional dependencies, run the following command:
```sh
pip install -r requirements.txt
```
Best practice is to install these dependencies into an activated virtual environment. ```pip``` should be smart enough to handle dependencies between all packages required during installation.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.