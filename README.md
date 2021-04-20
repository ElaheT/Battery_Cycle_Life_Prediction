# Battery_Cycle_Life_Prediction

This notebook presents a simple process for the prediction of the useful life of Li-ion batteries based on their early cycle life performance. The input features are derived from the measurement of voltage, current, time, and temperature of the batteries during the charge and discharge.

The dataset used in this project is obtained from a publicly available repository [1]. The data is collected from the cycling of 120 identical commercial LFP/graphite Li-ion batteries, using 72 different fast-charging conditions but identical discharging conditions. The cycle lives of the batteries ranged from 335 to 2237 cycles, with cycle life (or equivalently, end of life) defined as the number of cycles until 80% of nominal capacity.

In the pre-processing section, the input features for the model are described, and the functions for the processing of the raw data files to extract the features are presented. In the model section, a ridge regression model is trained to predict the end of life of the batteries based on the features derived from the first 100 cycles.

[1] Severson et al. Data-driven prediction of battery cycle life before capacity degradation. Nature Energy volume 4, pages 383–391 (2019).
