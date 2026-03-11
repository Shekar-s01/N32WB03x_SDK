# N32WB03x SDK – Setup Guide

# Overview
This repository contains the N32WB03x SDK, including firmware, middleware components, utilities, and example projects for development and evaluation.

To build and run the SDK projects, please install the required development tools and follow the setup instructions below.

# Required Software
1) Keil MDK-ARM

This SDK is intended to be built using Keil MDK-ARM.

Download Link: https://www.keil.com/download/product/

Install a version supporting ARM Cortex-M series.
A valid license may be required for full project builds.
Evaluation version can be used for testing and development.

# Getting Started

## Step 1 – Clone the Repository
git clone https://github.com/BIMATIX/N32WB03x_SDK.git

## Step 2 – Open a Project in Keil

Launch Keil uVision

Click Project → Open Project

Navigate to:
projects/<example_project>/keil/

Open the .uvprojx project file

## Step 3 – Build the Project

Select the correct target configuration

Click Project → Rebuild All

## Step 4 – Program the Device

Connect the debugger

Click Flash → Download

# Folder Structure

N32WB03x_SDK/
│
├── firmware/        → Core device drivers and firmware source files
├── middlewares/     → Protocol stacks and middleware components
├── utilities/       → Helper libraries and support utilities
├── projects/        → Example applications and Keil project files


# Folder Description

firmware  
Contains low-level drivers, peripheral control code, and device-specific firmware.

middlewares  
Includes protocol stacks, libraries, and higher-level components used by applications.

utilities  
Common helper functions, tools, and reusable modules shared across projects.

projects  
Ready-to-build example applications with Keil project files.


# Notes

Ensure the correct device is selected in Keil project settings.

Use example projects inside the projects folder as a reference for new development.

All required core files and libraries are included within the SDK.

---

## Support

**Bimatix Private Limited**
Website: [https://www.bimatix.com](https://www.bimatix.com)
