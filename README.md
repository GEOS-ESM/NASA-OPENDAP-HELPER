# NASA-OPENDAP-HELPER
A utility to assist the public with accessing NASA data available via OpenDAP

## Requirements

This script requires Python 3.11+ with the following packages:
- xarray
- numpy
- requests
- netCDF4

### On NASA Discover:

module load python/GEOSpyD/24.3.0-0/3.11

### On other systems
conda env create -f environment.yml

### Execution
python main.py

# From here, the script will help the user refine their download selection to only the required variables and area of interest.
# For issues and errors contact: wesley.j.davis@nasa.gov
