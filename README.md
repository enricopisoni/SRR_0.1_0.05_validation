# Validation for the Source Receptor Relationships (SRR) at 0.1 x 0.05 degrees resolution

This repository contains validation results for the SHERPA SRR, developed in June 2022, at 0.1 x 0.05 spatial resolution.
In particular, the 2 subdirectories refer to PM2.5 and NO2 validation.

Validation is shown comparing EMEP and SHERPA delta concentrations (yearly averages by cell) through scatter plots (each point compares the deltas between basecase and scenario, for the 2 models), violin plots (showing the percentage error distribution between the 2 models) and maps (showing the percentage error maps). 

The filenames in the 2 subdirectories define the type of analysis, in particular using at the end of the filename the word '_scatter' (for scatter plots), '_biasP_violin' (for violin plots) and '_biasP_map' (for maps).

In terms of validation domains and scenarios, below the filename definitions:

* 'EUresults_{biasP_map/biasP_violin/scatter}.png'. Validation scenarios refers to reductions for the whole domain for NOx (scenario # 1 in the scatterplots), VOC (scenario # 2), NH3 (3), PPM (4), SO2 (5), all pollutant together (6), traffic sector reduction (10), residential sector reduction (11), industry sector reduction (12);
* 'DEresults_{biasP_map/biasP_violin/scatter}.png'. The validation scenario refers to a case where all German emissions (all pollutants) are reduced;
* 'REG*{biasP_map/biasP_violin/scatter}.png' and 'LOC*{biasP_map/biasP_violin/scatter}.png' refer to regional and local validation scenarios. The filenames here (see 'pm25' and 'no2' directories) specify the name of cities to which the scatter refers to.

For more details, please refer to the following publications:
1.   Design and implementation of a new module to evaluate the cost of air pollutant abatement measures (2022) Journal of Environmental Management, Volume 317, 115486 ( Bessagnet, B., Pisoni, E., Thunis, P., Mascherpa, A. )

2.   Application of the SHERPA source-receptor relationships, based on the EMEP MSC-W model, for the assessment of air quality policy scenarios (2019) Atmospheric Environment: X, 4, art. no. 100047 ( Pisoni, E., Thunis, P., Clappier, A )

3.   PM2.5 source allocation in European cities: A SHERPA modelling study (2018) Atmospheric Environment, 187, pp. 93-106 ( Thunis, P., Degraeuwe, B., Pisoni, E., Trombetti, M., Peduzzi, E., Belis, C.A., Wilson, J., Clappier, A., Vignati, E )

4.   Application of uncertainty and sensitivity analysis to the air quality SHERPA modelling tool (2018) Atmospheric Environment, 183, pp. 84-93 ( Pisoni, E., Albrecht, D., Mara, T.A., Rosati, R., Tarantola, S., Thunis, P. )

5.   Adding spatial flexibility to source-receptor relationships for air quality modeling (2017) Environmental Modelling & Software, Volume 90, Pages 68-77 ( Pisoni, E., Clappier, A., Degraeuwe, B., Thunis, P. )

6.   On the design and assessment of regional air quality plans: The SHERPA approach (2016) Journal of Environmental Management, 183, pp. 952-958 ( Thunis, P., Degraeuwe, B., Pisoni, E., Ferrari, F., Clappier, A. )

7.   A new approach to design source–receptor relationships for air quality modelling (2015) Environmental Modelling & Software, Volume 74, Pages 66-74 ( Clappier, A., Pisoni, E., Thunis, P. )

