US Domestic Flights Dataset (2015–2024)

A cleaned, analysis‑ready dataset containing 63,079,446 US domestic commercial flight records from January 2015 to December 2024. This dataset is derived from the US Department of Transportation’s Bureau of Transportation Statistics (BTS) and is in the public domain. It includes standardized flight‑level information such as carriers, airports, scheduled times, distances, and cancellation indicators — ideal for machine learning, time‑series analysis, and aviation research.

Dataset Overview • Total rows: 63,079,446 • Total columns: 11 • File size: ~2.95 GB • Time span: 2015–2024 • Source: US DOT / BTS (public domain) • Format: CSV (cleaned, consistent schema)

Column Type Description YEAR int64 Year of the flight (2015–2024) MONTH int64 Month of the flight (1–12) DAY_OF_WEEK int64 Day of week (1 = Monday, 7 = Sunday) OP_UNIQUE_CARRIER object Unique airline carrier code (e.g., AA, DL, UA) ORIGIN object Origin airport IATA code DEST object Destination airport IATA code CRS_DEP_TIME int64 Scheduled departure time (HHMM, local time) CRS_ARR_TIME int64 Scheduled arrival time (HHMM, local time) CANCELLED bool Whether the flight was cancelled (True/False) CRS_ELAPSED_TIME float64 Scheduled flight duration in minutes DISTANCE float64 Distance between airports in miles
