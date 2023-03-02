# CO_and_NO_Gas_Prediction
This program is a project of one of the courses in the nuclear engineering and physics engineering departments, namely artificial intelligence. The author makes a program to predict CO and NO exhaust gas at a power plant. The data used is a record of exhaust gases along with parameters that affect power plants in Turkey.

## Background
Increasing energy demand over time results in a greater negative impact on the environment. This situation is exacerbated by increasing deforestation and increasing carbon emissions. Based on the Paris Climate Change Convention, air pollution is a vital problem for life on earth. The term air pollution includes all substances that are potentially harmful to living things. Most of the air pollution is contributed by the process of burning fossil fuels used in power plants and vehicles. NOx and CO are considered as major pollutants in the atmosphere because they can cause photochemical smog, acid rain, depletion of the ozone layer, and global warming. NOx and CO gases can also cause health problems in humans when exposed to high gas concentrations.
The main source of harmful pollutants (NOx and CO) released into the atmosphere is the combustion process in the power generation industry. Therefore, there is special attention to reduce exhaust emissions from power plants (power plants). These emissions are limited to some extent by strict environmental regulations in many parts of the world. The European Union (EU) has limited exhaust emissions (for example NOx, CO and dust) by the Industrial Emissions Directive (IED) starting in 2016 for plants producing more than 50 MW of power. According to the IED, the exhaust gas concentrations of NOx and CO must be measured continuously in every combustion unit that produces 100 MW of power. NOx and CO emissions are limited to 25 ppmdv (parts per million by dry volume) when natural gas is used as fuel.
It is important to monitor the pollutant gases NOx and CO during the combustion process at the power plant. There are three solutions developed to monitor exhaust emissions from combustion units, namely periodic measurements, Continuous Emission Monitoring System (CEMS), or Predictive Emission Monitoring Systems (PEMS). Periodic measurements are generally carried out with equipment that has been calibrated by emission testing in a laboratory. Monitoring emissions with CEMS using sensor equipment installed at the measurement location. CEMS provides direct emission information from sensors in real-time. The validity of CEMS measurements depends on good sensor maintenance and calibration according to standard procedures. PEMS 2 is a system that requires the input of a process variable (eg ambient temperature, turbine pressure, etc.) and is used to predict the training model based on the data obtained to estimate the amount of emissions.

## Objective
Measurement and monitoring of CO and NOx emissions using periodic measurement methods and CEMS has the potential for data inaccuracies. The inaccuracy of the data can be caused by the failure of measuring devices or sensors to measure variable values at the test location. Therefore, to ensure the accuracy of the data, PEMS is needed to predict the amount of CO and NOx emissions based on independent process variables. PEMS prediction results will be compared with direct measurement data in the field by looking for error values. A small error value between the PEMS and CEMS methods or periodic measurements indicates that the sensor has no problems in measurement. PEMS will use one of the methods in machine learning to create a predictive model for CO and NOx emissions

## Conclusion
Based on the results of modeling carried out using the Random Forest Regression method, it can be concluded that modeling for the prediction of CO and NOx gases in power plant gas turbines using the RFR method has good accuracy. This can be seen from the MAE, MSE, and RMSE values in the test data for both gases. For CO gas, MAE is 0.01786, MSE is 0.00113, and RMSE is 0.03368. Whereas for NOx gas, MAE is 0.10916, MSE is 0.01725, and RMSE is 0.13137. The error obtained is small and close to 0 which indicates the prediction is close to the actual variable. Comparison between the results of MAE, MSE, and RMSE on test data and training data shows that the data obtained based on modeling is slightly overfitting.
