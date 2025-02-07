# SpikeInterface Tutorials for Oxford Cortex Club - January 2025

Material for the spike sorting/SpikeInterface training day.


**To do before the training:**

1. Install SpikeInterface, using the [installation guide](#installation) below
2. Download the [dataset for the tutorials](#dataset)



## Schedule


The best is to start with the **overview_tutorials**

  * Object interaction cookbook 15min
  * Probe handling 15min
  * Preprocessing  20min
  * Drift with generated data 20min
  * Postprocessing 20min
  * Visualization (Sortingview, Sigui) 20min
  * Metrics & Curation (Automerge, etc.) 20min
  * Sorting on your own dataset 30min



## Installation

This procedure uses the new [uv fast installer for python](https://github.com/astral-sh/uv).

**Procedure for Windows/Apple/Linux:**

1. On MacOS and Linux. Open a terminal and do $ curl -LsSf https://astral.sh/uv/install.sh | sh
1. On Windows. Open a powershell and do powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
2. exit session and log again.
3. Go to this page https://github.com/samuelgarcia/school_spike_sorting_neuralnet_saclay_2024
4. Click on **"code"** (green button) and download the zip. Etxract the zip.
5. open terminal or powershell
6. Go to the correct folder `cd C:/users/myusername/where_the_zip_is`
7. Create an empty env `uv venv si_env --python 3.11`
8. linux/macos : Activate the env `source si_env/bin/activate` (you should have (si_env) in your terminal)
8. windows : activate the env `si_env/bin/activate` (you should have (si_env) in your terminal)
9. `uv pip install -r requirements_tutorial.txt`

**Do not wait to do this during the tutorial, it can be time consuming**

For installtion, you can have more information [here](https://github.com/SpikeInterface/spikeinterface/tree/main/installation_tips)


## Dataset

Please download datasets from this link and unzip them:

https://drive.google.com/drive/folders/17RlgsMLheW82IMLMgmTFifVACebDZ8X5?usp=sharing
