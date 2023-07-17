# Repo Installation

"""This page is still under construction"""

For Rocky 8 and 9, `dnf install rocky-release-hpc` will install the required repos

# Slurm installation:

For Rocky 9: `dnf install slurm22` or `dnf install slurm23`

For Rocky 8: you need to enable PowerTools repo first, then `dnf install slurm22` or `dnf install slurm23`

Slurm is divided into multiple packages, so `dnf search slurm` might be a good idea to fetch whatever packages you need
