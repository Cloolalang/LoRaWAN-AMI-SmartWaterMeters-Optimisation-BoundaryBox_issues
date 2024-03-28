This repo is under-construction.

Brief:

As part of a larger study to document system design optimisation of LoRaWAN networks for AMI water-metering (Smart water meters).

This part will address the issue of installing LoRaWAN End-devices into sub-surface meter pits / boundary boxes / meter vaults and the RF attenuating effects thereof.

Notes;

1) Boundary box phyical dimensions, materials, lids and man-hole covers.
2) Meter antenna type, placement, ground-plane, performance, de-tuning. s-paramaters, radiation pattern
3) Basic attenuation calculations
4) RF coverage planning  - recommended configuration and input data, survey test standard measurements, validation of coverage analysis.
5) Environmental variables - weather and FOD, seasonal, sand and mud inundation. grouted lids
6) End-device SF/ADR restrictions to preserve battery life, at the expence of link budget - thus forcing the requirement for lower gateway int-ersite distance, (more gateways per given geography).
7) Methods of improving link budget for this use-case, including plactic box/chamber/pit lids, through-the-lid antennas, rotaing meter position etc.
8) Effects of frost covers, meter risers etc.
9) CW testing
10) Test setup calibration, test antennas and E2E LoRaWAN network
11) Radiated field test
12) https://lora-alliance.org/wp-content/uploads/2021/05/TR007_Developing_LoRaWAN_Devices-v1.0.0.pdf
13) https://www.slcmeterllc.com/slc2017/assets/pdf/cewhite.pdf
14) Anecdotally, It appears that LoRaWAN water metering end-devices installed in sub-surface meter pits, vaults, boundary boxes at or below 500mm from the street surface level, with metal lids which are restricted to operating in EU868 regional parameters with a maximum spreading factor of SF9, with an installation margin of 10dB, will be limited to operating not greater than 250m range from a gateway site, with an omni-directional antenna mounted at 10m above ground level and a gain of 6dbi. (End-device suffers about 10dB being in the pit, and 20dB from the metal lid)
15) Max coupling loss and link budget calculations for various SF, gateway configs, etc
16) Why energy-harvesting, NB-IOT at 450MHz with steet lamp post small cells will be a better fit for SWM
17) IOT hype cycle and technological expectations
18) https://lora-developers.semtech.com/documentation/tech-papers-and-guides/predicting-lorawan-capacity
19) https://lora-alliance.org/wp-content/uploads/2019/10/Radiated-RF-Performance-FAQ.pdf
20) https://lora-alliance.org/wp-content/uploads/2019/07/rf_performance_test_report_20181206_trptis_1m2m_extended.pdf
21) https://www.youtube.com/watch?v=oI7CxF65cxY
