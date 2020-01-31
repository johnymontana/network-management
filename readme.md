//name of the graph example
:name: Network Management
//graph example description
:description: Dependency and root cause analysis and more for network and IT management
//icon representing graph example
:icon: resources/network.svg
//associated search tags, separate multiple tags with comma
:tags: network-mgt,it-operations,datacenter
//graph example author
:author: Michael Hunger
//use a script to generate/process data? Set to either path for script, or false if not used
:use-load-script: scripts/network-management.cypher
//use a graph dump file for initial data set? Set to either path for dump file, or false if not used
:use-dump-file: false
//use a plugin for the database, separate multiple plugins with comma. 'public' plugins are apoc, graph-algorithms. 
//other algorithms are specified by path, e.g. apoc,graph-algorithms; Set to false if not used
:use-plugin: false
//target version of the database this example should run on
:target-db-version: 3.5.14,4.0
//specify a Bloom perspective, or false if not used
:bloom-perspective: resources/network-management.json
//guide for the graph example. Should be friendly enough to be converted into various document formats
:guide: documentation/network-management.adoc
//guide for modelling decisions. Should be friendly enough to be converted into various document formats
:model-guide: documentation/modelling-decisions.adoc

= {name} Graph Example

Description: {description}

=== Setup

This is for version: {target-db-version}

unrendered guide:{guide}
rendered guide available from: 