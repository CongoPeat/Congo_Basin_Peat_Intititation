# Congo_Basin_Peat_Intititation


Data and code required for reproducing the figures featured in the following publication:

Dargie et al. (XXXX). Timing of peat initiation across the central Congo Basin. xxxxxxxxxxxxxxxxxx

Please cite this paper if you're using any of the data or code presented here.

# Code
## SI_FIG_1_SCRIPT_GDARGIE_ET_AL.XXXX_TIMING_OF_PEAT_INITIATION_ACROSS_THE_CENTRAL_CONGO_BASIN
This file contains the R code used to produce SI Figure 1. Users will also require the following data files: "IKE1_5.0.csv" and "IKE1_5.0_DOWN_CORE_OXCAL_OUTPUT.csv"

# Data


## Figure 1 data
### Core_GeoB6518-1_delta18O_data.csv metadata
Ths file contains the extended planktic foraminifera δ18O data from marine core GeoB6518-1 presented in Figure 1 of the article.

Columns contain the following:

**Depth (cm):** This is the sample depth in centimeters.\
**Foram age (cal. yrs BP):** This is the calibrated planktic foraminifera radiocarbon age (calibrated year Before Present).\
**d18O Standard (PDB):** This is &delta;<sup>18</sup>O of the standard Vienna Pee Dee Belemnite.\
**UK37' SST:** This is the alkenone-derived sea-surface temperatures (&ordm;C).\
**d18Owater Temp. Corrected:** This is &delta;<sup>18</sup>O record of surface waters of the Congo plum after correcting for sea-surface temperatures.\
**Ice Correction Factor:** \
**d18Owater Ice Corrected:** This is &delta;<sup>18</sup>O temperature corrected record of surface waters of the Congo plum after correcting for continental ice mass.



## SI Figure 1 data
### IKE1_5.0.csv metadata
This file contains the raw data required for the Bacon age-depth model.

Columns contain the following:

**labID:** This is the unique sample identifier. This is the same as the "Sample Publication Code" in Table 1 of the article.\
**age:** This is the conventional (uncalibrated) radiocarbon age, in years Before Present.\
**error:** This is the 1 σ error. For the surface, we have arbitrarily put an error of 1 year.\
**depth:** This is the mean depth of the sample. The samples were 10 cm thick. So if a sample was from 200-210 cm, we list the depth here as 205 cm. Surface is set to zero.\
**cc:** This is the calibration curve to be used. 4=the mixed northern-southern hemisphere curve created in the corresponding R script. 0=dates are already calibrated.

### IKE1_5.0_DOWN_CORE_OXCAL_OUTPUT.csv
This file contains the OxCal output for peat core IKE1_5.0, plotted in SI Figure 1.

Columns contain the following:

**Sample:** This is the unique sample identifier. This is the same as the "Sample Publication Code" in Table 1 of the article.\
**Median:** This is the median calibrated radiocarbon age, in calibrated years Before Present, calculated in OxCal using a 50:50 northern-southern hemisphere calibration curve.\
**CI95_Min:** This is the lower 95%, or 2-sigma, confidence interval calibrated radiocarbon age, in calibrated years Before Present, calculated in OxCal using a 50:50 northern-southern hemisphere calibration curve.\
**CI95_Max:** This is the upper 95%, or 2-sigma, confidence interval calibrated radiocarbon age, in calibrated years Before Present, calculated in OxCal using a 50:50 northern-southern hemisphere calibration curve.\
**Depth:** This is the mean depth of the sample. The samples were 10 cm thick. So if a sample was from 200-210 cm, we list the depth here as 205 cm. Surface is set to zero.

### IKE1_5.0_DOWN_CORE_DATES_TABLE
This table presents information on the down core radiocarbon dates for peat core IKE1_5.0, in the same format as Table 1 in the publication.




