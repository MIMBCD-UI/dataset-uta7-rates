# Rates Dataset of UTA7

<img src="https://github.com/MIMBCD-UI/meta/blob/master/banners/datasets_1280x640.png?raw=true" width="100%" />

[![MIT](https://flat.badgen.net/github/license/MIMBCD-UI/dataset-uta7-rates)](https://github.com/MIMBCD-UI/dataset-uta7-rates/blob/master/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/python?style=flat-square)](https://pypi.org/)
[![Last commit](https://img.shields.io/github/last-commit/MIMBCD-UI/dataset-uta7-rates?style=flat-square)](https://github.com/MIMBCD-UI/dataset-uta7-rates/commits/master)
[![HitCount](http://hits.dwyl.io/MIMBCD-UI/dataset-uta7-rates.svg)](http://hits.dwyl.io/MIMBCD-UI/dataset-uta7-rates)
[![OpenCollective](https://opencollective.com/oppr/backers/badge.svg?style=flat-square)](#backers)
[![OpenCollective](https://opencollective.com/oppr/sponsors/badge.svg?style=flat-square)](#sponsors)
[![Gitter](https://img.shields.io/gitter/room/gitterHQ/gitter.svg?style=flat-square)](https://gitter.im/opprTeam)
[![Status](https://flat.badgen.net/github/status/MIMBCD-UI/dataset-uta7-rates)](https://circleci.com/gh/MIMBCD-UI/dataset-uta7-rates)
[![Twitter](https://flat.badgen.net/twitter/follow/opprGroup)](https://twitter.com/opprGroup)

In this repository, we present our breast cancer rates of clinicians from our [User Tests and Analysis 7 (UTA7)](https://github.com/MIMBCD-UI/prototype-breast-screening/wiki/User-Research#test-7-multi-modality-vs-assistant-chi2020-) study. The rates are representative of the number of [False-Positives and False-Negatives](https://en.wikipedia.org/wiki/False_positives_and_false_negatives) during the diagnosis of medical imaging modalities by several clinicians. The type of data included in this repository contained a narrower range of values acquired during the medical imaging diagnosis of several patients. In this repository, we provide a *dataset* measuring the number of **false-positives** and **false-negatives** during our user tests. The user tests were made in clinical institutions, where clinicians diagnose several patients without and with an *AI-Assistant* agent. For example, in these tests we used the [`prototype-multi-modality-assistant`](https://github.com/mida-project/prototype-multi-modality-assistant) repository. However, the hereby *dataset* represents the pieces of information of the [BreastScreening](https://BreastScreening.github.io/) project. This project, is a research project that deals with the use of a recently proposed technique in literature: [Deep Convolutional Neural Networks (CNNs)](https://en.wikipedia.org/wiki/Convolutional_neural_network). These deep networks will incorporate several datasets from several different modes by a User Interface (UI) implemented on our [`prototype-multi-modality-assistant`](https://github.com/mida-project/prototype-multi-modality-assistant) repository. We also have several demos to see in our [YouTube Channel](https://www.youtube.com/channel/UCPz4aTIVHekHXTxHTUOLmXw), please follow us.

<a href="https://www.patreon.com/oppr" target="_blank">
<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

## Pre-Requisites

To run the various *dataset* tools available on the `src/` directory, it is needed:

- [Python 2.6](https://www.python.org/download/releases/2.6/) or [latest](https://www.python.org/downloads/);

- The [pip](https://pypi.org/project/pip/) package management tool;

- The [`sheet-reader`](https://github.com/MIMBCD-UI/sheet-reader) (>= [v1.2.1](https://github.com/MIMBCD-UI/sheet-reader/releases/tag/v1.2.1) version) repository;

## Instructions

The instructions are as follows. We assume that you already have knowledge over [Git](https://git-scm.com/) and [GitHub](https://github.com/). If not, please follow this [support](https://guides.github.com/activities/hello-world/) information. Any need for support, just open a [New issue](https://github.com/MIMBCD-UI/dataset-uta7-rates/issues/new).

### Guidelines

We are thrilled to guide newcomers into our *dataset* repository. We want to use this repository to distribute the best data and loading pipeline for the presented *dataset*. The following guidelines will instruct how to obtain and use this data.

#### Clone

1.1. Clone the project repository:

```
git clone git@github.com:MIMBCD-UI/dataset-uta7-rates.git
```

1.2. Go inside the project folder:

```
cd dataset-uta7-rates/
```

### Install

The installation guidelines are as follows. Please, be sure that you follow it correctly.

2.1. Run the following command to install the [library](https://github.com/google/google-api-python-client) using [pip](https://pypi.org/project/pip/):

```
pip install --upgrade google-api-python-client
```

2.2. Follow the next step;

### Run

The running guidelines are as follows. Please, be sure that you follow it correctly.

3.1. Run the sample using the following command:

```
python3 src/core/main.py
```

3.2. Enjoy our source code!

### Notebooks

You can also run a Notebook to watch some of our `methods` in action. For this goal we are using the well known [Jupyter Notebook](http://jupyter.org/) web application. To run the [Jupyter Notebook](http://jupyter.org/) just follow the steps.

4.1. Get inside our project directory:

```
cd dataset-uta7-rates/
```

4.2. Run [Jupyter Notebook](http://jupyter.org/) application by typing:

```
jupyter notebook
```

> If you have any question regarding the [Jupyter Notebook](http://jupyter.org/) just follow their [Documentation](http://jupyter.org/documentation). You can also ask for help close to the [Community](http://jupyter.org/community).

## Information

As far as we have to store the presented data regarding our users results, we need to share their results with the community. This data will gave us a better understanding regarding how users are aiming to interact with our systems.

### About

For more information about the [MIMBCD-UI](https://MIMBCD-UI.github.io/) project just follow the [link](https://github.com/MIMBCD-UI/meta). Pieces of information about details of this *dataset* are also in a [wiki](https://github.com/MIMBCD-UI/dataset-uta7-rates/wiki).

### Related Repositories

The following list, represents the set of related repositories for the presented one:

- [`dataset-uta7-sus`](https://github.com/MIMBCD-UI/dataset-uta7-sus)

- [`dataset-uta7-nasa-tlx`](https://github.com/MIMBCD-UI/dataset-uta7-nasa-tlx)

- [`dataset-uta7-time`](https://github.com/MIMBCD-UI/dataset-uta7-time)

- [`dataset-uta7-rates`](https://github.com/MIMBCD-UI/dataset-uta7-rates)

### Dataset Resources

For the [User Test Analysis 7 (UTA7)](https://github.com/MIMBCD-UI/prototype-breast-screening/wiki/User-Research#test-7-multi-modality-vs-assistant-chi2020-) of this project we generated a combination of interesting [datasets](https://www.kaggle.com/MIMBCD-UI). To publish our [datasets](https://www.kaggle.com/MIMBCD-UI) we used a well known platform called [Kaggle](https://www.kaggle.com). To access our project's [Profile Page](https://www.kaggle.com/MIMBCD-UI) just follow the [link](https://www.kaggle.com/MIMBCD-UI). We are also working on several other [User Research](https://github.com/MIMBCD-UI/prototype-breast-screening/wiki/User-Research) studies, while this repository is being an important asset to them.

### Acknowledgements

We would like to convey [Google](https://google.com) from their [Google Sheets API Documentation](https://developers.google.com/sheets/api/guides/concepts). This repository source code is based on [Google](https://google.com)'s [Python Quickstart](https://developers.google.com/sheets/api/quickstart/python) guide.

### Authors

- [Francisco Maria Calisto](http://www.franciscocalisto.me/) [[Google Scholar](https://scholar.google.com/citations?user=KI0G_SUAAAAJ&hl=en) | [ResearchGate](https://www.researchgate.net/profile/Francisco_Maria_Calisto) | [GitHub](https://github.com/FMCalisto) | [Twitter](https://twitter.com/FMCalisto) | [LinkedIn](https://www.linkedin.com/in/fmcalisto/)]

### License

Copyright © 2019 [Instituto Superior Técnico (IST)](https://tecnico.ulisboa.pt/en/)

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

The [`dataset-uta7-rates`](https://github.com/MIMBCD-UI/dataset-uta7-rates) repository is distributed under the terms of both [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) and the [MIT License](LICENSE). For more information regarding the [License](LICENSE) of the hereby repository, just follow the [`LICENSE`](LICENSE) file.

## Supporting

Our organization is a non-profit organization. However, we have many needs across our activity. From infrastructure to service needs, we need some time and contribution, as well as help, to support our team and projects.

<span class="image">
  <a href="https://opencollective.com/oppr" target="_blank">
    <img src="https://opencollective.com/oppr/tiers/backer.svg" width="220">
  </a>
</span>

### Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].

<span class="image">
  <a href="graphs/contributors">
    <img src="https://opencollective.com/oppr/contributors.svg?width=890" />
  </a>
</span>

### Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/oppr#backer)]

<span class="image">
  <a href="https://opencollective.com/oppr#backers" target="_blank">
    <img src="https://opencollective.com/oppr/backers.svg?width=890">
  </a>
</span>

### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/oppr#sponsor)]

<span class="image">
  <a href="https://opencollective.com/oppr/sponsor/0/website" target="_blank">
    <img src="https://opencollective.com/oppr/sponsor/0/avatar.svg">
  </a>
</span>

<br />

<span class="image">
  <a href="http://www.fct.pt/" title="FCT" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/fct_footer.png" alt="fct" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.fccn.pt/en/" title="FCCN" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/fccn_footer.png" alt="fccn" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.ulisboa.pt/en/" title="ULisboa" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/ulisboa_footer.png" alt="ulisboa" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://tecnico.ulisboa.pt/" title="IST" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/ist_footer.png" alt="ist" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://hff.min-saude.pt/" title="HFF" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/hff_footer.png" alt="hff" width="20%" />
  </a>
</span>

#### Departments

<span class="image">
  <a href="http://dei.tecnico.ulisboa.pt" title="DEI" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/dei_footer.png" alt="dei" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://deec.tecnico.ulisboa.pt" title="DEEC" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/deec_footer.png" alt="dei" width="20%" />
  </a>
</span>

#### Laboratories

<span class="image">
  <a href="http://sipg.isr.tecnico.ulisboa.pt/" title="SIPG" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/sipg_footer.png" alt="sipg" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://welcome.isr.tecnico.ulisboa.pt/" title="ISR" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/isr-lisboa_footer.png" alt="isr" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://larsys.pt/" title="LARSys" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/larsys_footer.png" alt="larsys" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.m-iti.org/" title="M-ITI" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/iti_footer.png" alt="iti" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://www.inesc-id.pt/" title="INESC-ID" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/inesc-id_footer.png" alt="inesc-id" width="20%" />
  </a>
</span>

#### Domain

<span class="image">
  <a href="https://europa.eu/" title="EU" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/eu_footer.png" alt="eu" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.portugal.gov.pt/" title="Portugal" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/pt_footer.png" alt="pt" width="20%" />
  </a>
</span>