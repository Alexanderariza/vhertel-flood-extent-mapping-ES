<p><center> <img src="resources/header.png" width="1000"/> </p></center>

# Práctica recomendada para el mapeo de inundaciones en imágenes de radar Sentinel-1

<p><center> <img src="resources/example.png" width="1000"/> </p></center>

***

El objetivo de esta [práctica recomendada](https://un-spider.org/advisory-support/recommended-practices) es determinar la extensión de las áreas inundadas. Mediante el uso de imágenes satelitales de radar de apertura sintética (SAR) para el mapeo de la extensión de las inundaciones. Esta práctica, constituye una solución viable para el procesamiento rápido de imágenes Sentinel-1, ya que proporciona información de inundaciones casi en tiempo real a las agencias de ayuda para apoyar la acción humanitaria. La alta confiabilidad de los datos, así como la ausencia de restricciones geográficas y la accesibilidad a las zonas afectadas, enfatizan el potencial de esta tecnología.

This [Jupyter Notebook](https://github.com/vhertel/flood-extent-mapping/blob/main/flood-extent-mapping.ipynb) covers the full processing chain from data query and download up to the export of a final flood mask product by utilizing open access Sentinel-1 SAR data. The tool's workflow follows the UN-SPIDER Recommended Practice on [Radar-based Flood Mapping](https://un-spider.org/advisory-support/recommended-practices/recommended-practice-radar-based-flood-mapping) and is illustrated below. More detailed information regarding user inputs and processing steps can be found within the Jupyter Notebook.

<p><center> <img src="resources/english/chart_readme.png" width="1000"/> </p></center>

An alternative version has been optimized for the use with Google Colab. As a cloud computing-based environment for Jupyter Notebooks, it takes advantage of external technical resources and thus allows this tool to be applied using devices with limited computing power, including phones and tablets, and in areas with scarce bandwidth. This version can directly be accessed and used by clicking the icon below. <br />

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vhertel/flood-extent-mapping/blob/main/colab/flood-extent-mapping-colab.ipynb)

***

# Tutorial

The tool's workflow is demonstrated using the example of the Ulua Basin, Honduras, after the tropical cyclone Eta with Sentinel-1 data from November 11, 2020. [Click here](https://youtu.be/TYm7hxg3SHg) to see the full tutorial.

<p align="center"> <img src=resources/tutorial.gif width="800"> </p>

*This tool was created to support the [UN-SPIDER Knowledge Portal](http://www.un-spider.org/).*  <br />

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
