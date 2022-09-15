# Workflows 

This repo contains workflows using different workflow managers: KNIME and Snakemake.

# KNIME (outdated and archived)

KNIME workflows for use with OpenMS.

To download a specific file, please click on it and then click on the 'Raw' button.

The KNIME workflows in this repository is archived and most likely outdated. Very old KNIME and OpenMS versions might have been used.
Use at your own risk.

Please see our [Tutorials](https://github.com/OpenMS/Tutorials) for maintained basic workflows
and the KNIME Hub for community-maintained more complex KNIME workflows (e.g., [here](https://hub.knime.com/openms-team) or [here](https://hub.knime.com/search?q=openms&type=all&sort=best))

# Snakemake

[Snakemake](https://snakemake.readthedocs.io/en/stable/) is a workflow manager implemented and distributed via python, that allows the ease of scaling up workflows from single-core machines to large compute clusters. Snakemake follows the philosophy of human reable workflows that are easy to implement and allow for interoperatability when re-analyzing data, or moving to a different computing system. [1] Furthermore, workflows are set up as a list of rules to run, which can generate directed acyclic graphs to identify which rules have dependencies of prior rules exectuing successfully before self execution. This makes snakemake ideal for running pipelines for analyzing mass spectrometry data, because it allows for mutiple analyses to be run in parallel for many MS experiment files across several computing nodes.

See the **snakemake** folder for workflows for analyzing MS data.