# BRAKER_singularity
Singularity def file template for BRAKER
1. The GeneMark package has to be downloaded before building container.
2. Since BRAKER need to write to AUGUSTUS_CONFIG, it has to be located outside of container. The default setting in this container is AUGUSTUS_CONFIG_PATH=~/Augustus/config/. This means a manually setup of ~/Augustus/config/ is necessary.
3. Create links inside of container according to your cluster.
