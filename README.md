# Reducing Service Creation Time Leveraging on Network Function Virtualization experiment descriptors



VNF Packages

For the vnf configuration; we used the ansible-charm developed under the 5GinFIRE project 
which can be accessed at the following link:

https://github.com/5GinFIRE/mano/tree/master/charms/ansible-charm

In order to ease the upload of all the vnf descriptors, we have only included the playbook used to configure each vnf 
in the charms folder, otherwise the files are too big. The other contents of the charms folder can be accessed from
the above link and replace the playbook folder with the one presented in the charms folder.

After compile the new charms folder and zip your vnf folder and its ready to be uploaded to the ETSI OSM platform


NSD Packages

Customise the given descriptor to suit your network environment and zip the entire folder and its ready for upload

NST

No need for zipping, just upload the yaml file as it is provided.
