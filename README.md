Red Hat Certified Engineer - Practice Test
===========================================

DESCRIPTION
------------

This is a practice test I created along with the answer sheet for the RHCE 7 exam. Using this practice test I was able to successfully complete the exam and become a Red Hat Certified Engineer.

This practice exam tries to cover all aspects of the test but please understand that it will not cover everything as I witnessed first hand when taking the exam. So I recommend that you have previously studied all of the [RHCE Objectives](https://www.redhat.com/en/services/training/ex300-red-hat-certified-engineer-rhce-exam) prior to using this practice test to prepare for the exam.

Good Luck!


REQUIREMENTS
------------

* 3 CentOS / RHEL 7.1 Servers named krbserver, krbclient, and storage
	* [CentOS 7.1 ISOs](http://vault.centos.org/7.1.1503/isos/x86_64/)
	* [Red Hat Developer Program](https://developers.redhat.com/)
* 20GB Hard Drive on each Server
* Additional 2GB Hard Drive on Storage
* 2 NIC cards on each server

INSTALLATION
------------
* Install the server with 'Server with GUI' option
* After booting install vim and bash-completion
* Refer to documents on how to configure KRB Server for Practice Test
* Configure hosts file on each of your systems
* On krbserver create a directory on root called RHCE_LAB and copy the tls certs from your workstation that will be used in the Practice Test

Additional Information
-------------

For my internal network I utilize the 10.0.50.x network so you will need to substitute your network for the 10.0.50.x network for the steps to work properly.

AUTHOR
------
MogiePete
