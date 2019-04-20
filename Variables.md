# Varaibles list

Measurement variables ID | Long name | Unit | Category | Lower threshold | Upper threshold | Data type |
------- | -------- | -------- | -------- | -------- | -------- | -------- |
 | BG_light | background light | mV | atmosphere | 0.0 | double | 
 | BSC | height normalised backscatter | 10-8.m-1.sr-1 | atmosphere | double | 
 | BSC_sum | sum of detected normalised backscatter | 10-8.m-1.sr-1 | atmosphere | double | 
 | BattVolt | Battery_Voltage | V | Diagnostics | double | 
 | CBH | Cloud Base Height | m | atmosphere | 0.0 | double | 
 | CC_high | high cloud amount | %atmosphere | 0.0 | 100.0 | double | 
 | CC_low | low cloud amount | % | atmosphere | 0.0 | 100.0 | double | 
 | CC_medium | medium cloud amount | % | atmosphere | 0.0 | 100.0 | double | 
 | CLD_Cover | cloud_ cover | % | atmosphere | double | 
 | CLD_Cover_sc | cloud cover_sky_condition_algorithm | oktas | atmosphere | double | 
 | CLD_Cover_sc_L1 | cloud cover sky condition level 1 | oktas | atmosphere | 0.0 | 8.0 | integer | 
 | CLD_Cover_sc_L2 | cloud cover sky condition level 2 | oktas | atmosphere | 0.0 | 8.0 | integer | 
 | CLD_Cover_sc_L3 | cloud cover sky condition level 3 | oktas | atmosphere | 0.0 | 8.0 | integer | 
 | CLD_Cover_sc_L4 | cloud cover sky condition level 4 | oktas | atmosphere | 0.0 | 8.0 | integer | 
 | CLD_Cover_sc_L5 | cloud cover sky condition level 5 | oktas | atmosphere | 0.0 | 8.0 | integer | 
 | CLD_Height | cloud_height | m | atmosphere | double |  | 
 | CLD_Height_L1 | cloud height level 1 | m | atmosphere | 0.0 |  | double | 
 | CLD_Height_L2 | cloud height level 2 | m | atmosphere | 0.0 |  | double | 
 | CLD_Height_L3 | cloud height level 3 | m | atmosphere | 0.0 |  | double | 
 | CLD_Height_sc | cloud_height_sky condition_algorithm | m | atmosphere |  |  | double | 
 | CLD_Height_sc_L1 | cloud height sky condition level 1 | m | atmosphere | 0.0 |  |  | integer | 
 | CLD_Height_sc_L2 | cloud height sky condition level 2 | m | atmosphere |  | 0.0 |  |  | integer | 
 | CLD_Height_sc_L3 | cloud height sky condition level 3 | m | atmosphere | 0.0 |  | integer | 
 | CLD_Height_sc_L4 | cloud height sky condition level 4 | m | atmosphere | 0.0 |  | integer | 
 | CLD_Height_sc_L5 | cloud height sky condition level 5 | m | atmosphere | 0.0 |  | integer | 
 | CLD_status | cloud_detection_status |  | dimensionless |  | atmosphere |  |  | double | 
 | CO2_absorp | carbon_dioxide_absorptance | N/A | carbon_dioxide |  |  | float | 
 | CO2_absrop | carbon_dioxide_absorptance |  | dimensionless |  | carbon_dioxide |  |  | double | 
 | CT2 | temperature_structure_parameter | K-2m^2/3 | turbulence |  |  | double | 
 | CT2_BLS | BLS_temperature_structure_parameter | K-2m^2/3 | atmosphere |  |  | double | 
 | C_CO2 | carbon_dioxide_concentration | mmol.m-3 | carbon_dioxide |  |  |  |  | double | 
 | C_CO2_kg_per_kg | carbon_dioxide_concentration_kg_per_kg | kg.kg-1 | carbon_dioxide |  | double | 
 | C_H2O | water_vapour_concentration | mmol.m-3 | humidity |  | double | 
 | Cn2 | refractive_index_structure_parameter | m-2/3 | atmosphere |  | double | 
 | Cn2Max | maximum_refractive_index_structure_parameter | m-2/3atmosphere |  | double | 
 | Cn2Min | minimum_refractive_index_structure_parameter | m-2/3 | atmosphere |  |  | double | 
 | Cn2Sig | refractive_index_structure_parameter | m-2/3 | atmosphere |  |  | double | 
 | Cn2_RAW | refractive_index_structure_parameter_RAW | m-2/3 | atmosphere |  |  | double | 
 | Cn2_SigUCn2 | refractive_index_structure_parameter_UCn2Sig_method |  | m-2/3 | Optical |  |  | double | 
 | Demod | demodulated_signal | mV | atmosphere |  |  |  |  | double | 
 | DemodSig | demodulated_signal_sig | mV | atmosphere |  |  | double | 
 | DeviceTemp | device_temperature | Celsius | Diagnostics |  |  | double | 
 | FLAG | Status flag | N/A | META |  |  |  | integer | 
 | F_CO2 | upward_turbulent_carbon_dioxide_flux | umol.m-2.s-1 | turbulence | double | 
 | H2O_absorp | water_vapour_absorptance | dimensionless | humidity |  |  |  | double | 
 | H_convection | Heat_flux_free_convection | W.m-2 | turbulence |  |  | double | 
 | Hfree | upward_turbulent_sensible_heat_flux_free_convection_method | W.m-2 |  | atmosphere |  |  | double | 
 | Kdiff | diffuse_shortwave_radiation | W.m-2 | radiation | 0.0 | 1200.0 | double | 
 | Kdn | incoming_shortwave_radiation | W.m-2 | radiation | 0.0 | 1200.0 | double | 
 | Kup | outgoing_shortwave_radiation | W.m-2 | radiation |  |  | double | 
 | L | Obukhov_length | m | turbulence |  |  |  | float | 
 | Ldn | incoming_longwave_radiation | W.m-2 | radiation | 100.0 | 600.0 | double | 
 | Lup | outgoing_longwave_radiation | W.m-2 | radiation | 200.0 | 750.0 | double | 
 | PAR_W | photosynthetically_active_radiation | W.m-2 | radiation | 0.0 | 400.0 | double | 
 | PAR_umol | PAR_radiation_umol | umol.m-2.s-1 | radiation | 0.0 | 2000.0 | double | 
 | Q_E | upward_turbulent_latent_heat_flux | W.m-2 | turbulence |  |  | double | 
 | Q_H | upward_turbulent_sensible_heat_flux | W.m-2 | turbulence |  |  | double | 
 | Q_H_db | upward_turbulent_sensible_heat_flux_de_bruin_method |  | W.m-2 | turbulence |  |  | double | 
 | Q_H_fc | upward_turbulent_sensible_heat_flux_free_convection_method | W.m-2 | turbulence |  |  | double | 
 | Qstar | net_allwave_radiation | W.m-2 |  | radiation | -850.0 | 1600.0 | double | 
 | RH | relative_humidity | % | humidity | 0.0 | 100.0 | double | 
 | RH_indoor | Indoor relative humidity | % | humidity | 0.0 | 100.0 | double | 
 | RR | rain_rate | mm.h-1 | precipitation | 0.0 | 5400.0 | double | 
 | RR_acc | rain_rate_accumulation |  | mm.h-1 | precipitation |  |  | double | 
 | R_acc | accumulated_rain | mm | precipitation |  |  | double | 
 | SNR | Signal to Noise Ratio | dimensionless | Diagnostics |  |  | double | 
 | SatCorrFactor | Saturation_Correction_Factor |  | dimensionless | Diagnostics |  | double | 
 | Soil_Moist | Soil_Moisture | % | humidity | 0.0 | 100.0 |  | double | 
 | Soil_Temp | Soil_Temperature | Celsius | temperature | -30.0 | 50.0 | double | 
 | Srt | maximum_refractive_index_structure_parameter | K-2m^2/3 | atmosphere |  |  | double | 
 | Sun | sunshine_status | % | radiation | 0.0 | 100.0 | double | 
 | T_CNR | CNR_body_temperature | Celsius | META | -30.0 | 100.0 | double | 
 | T_CNR1 | CNR1_body_temperature | Celsius | radiation |  | double | 
 | T_CNR1_K | CNR1_body_temperature_kelvin | Kelvin | radiation |  |  | double | 
 | T_CNR4 | CNR4_body_temperature | Celsius | radiation |  |  | double | 
 | T_CNR_K | CNR_body_temperature_kelvin | K | temperature | -30.0 | 60.0 | double | 
 | T_Chip | Chip temperature | Celsius | Diagnostics | 0.0 | 120.0 | double | 
 | T_dew_indoor | Indoor dew point temperature | Celsius | temperature |  |  | double | 
 | Tair | air_temperature | Celsius | temperature | -30.0 | 50.0 | double |
 | Tair_K | air_temperature_kelvin | K | temperature | 243.0 | 323.0 | double | 
 | Tair_indoor | Indoor air temperature | Celsius | temperature | double | 
 | Tb | Brightness temperature | K | radiation |  |  | double | 
 | Tlaser | laser temperature | Celsius | Diagnostics |  |  | double | 
 | Tsfc | surface_temperature | Celsius | temperature |  |  | double | 
 | Tsfc_K | surface_temperature_kelvin | K | temperature |  |  | double | 
 | Tsonic | sonic_temperature | Celsius | temperature |  |  | double | 
 | Tsonic_K | sonic_temperature_kelvin | K | temperature |  |  | double | 
 | Twater | River_Thames_water_temperature | Celsius | temperature |  |  | double | 
 | UCn2 | UCn2 | m-2/3 | Optical |  |  | double | 
 | UCn2Sig | standard_deviation_UCn2 | m-2/3 | Optical |  |  | double | 
 | UDemod | demodulated_signal | mV | atmosphere |  |  | double | 
 | UVA_W | UVA_radiation | W.m-2 | radiation | 0.0 | 100.0 | double | 
 | UVA_umol | UVA_radiation_umol | mol.m-2.s-1 | radiation | 0.0 | 500.0 | double | 
 | UVB_W | UVB_radiation | W.m-2 | radiation | 0.0 | 100.0 | double | 
 | UVB_umol | UVB_radiation_umol | umol.m-2.s-1 | radiation | 0.0 | 500.0 | double | 
 | UdemodSig | demodulated_signal_sig |  | mV | atmosphere |  | double | 
 | WS | horizontal_wind_speed | m.s-1 | wind | 0.0 | 50.0 | double |
 | WS_max | Horizontal wind speed maximum |  | m.s-1 | wind | 0.0 | 50.0 | double | 
 | WS_min | Horizontal wind speed minimum | m.s-1 | wind | 0.0 | 50.0 | double | 
 | X_c | average_X_intensity_corrected | dimensionless | atmosphere |  |  | double | 
 | Y_c | average_Y_intensity_corrected | dimensionless | atmosphere |  |  | double | 
 | a | water_vapour_density | g.m-3 | humidity |  |  | double | 
 | albedo | bulk_surface_albedo | dimensionless | radiation | 0.0 | 1.0 | double | 
 | beta | height normalised backscatter | 10-8.m-1.sr-1 | atmosphere |  |  | double | 
 | beta_tR | smoothed backscatter in height and time | 10-8.m-1.sr-1 | atmosphere |  |  | double | 
 | clear | Percentage of clear sky within time frame | % | atmosphere | 0.0 | 100.0 | double |  | 
 | contamination | window contamination | mV | Diagnostics |  |  | integer | 
 | cor_c | correlation_of_X_Y |  | dimensionless | atmosphere |  |  | double | 
 | correctCn2Cov | Cn2_correction_factor_saturation_cov |  | dimensionless | atmosphere |  |  | double | 
 | correctCn2EO | Cn2_correction_factor_extinction_outer_scale | dimensionless | atmosphere |  |  | double | 
 | correctCn2Sat | Cn2_correction_factor_saturation |  | dimensionless | atmosphere |  |  | double | 
 | cov_TsonicC_CO2 | covariance_TsonicC_CO2 | K.kg.kg-1 | Eddy_Covariance |  |  | float | 
 | cov_Tsonicq | covariance_Tsonicq | K.kg.kg-1 | Eddy_Covariance |  |  | float | 
 | cov_qC_CO2 | covariance_qC_CO2 | kg2.kg-2 | Eddy_Covariance |  |  | float | 
 | cov_uC_CO2 | covariance_uC_CO2 | m.kg.s-1.kg-1 | carbon_dioxide |  |  | float | 
 | cov_uTsonic | covariance_uTsonic | m.K.s-1 | Eddy_Covariance |  |  | float | 
 | cov_uq | covariance_uq | m.kg.s-1.kg-1 | humidity |  |  | float | 
 | cov_uv | covariance_uv | m2.s-2 | Eddy_Covariance |  |  | float | 
 | cov_uw | covariance_uw | m2.s-2 | Eddy_Covariance |  |  | float | 
 | cov_vC_CO2 | covariance_vC_CO2 |  | m.kg.s-1.kg-1 | carbon_dioxide |  |  | float | 
 | cov_vTsonic | covariance_vTsonic | m.K.s-1 | Eddy_Covariance |  |  | float | 
 | cov_vq | covariance_vq | m.kg.s-1.kg-1 | humidity |  |  | float | 
 | cov_vw | covariance_vw | m2.s-2 | Eddy_Covariance |  |  | float | 
 | cov_wC_CO2 | covariance_wC_CO2 | m.kg.s-1.kg-1 | carbon_dioxide |  |  | float | 
 | cov_wTsonic | covariance_wTsonic | m.K.s-1 | Eddy_Covariance |  |  | float | 
 | cov_wq | covariance_wq | m.kg.s-1.kg-1 | humidity |  |  | float | 
 | crosswind | crosswind | m.s-1 | wind |  |  |  | double | 
 | diag | diagnostics | N/A | META |  |  |  | double | 
 | diag_pct | diagnostics_percentage | % | META |  |  | float | 
 | dir | wind_direction | degree | wind |  | 0.0 | 360.0 | double | 
 | dir_max | Wind direction maximum | degree | wind | 0.0 | 360.0 | double | 
 | dir_min | Wind direction minimum | degree | wind | 0.0 | 360.0 | double | 
 | error | error | N/A | META |  |  | integer | 
 | hail_acc | hail_accumulation |  | hits.cm-2 | precipitation |  |  | double | 
 | hail_dur | hail_duration |  | s | precipitation |  |  | double | 
 | hail_int | hail rate | hits.cm-2.h-1 |  | precipitation |  |  | double | 
 | omas | imas flag | N/A | Eddy_Covariance |  |  | integer | 
 | imas_pct | identification_microscale_anthropogenic_sources | % | Eddy_Covariance |  |  | float | 
 | nSamples | nSamples | samples/interval | META |  |  | integer | 
 | numDgnTotal | total_number_of_diagnosis_subperiods_measured | dimensionless | Diagnostics |  |  | double | 
 | numDgnValid | num_valid_diagnosis_subperiods_included |  | dimensionless | Diagnostics |  |  | double | 
 | numDgnValidCrosswind | num_valid_diagnosis_subperiods_included_crosswind |  | dimensionless | Diagnostics |  |  | double | 
 | press | barometric_pressure | hPa | atmosphere | 800.0 |  | 1200.0 | double | 
 | pulse | laser pulse energy | % | Diagnostics | 0.0 |  | integer | 
 | q | specific_humidity | kg.kg-1 | humidity |  |  | double | 
 | rain_acc | rain_acc | mm | precipitation | 0.0 | 3.0 | double | 
 | rain_dur | rain_duration | s | precipitation |  |  | double | 
 | rain_int | Rainfall intensity | hits.cm-2.h-1 | precipitation |  |  | double | 
 | receiver | receiver sensitivity | % | atmosphere |  |  |  | integer | 
 | sd_CO2_absorp | standard_deviation_CO2_absorp |  | N/A | carbon_dioxide | float | 
 | sd_C_CO2 | standard_deviation_CO2 | mmol.m-3 | carbon_dioxide |  |  | float | 
 | sd_C_H2O | standard_deviation_H2O | mmol.m-3 | humidity |  |  | float | 
 | sd_H2O_absorp | standard_deviation_H2O_absorp | N/A | humidity |  |  | float | 
 | sd_Kdiff | standard_deviation_diffuse_shortwave_radiationW.m-2 | radiation |  |  | double | 
 | sd_Kdn | incoming_shortwave_radiation | W.m-2 | radiation |  |  | double | 
 | sd_Kup | standard_deviation_Kup | W.m-2 | radiation |  |  | double | 
 | sd_Ldn | standard_deviation_Ldn | W.m-2 | radiation |  |  | double | 
 | sd_Lup | standard_deviation_Lup | W.m-2 | radiation |  |  | double | 
 | sd_PAR_W | standard_deviation_photosynthetically_active_radiation_W | W.m-2 | radiation |  | double | 
 | sd_PAR_umol | standard dev PAR_umol | umol.m-2.s-1 | radiation |  |  | double | 
 | sd_Qstar | standard_devation_net_allwave_radiation | W.m-2 | radiation |  |  | double | 
 | sd_RH | Standard deviation relative humidity | % | humidity |  |  | double | 
 | sd_T_CNR | standard_deviation_T_CNR1_C | Celsius | radiation |  |  | double | 
 | sd_T_CNR_K | Standard deviation air temperature CNR body temperature Kelvin | Kelvin | radiation |  |  | double | 
 | sd_Tair | Standard deviation air temperature | Celsius | temperature |  |  | double | 
 | sd_Tsonic | standard_deviation_Tsonic | Celsius | Eddy_Covariance |  |  | float | 
 | sd_UVA_W | standard_deviation_UVA_radiation_W | W.m-2 | radiation |  |  | double | 
 | sd_UVA_umol | standard_deviation_UVA_umol | umol.m-2.s-1 | radiation |  |  | double | 
 | sd_UVB_W | standard_deviation_UVB_radiation_W | W.m-2 | radiation |  |  | double | 
 | sd_UVB_umol | UVB_radiation_umol | umol.m-2.s-1 | radiation |  |  | double | 
 | sd_WS | Horizontal wind speed standard deviation | m.s-1 | atmosphere |  |  | double | 
 | sd_albedo | standard_deviation_bulk_surface_albedo | dimensionless | radiation |  |  | double | 
 | sd_press | Standard deviation barometric pressure | hPa | atmosphere |  |  | double | 
 | sd_q | standard_deviation_q | kg.kg-1 | humidity |  | float | 
 | sd_u | standard_deviation_u | m.s-1 | Eddy_Covariance |  |  | float | 
 | sd_v | standard_deviation_v | m.s-1 | Eddy_Covariance |  |  | float | 
 | sd_w | standard_deviation_w | m-2/3 | Eddy_Covariance |  |  | float | 
 | sigCrosswind | standard_deviation_crosswind | m.s-1 | wind |  |  | double | 
 | sigXn_c | standard_deviation_of_X_intensity | dimensionless | atmosphere |  |  | double | 
 | sigYn_c | standard_deviation_of_Y_intensity | dimensionless | atmosphere |  |  | double | 
 | spike | spike_flag | N/A | Eddy_Covariance |  |  | integer | 
 | spike_pct | spike_percentage | % | humidity |  |  | float | 
 | sun_status | Sunshine status | N/A | radiation |  |  | double | 
 | t_dew | Dew point temperature | Celsius | temperature |  |  | double | 
 | tilt | tilt angle | degree | Diagnostic |  |  | double | 
 | tol_F_CO2 | tolerance_F_CO2 | umol.m-2.s-1 | Eddy_Covariance |  |  | float | 
 | tol_Q_E | tolerance_Q_E | W.m-2 | Eddy_Covariance |  |  | float | 
 | tol_Q_H | tolerance_Q_H | W.m-2 | Eddy_Covariance |  |  | float | 
 | tol_WS | tolerance_WS | m.s-1 | Eddy_Covariance |  |  | float | 
 | tol_dir | tolerance_wind_direction | degree | Eddy_Covariance |  |  | float | 
 | tol_ustar | tolerance_ustar | m.s-1 | Eddy_Covariance |  |  | float | 
 | transmission | window transmission | % | Diagnostics | 0.0 |  | integer | 
 | u | zonal_wind_component | m.s-1 | wind |  |  | float | 
 | ustar | friction_velocity | m.s-1 | turbulence |  |  | double | 
 | uv_index | Ultraviolet index | N/A | radiation |  | double | 
 | v | meridional_wind_component | m.s-1 | wind |  | float | 
 | vis_z | vertical_visibility | m | atmosphere |  | double | 
 | vis_z_max | maximum visibility | m | atmosphere | 0.0 |  | double | 
 | w | Vertical wind component | m.s-1 | wnd |  |  | float | 
 | zL | atmospheric_stability_parameter | dimensionless | turbulence |  |  | double |
