<!--
**bcrodrigo/bcrodrigo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<h1 align="center">Hi, I'm Rodrigo</h1>
<h3 align="center">Data Scientist based in Vancouver, Canada</h3>

## Current Projects

### [Image Classification of Forest Fires](https://github.com/bcrodrigo/capstone_project)

Using PyTorch, I trained state-of-the-art Computer Vision Models (VGG19 and ResNet18) and performed transfer learning to accurately classify images of Forest Fires. I was able to reproduce the classification metrics reported in the literature by the dataset authors.

**Tools:** PyTorch, Pandas, Matplotlib,  Streamlit
### [RAG using Ollama](https://github.com/bcrodrigo/rag_with_ollama)

Implemented a command line program to create and update a vector database locally and query it using a Large Language Model through Retrieval Augmented Generation.

**Tools:** Python, Ollama, Langchain, Chroma
## Previous Projects

### Light Scattering from Randomly-Oriented Particles

During my PhD I studied light scattering from randomly oriented particles. You can see my thesis [here](http://hdl.handle.net/1974/14915). Helical shaped particles were of particular interest because their optical properties resemble those of chiral molecules. These kinds of molecules selectively absorb circularly-polarized light according their molecular orbital asymmetry, known as chirality. This chirality assigns a 'handedness' to the molecule, and interpreting whether a molecule is right or left handed is crucial in understanding its properties such as flavour, odour, drug safety, and drug effectiveness. Additionally, the orientation of the molecule will also have an effect on the absorption spectra, so much so, that the optical response of a randomly oriented collection of molecules might look as the opposite of a single oriented molecule, leading to ambiguity in measurement interpretation.

Using numerical simulations I calculated the optical properties of randomly oriented helical particles. I also fabricated nanostructured helical columnar films, and detached the columns to create a suspension of particles in water to try to characterize the optical properties.

#### [Discrete Dipole Approximation for Light Scattering](https://github.com/bcrodrigo/OpenDDA_MPI_modifications) 

The Discrete-Dipole Approximation (DDA) is a numerical method that represents an arbitrarily-shaped particle as electric dipoles on a cubic lattice. There are many implementations, but the one I used was [OpenDDA](https://github.com/drjmcdonald/OpenDDA). In particular, I made some modifications to use the parallelized version using the Message-Passing Interface (MPI) for distributed memory clusters. You can see all the modifications I did in the [following repository](https://github.com/bcrodrigo/OpenDDA_MPI_modifications).

#### [Generating Dipole Locations for Different Particle Shapes](https://github.com/bcrodrigo/dipole_locations/tree/main)

Using Python I wrote scripts to generate different kinds of particle shapes: sphere, cylinder, helices, in order to generate input targets for OpenDDA. You can see the code in the [dipole_locations](https://github.com/bcrodrigo/dipole_locations/tree/main) repository.

<img src="/images/sphere_preview.png" alt="sphere_preview" width="150" height="auto"> <img src="/images/cylinderpreview.jpg" alt="cylinder_preview" width="150" height="auto"> <img src="/images/helixpreviewLH.jpg" alt="helix_preview" width="150" height="auto"> 

#### [Simulation Analysis](https://github.com/bcrodrigo/OpenDDA_output_parsing)

Simulation outputs were post-processed with custom Python scripts and measurable quantities were calculated. In particular, the Mueller Matrix (a 4-by-4 real valued matrix) relates the incident and scattered polarization states, and allows you to validate if the simulation outputs are correct by looking at the number of non-zero elements as well as its symmetries. Additionally, the elements of the Mueller matrix can be measured experimentally.

## Connect with me
- [Linkedin](https://linkedin.com/in/rodrigobc)

## Languages and Tools:

<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://hive.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hive/apache_hive-icon.svg" alt="hive" width="40" height="40"/> </a> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

