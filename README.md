# dnet-gdup
gdup is a extension of the services included in a D-Net bundle. 

The D-Net software toolkit, is a software framework for the realization of aggregative data infrastructures (https://github.com/dnet-team/dnet-basic-aggregator), 
and gdup extends its functionalities by providing the workflows and the services implementing a Big Graph Entity Deduplication System.

# Installation requirements

gdup is a single web application that inherits the requirements of the dnet-basic-aggregator. 
On top of that its deduplication workflow are implemented as chains of Map Reduce jobs to be run on Apache Hadoop.

