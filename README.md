# Comparing Blood Pressure measurements

A fun repo to share results comparing two devices to measure Blood Pressure.

## Methods

I compared [Garmin Index BPM](https://www.garmin.com/en-US/p/716808) vs Greater Goods Balance [Smart Blood Pressure Monitor Model 0604](https://greatergoods.com/service/0604)

* I took 3X readings with each device each morning before eating, drinking, or exercising.
* I took the readings in my left arm.
* 3X readings replications were taken with 1 min interval in between readings for each device.
* Mean of the the 3X readings was recorded and reported in the `data` folder.

## Notes

* Claimed accuracy for Garmin Index BPM:
   * Blood pressure: ± 3 mmHg or ± 2%
   * Pulse: ± 5%
* Claimed accuracy for Greater Goods Balance Smart Blood Pressure Monitor Model 0604:
   * Blood pressure: ± 3mmHg
   * Pulse value: ± 5%

## Overview of main branches:
`main` branch is the most recent "production" version

`dev` branch is a preview of the next release which should be functional and error/bug free, but proceed with caution

## Repository Structure

* **project**:
    * **data**:
      * raw: Raw data goes here.
      * processed: Data outputs and data derivatives
    * **src**: R files here, R markdown documents explaining the analysis, SQL queries, Jupyter Notebooks.
    * **report**: Script outputs (eg. cleaned data and figures)
