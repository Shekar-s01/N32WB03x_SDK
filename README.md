# N32WB03x SDK – Setup Guide

## Overview

This repository contains the N32WB03x SDK, including firmware, middleware components, utilities, and example projects for development and evaluation.

To build and run the SDK projects, please install the required development tools and follow the setup instructions below.

---

## Required Software

### 1) IAR Embedded Workbench for ARM

This SDK is intended to be built using **IAR Embedded Workbench for ARM**.

**Download Link:**
[https://www.iar.com/embedded-development-tools/iar-embedded-workbench-for-arm](https://www.iar.com/embedded-development-tools/iar-embedded-workbench-for-arm)

* Install a version supporting ARM Cortex-M series.
* A valid license may be required for full project builds.
* Trial version can be used for evaluation.

---

## Getting Started

### Step 1 – Clone the Repository

```bash
git clone https://github.com/BIMATIX/N32WB03x_SDK.git
```

### Step 2 – Open a Project in IAR

1. Launch IAR Embedded Workbench
2. Click **File → Open → Workspace**
3. Navigate to:

```
projects/<example_project>/iar/
```

4. Open the `.eww` workspace file

### Step 3 – Build the Project

* Select the correct target configuration
* Click **Project → Rebuild All**

### Step 4 – Program the Device

* Connect the debugger
* Click **Download and Debug**

---

## Folder Structure

```
N32WB03x_SDK/
│
├── firmware/        → Core device drivers and firmware source files
├── middlewares/     → Protocol stacks and middleware components
├── utilities/       → Helper libraries and support utilities
├── projects/        → Example applications and IAR workspaces
```

### Folder Description

* **firmware**
  Contains low-level drivers, peripheral control code, and device-specific firmware.

* **middlewares**
  Includes protocol stacks, libraries, and higher-level components used by applications.

* **utilities**
  Common helper functions, tools, and reusable modules shared across projects.

* **projects**
  Ready-to-build example applications with IAR project files.

---

## Notes

* Ensure the correct device is selected in IAR project settings.
* Use example projects inside the `projects` folder as a reference for new development.
* All required core files and libraries are included within the SDK.

---

## Support

**Bimatix Private Limited**
Website: [https://www.bimatix.com](https://www.bimatix.com)
