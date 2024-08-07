# California IMR Dataset PII Extension

This repository contains a modified and extended version of the California Independent Medical Review (IMR) dataset, along with a Jupyter notebook that documents all changes. Original entries of the dataset are extended to contain fictional personal information about the patient.

## Data Source
The original dataset is provided by the Department of Managed Health Care, California, US. For more information, visit [CalHHS Open Data Portal](https://data.chhs.ca.gov/dataset/independent-medical-review-imr-determinations-trend). [Terms of use](https://data.chhs.ca.gov/pages/terms) apply.

## License
- The dataset is licensed under the [Open Data Commons Open Database License (ODbL)](LICENSE.ODbL).
- The code and Jupyter notebook are licensed under the [MIT License](LICENSE.MIT).

## Setup

### Step 1: Create a Virtual Environment
Ensure you have Python installed on your system. Python 3 and later include the venv module, which is used to create virtual environments. Here's how you can create a virtual environment named venv:

```bash
python3 -m venv venv
```

### Step 2: Activate the Virtual Environment
Before you can start installing packages, you need to activate the virtual environment. The activation command differs depending on your operating system.

Linux/Mac
```bash
source venv/bin/activate
```

Windows
```bash
venv\Scripts\activate
```

### Step 3: Install Requirements
With the virtual environment activated, you can now install the project's dependencies. These dependencies are listed in a file called requirements.txt. To install them, run:

```bash
pip install --no-cache-dir -r requirements.txt
```
