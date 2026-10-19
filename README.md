# Kathmandu-PM2.5-Forecasting

Phase 1: This phase includes following processes
    1. Gathered data from https://openaq.org/ site: I downloaded CSV datasets of different places of Kathmandu i.e. Bagdol,
        Gothatar, Handigaun, Imadol, Kupondole, Lagankhel, Mid-Baneswor, Tokha and Tyanglaphat. Datasets are last one year, last one month, last 7 days and last 24 hours datasets upto date Oct 12 2026.

    2. Cleaned Data using pandas library and jupyter notebook in vs code: Data with parameter 'pm2.5' are filtered and date and time are
        seperated into different columns. Unwanted columns and null columns are removed from datasets. Then, Cleaned datasets are saved in csv format.