![Hackathon-banner](/image001.jpg)
# CENTURI Hackathon 2023 For quantitative biology

This is the GitHub repository for the [CENTURI Hackathon 2023 For quantitative biology].

<!-- <img src="/profile/images/poster.jpg" alt="Hackathon-poster" width="200"/> -->

## Welcome to the second CENTURI Hackathon!

During this weekend, you will be working in groups of _5 to 7_ people. In order to make
everything running as smoothly as possible, it is important to identify the different
problems that you will be working on and to split the team members across these specific
tasks.

To help you identifying the problems to solve and organizing your weekend Road Maps have
been designed for each project. Moreover, the project heads together with the organisers
are here to help you. The road maps can usually be found in your GitHub repositories as
issues.

## Slack
A slack workspace have been created for the hackathon with channels dedicated to each
project and also more general channels. If you are not in the slack workspace, please contact
one of the organizers (Florence, Philippe or Léo).

## GitHub
To keep the code organized, we encourage you to use GitHub though it is not mandatory.
In order to be able to access and modify the repositories of your project, please reach out
to one of the organizers through the github-request channel of the slack (you will need a github
account to be able to get access).

You should be able to find the repositories dedicated to your project here.

Here is the mapping of the project names to the repository names:
<!-- - High-throughput tracking of bacteria: [bacteria-tracking]
- It's like riding a bike!: [bike-riding]
- BioImageIt project: [bio-image-it]
- Visualizing heart development from 3D volumetric images: [heart-visualisation]
- FreeCAD - Open Lab Frame: [FreeCAD_OpenLabFrame]
- Optimal frame sampling with Robotic Microscopy: [optimal-frame-sampling]
- Visualizing fast cellular movements in the Placozoa: [placozoa-tracking]
- Correlating optical images and mechanical maps: [project-corima]
- Open source syringe driver: [syringe-driver]
-->
In general, the specifics are described within the repository of each project.

## Resources

You can find below some ressources about different topics.

### GitHub
- [Version control with git](https://swcarpentry.github.io/git-novice/) (standard
git information)
- [Git cheat sheet](https://www.git-tower.com/blog/git-cheat-sheet/) (git cheat sheet)
- [Oh Shit Git](https://ohshitgit.com/) (how to fix git mistakes)

### Python
- [Introduction to Python](https://guignardlab.github.io/CenTuri-Course-2022/1-Introduction-to-Python/Resources/1-Variables.html)
- [Introduction to numpy](https://numpy.org/doc/stable/user/quickstart.html)
- [Matplotlib cheatsheet](https://github.com/matplotlib/cheatsheets)

## Troubleshooting

### Installing dependencies on Mac M1 chips
It can be troublesome to install some Python libraries on Mac M1 chips.
One workaround is to use [miniforge] which is a slight alternative to [miniconda].

Note that the workaround only works for `Python 3.9` and bellow and that you cannot
install the latest versions of numpy due of some unfixed denpencies to `libcblas`.

Therefore, when you create a new environement it is strongly advised to first install
the correct version of numpy (1.22.3) and then install the rest.

Moreover, it is probably safer to install with `conda` everything that can (before using
`pip`).

In other words, you can install your libraries the following way, once [miniforge] is installed:
```shell
conda create -n my_project python=3.9
conda activate my_project
conda install numpy=1.22.3
```
After that everything should be mostly working.

[...]

[CENTURI Hackathon 2023 For quantitative biology]: https://centuri-livingsystems.org/hackathon-202"/
[bacteria-tracking]: https://github.com/CENTURI-Hackathon-2022/bacteria-tracking
[bike-riding]: https://github.com/CENTURI-Hackathon-2022/bike-riding
[bio-image-it]: https://github.com/CENTURI-Hackathon-2022/bio-image-it
[heart-visualisation]: https://github.com/CENTURI-Hackathon-2022/heart-visualisation
[FreeCAD_OpenLabFrame]: https://github.com/CENTURI-Hackathon-2022/FreeCAD_OpenLabFrame
[optimal-frame-sampling]: https://github.com/CENTURI-Hackathon-2022/optimal-frame-sampling
[placozoa-tracking]: https://github.com/CENTURI-Hackathon-2022/placozoa-tracking
[project-corima]: https://github.com/CENTURI-Hackathon-2022/project-corima
[syringe-driver]: https://github.com/CENTURI-Hackathon-2022/syringe-driver
[miniforge]: https://github.com/conda-forge/miniforge
[miniconda]: https://docs.conda.io/en/latest/miniconda.html
