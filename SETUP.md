# Setup Guide

This guide summarises the accounts and online services required for the practical exercises in the **SIOS Remote Sensing Training Course 2026**.

The practical sessions are designed to run mainly in **Google Colab**, so no local Python installation is required.

## 1. Copernicus Data Space Ecosystem

The Copernicus Data Space Ecosystem provides access to Sentinel satellite data and related services.

Create a free account at:

https://dataspace.copernicus.eu/

This account will be used to:

* search for Sentinel-2 imagery;
* access Sentinel-2 Level-2A products;
* inspect available acquisitions;
* access satellite data programmatically from Python.

Before starting the exercises, make sure that you can log in successfully.

## 2. Google Account

A Google account is required to use Google Colab and Google Earth Engine.

If you do not already have one, create an account at:

https://accounts.google.com/

## 3. Google Colab

Google Colab provides a browser-based Python environment and will be used for the practical exercises.

Open:

https://colab.research.google.com/

You do not need to install Python locally.

To open a notebook from this repository:

1. open the relevant `.ipynb` file on GitHub;
2. select **Open in Colab**, if available;
3. alternatively, open Google Colab and choose **File → Open notebook → GitHub**;
4. paste the repository URL or search for the repository name.

The notebooks may require additional Python packages. These will be installed directly within the notebook when needed.

## 4. Google Earth Engine

Google Earth Engine will be used in selected exercises for accessing and analysing satellite time series and larger image collections.

Access Earth Engine at:

https://earthengine.google.com/

To register:

1. sign in with your Google account;
2. request access to Google Earth Engine;
3. complete the registration process;
4. confirm that the Earth Engine Code Editor is available.

Code Editor:

https://code.earthengine.google.com/

Some notebooks may request authentication with your Google account when connecting to Earth Engine from Google Colab.

## 5. Recommended browser

A recent version of a web browser is recommended.

Google Chrome provides the most straightforward integration with:

* Google Colab;
* Google Earth Engine;
* Google Drive;
* GitHub.

Other modern browsers should also work.

## 6. Course repository

The course materials are organised into four modules:

1. **Optical Satellite Data: Access and Processing**
2. **Snow Cover in Arctic Vegetation Monitoring**
3. **Vegetation Time-Series Analysis and Phenology**
4. **GeoAI for Arctic Vegetation Classification**

Each module contains:

* lecture slides in PDF format;
* a practical Jupyter notebook designed for Google Colab;
* a short README describing the exercise.

## 7. Before starting an exercise

Before running a notebook, check that:

* you can log in to the Copernicus Data Space Ecosystem;
* you can open Google Colab;
* your Google Earth Engine account is active where required;
* you are signed in to the correct Google account;
* the notebook opens without errors.

Some exercises download or process satellite imagery and may take several minutes to complete depending on data availability and the current Colab environment.

## Notes

The exercises use relatively small study areas and simplified workflows so that they can be completed within the available course time.

For larger research applications, additional consideration should be given to data volume, computational resources, quality control, reproducibility and validation.
