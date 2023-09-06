# AURIN ECALD Project
The RMIT AURIN High Impact Project, a Nationwide longitudinal database for Emerging CALD Communities and social-environmental inequalities (ECALD Database), aims to establish the first nationwide database of culturally and linguistically diverse (CALD) population changes and socio-economic data derived from five consecutive censuses, and environmental data for the corresponding census years derived from satellite. Full versions of datasets are available on the [AURIN website](https://aurin.org.au/).

Four datasets were generated and are listed below:

Dataset 1: Identified areas of Emerging CALD Communities at the SA1 level between the census years of 2001, 2006, 2011, 2016 and 2021
Dataset 2: Measures of social inequality for CALD populations derived from longitudinal census datasets of 2001, 2006, 2011, 2016 and 2021, including demographic and socioeconomic characteristics, such as education, income, and dwelling aspects for each SA1
Dataset 3: Measures of the environmental inequality among CALD populations derived from the time-series Landsat satellite images from 2001 to 2021, including land surface temperature, urban heat intensity index, NDVI (normalized difference vegetation index) and NDBI (normalized difference built-up index) for each SA1
Dataset 4: A composite integrated heat vulnerability index for CALD populations which combines heat exposure indicator, heat sensibility indicator, and heat adaptive capability indicator that is derived from the social and environmental variables in the preceding Dataset 2 and 3 in the years 2011, 2016 and 2021 for each SA1

Database workflow:

<img width="479" alt="image" src="https://github.com/WenhuiCaii/AURIN_CALD_Project/assets/112457418/95438fc3-bbfb-4688-861d-a567376992ed">

We retrieved selected Census data for 2001, 2006, 2011, 2016, and 2021, the 2021 digital boundary file for Statistical Area Level 1 (SA1), and the correspondence files for 2001-2021 from the Australian Bureau of Statistics (ABS). Based on the correspondence file, all years' data are unified to the SA1 boundary of 2021. [Here](https://github.com/WenhuiCaii/AURIN_CALD_Project/blob/11024aa33473e894379718d1e6167de492621a84/SA1%202016%20to%202021/SA1_2016_to_2021.ipynb) is a code example that uses the conversion from 2016 to 2021. 

Satellite images of Australia were calculated by [iGEE toolkit](https://kaigewang1.users.earthengine.app/view/igee-beta) and integrated heat vulnerability indices were calculated by [iHVI app](https://github.com/IGEE-IHVI/iHVI-app)
