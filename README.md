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

Options:
  1. Show all products (faster, but some may not be available)
  2. Validate product availability first (slower, but shows only working products)


