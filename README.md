# oci-autonomous-db-sec-posture
Checks for Autonomous DB's in all regions and compartments for a tenancy and provides security posture info
Autonomous Database Security Posture Script

Installation

1. Download the python script: wget https://raw.githubusercontent.com/chad-russell-git/oci-autonomous-db-sec-posture/main/autonomous_db_security_posture.py

2. Create a virtual environment: python3 -m venv oci_scripts_venv

3. Source the environment: source oci_scripts_venv/bin/activate

4. Install the dependences: pip3 install oci

5. Running the script on a local machine

6. Source the environment: source oci_scripts_venv/bin/activate

7. Run the script: python3 autonomous_db_security_posture.py

8. Running the script in Cloud Shell

9. Source the environment: source oci_scripts_venv/bin/activate

10. Run the script: python3 autonomous_db_security_posture.py -dt
