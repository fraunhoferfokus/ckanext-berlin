==============================================
ckanext-berlin - CKAN customization for Berlin
==============================================

This extension contains a plugin that themes CKAN for a single city. Most notably
it introduces a dataset ("package") form, that is reduced and documented,
so that city officials are guided to produce consistent metadata.


Dependencies
============

CKAN 1.4, major adjustments will be necessary to make this install look 
nice in CKAN 1.5.


Installation
============

clone this repo:
    git clone https://github.com/okfn/ckanext-berlin.git
make it a system wide python library:
    cd ckanext-berlin
    sudo python setup.py develop

adjust /etc/ckan/std/std.ini:
    ckan.plugins = std berlin

restart apache
	sudo service apache2 restart


Configuration
=============

You need to tweak this extension to use your city's district names etc.


Authors
=============

This extension was developed Fraunhofer FOKUS on behalf of the Senatsverwaltung
für Wirtschaft, Technologie und Forschung in Berlin.
Contributers are Florian Marienfeld and Philipp Lämmel.

