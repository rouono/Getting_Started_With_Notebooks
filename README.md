# Getting Started With Jupyter Notebooks for Teaching and Learning

Jupyter notebooks are an exciting new way of delivering rich, interactive content to students via a web browser, as well as a powerful tool for direct authoring of rich and interactive media components with little or no programming skill required.

The contents of this library provide an introduction to Jupyter notebooks and an overview of how they are already being used to support teaching in the OU. Whilst notebooks started out in the OU as a means of providing students with an interactive, browser based environment for running live programming code in support of OU computing courses, we also show how they can be used as a rich medium for direct authoring of a wide range of interactive materials in departments and subject areas across the university without any programming knowledge required at all, just a *gung ho* attitude towards making minor edits where you can predict what the change will do.

So it's not just computing and science courses that can benefit from using notebooks to support teaching or course production... If you want to embed interactive, customised maps in your course materials, there are simple ways of doing that. If you get tired of creating the same diagrams over and over again, with many changes to labels or layout, let the computer do it instead. If you want to embed musical scores - or listen to them play out - the notebooks can help you there too (or at least, they will as soon as Microsoft catch up with the rest of the world and update some of the necessary packages).

Jupyter notebooks run in a wide variety of environments, from your desktop to different services all over the web, which means there's a wide range of possibilities for how we actually present them to students. But for now, Azure notebooks provide one of the easiest ways of getting started.

If you click on a notebook (`.ipynb`) link in the *Microsoft Azure Notebooks* file browser, you will be presented with a static HTML preview of the notebook. To run a notebook, you will need to have a copy of the notebooks in your own file area:

- log in to [notebooks.azure.com](https://notebooks.azure.com/) using `OUCU@open.ac.uk` credentials (OU staff) or create your own personal account (free);
- clone the library that can be found at [https://notebooks.azure.com/OUsefulInfo/libraries/gettingstarted](https://notebooks.azure.com/OUsefulInfo/libraries/gettingstarted)
- in your file area, click in the notebook listing to select a notebook and click run, or click the notebook link and it should start the notebook server for you.

If you're new to Jupyter notebooks, check out the *1.00 Using Jupyter Notebooks in Teaching and Learning - READ ME FIRST.ipynb* notebook first.

## How it works (Quick Techie Bit for the Geeks - Don't Worry About It!)

A notebook server session is started in a Docker container when you first run a notebook in your file area. Each running notebook is attached to its own IPython process running inside the container. If you make changes to the notebook, or create new notebooks, the updated/new notebook will be saved in your file area. At the end of the session, the notebook server container is destroyed along with all the notebook Python processes (so state is lost) but the notebook files themselves, and any rendered outputs, are preserved.

---
*To learn more, email: tony.hirst@open.ac.uk*