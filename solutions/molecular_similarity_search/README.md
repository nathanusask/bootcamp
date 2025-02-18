# Molecular Similarity Search
Drug discovery, as the source of medical innovation, is an important part of new medicine research and development. Drug discovery is implemented by target selection and confirmation. When fragments or lead compounds are discovered, similar compounds are usually searched in internal or commercial compound libraries in order to discover structure-activity relationship (SAR), compound availability, thus evaluating the potential of the lead compounds to be optimized to candidate compounds.

In order to discover available compounds in the fragment space from billion-scale compound libraries, chemical fingerprint is usually retrieved for substructure search and similarity search.
## Try notebook
In this [notebook](./1_build_molecular_search_engine.ipynb) we will be going over the code required to perform molecular search. This example uses RDKit to generate fingerprint then used Milvus and Towhee to build a system that can perform the searches.
## How to deploy
Here is the [quick start](./quick_deploy) for a deployable version of molecular search. The code for the system is in the `quick_deploy/server` and `quick_deploy/client` directories.
