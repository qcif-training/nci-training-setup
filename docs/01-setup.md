---
layout: default
title: NCI Setup - Jupyter Lab
permalink: /setup/
---

# NCI Setup - Jupyter Lab

As part of our partnership with NCI, QCIF is offering free foundational training workshops in applied computing topics to support researchers across Australia in tackling complex societal challenges across various scientific fields and industries.

These instructions are for the NCI-QCIF Training Partnership Project using python virtual environments to run Jupyter Notebooks on [NCI's Gadi supercomputer].


## NCI Account Setup

Sign up for an [NCI account] if you don't already have one.

Select **Projects and groups** from the left hand side menu and then select the **Find project or group** tab. Search for **cd82**, the NCI-QCIF Training Partnership Project, and ask to join.

<p align='center'>
  <img alt="NCI Find a project or group page]" src="{{ site.baseurl }}/assets/setup_my_nci_project_cd82.png" width="750"/>
</p>

## NCI Australian Research Environment (ARE)

Connect to [NCI Australian Research Environment].

Be sure you use your NCI ID (eg, ab1234) for the username and not your email address.

Under **Featured Apps**, find and click the **JupterLab: Start a JupyterLab instance** option.

<p align='center'>
  <img alt="NCI ARE JupyterLab" src="{{ site.baseurl }}/assets/setup_nci_are_mainpage.png" width="750"/>
</p>

To Launch a JuptyerLab session, set these resource requirements:

| Resource                  | Value                                          |
|---------------------------|------------------------------------------------|
| Walltime (hours)          | 5                                              |
| Queue                     | normal                                         |
| Compute Size              | small                                          |
| Project                   | cd82                                           |
| Storage                   | scratch/cd82                                   |
| **Advanced Options...**       |                                                |
| Modules                   | python3/3.12.1                                  |
| Python or Conda virtual environment base | /scratch/cd82/venv_regression |


Then click the Launch button.

This will take you to your interactive session page you will see that that your JupyterLab session is Queued while ARE is searching for a compute node that will satisfy your requirements.

Once found, the page will update with a button that you can click to **Open JupyterLab**.

Here is a screenshot of a JupyterLab landing page that should be similar to the one that opens in your web browser after starting the JupyterLab server on either macOS or Windows.

<p align='center'>
  <img alt="JupyterLab landing page" src="{{ site.baseurl }}/assets/setup_jupyterlab_landing_page.png" width="750"/>
</p>


<!-- Collect your link references at the bottom of your document -->

[NCI's Gadi supercomputer]: https://nci.org.au/news-events/events/introduction-gadi-4
[NCI account]: https://my.nci.org.au
[NCI Australian Research Environment]: https://are.nci.org.au

