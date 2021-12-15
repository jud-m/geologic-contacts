# geologic-contacts

This work focuses on the differences in energy fluxes, mainly Land Surface Temperature, between different bedrock areas within the Sahara region. 
The surface temperatures along a contact between igneous and sedimentary bedrock act as a proxy for the thermal properties of each bedrock type. 
Tidy-verse functions and base R were used to test statistical differences between the two sides of the contacts. 
A Man-Whitney U test was conducted, which indicated that the distributions of sedimentary and volcanic surface temperatures are significantly different (p-value < 5%). The mean volcanic surface temperature (313.3 K) is larger than the mean sedimentary surface temperature (312.1 K), suggesting that the differences can be explained by the lower albedo of the volcanic regions compared to the bright sandy regions with sedimentary bedrock.  However, the effective temperature calculation predicts a larger difference than observed in the data. This could be explained by atmospheric effects such as winds, that are not included in the simple energy model used for the calculation. A least squares analysis was performed to determine the relationship between elevation and temperature in order to assess possible confounding effects and no significant elevation-temperature relationship was shown.

Work in collaboriation with Martina Caussi & Otto Briner. 
