# QRADAR_to_MISP
Pull information from QRadar reference sets and add them ass attributes to an event in MISP. Currently there is no direct way to integrate QRadar data with MISP events. This script will allow for reference sets to be regularly queried and if there are new values update the event with new attributes. 

The main use case for this is leveraging QRadars ability to pull data from STIX/TAXII endpoints. QRadar will populate reference sets and then with this script we can pull that feed straight into MISP for corolation and easy searching


# Useage

After cloning the repository, update servers.conf with the appropriate addresses and keys.

To set up an integration, run integration_adder.py which will walk you through addign the neccessarry information, validating it along the way

After you have an integration setup, you can 
