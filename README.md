# oci-autonomous-db-sec-posture
Checks for Autonomous DB's in all regions and compartments for a tenancy and provides security posture info
Autonomous Database Security Posture Script

Installation
Download the python script: wget https://raw.githubusercontent.com/Halimer/oci-scripts/master/cloud_guard/all_detectors_responders.py
Create a virtual environment: python3 -m venv oci_scripts_venv
Source the environment: source oci_scripts_venv/bin/activate
Install the dependences: pip3 install oci
Running the script on a local machine
Source the environment: source oci_scripts_venv/bin/activate
Run the script: python3 autonomous_db_security_posture.py
Running the script in Cloud Shell
Source the environment: source oci_scripts_venv/bin/activate
Run the script: python3 autonomous_db_security_posture.py -dt
