# Theoretical design of an axial fan for tunnel ventilation (TJHT/2/4-500-C)

## 1.-Dimensions

The reference fan is the SODECA THT/IMP-LS-UNI-50-2/4T-6-F400, a unidirectional axial jet fan with a nominal impeller diameter of 500 mm, designed for tunnel and car park ventilation.

The commercial assembly consists of a galvanized steel casing with reduced length, an axial impeller, an electric motor, silencers, a protective grille, an outlet deflector and mounting supports.

The manufacturer provides the following dimensions for the THT/IMP-LS-50 model. The symbols correspond to the dimensional drawing shown in Figure 1. All dimensions are expressed in millimetres.

<img width="1000" alt="Dimensions Fan" src="https://github.com/user-attachments/assets/c1c9b665-8b0b-4547-bff5-b25fd3dc717a" />

*Figure 1. Dimensional drawing of the SODECA THT/IMP-LS-50. All dimensions are in mm. Source: SODECA, THT/IMP technical catalogue, page 5.*

| Dimension | Value (mm) |
|-----------|--------------|
| A | 546 |
| B | 549 |
| C | 742 |
| E – Overall length | 1445 |
| L – Casing length | 1200 |
| X | 560 |
| X1 | 255 |
| Z | 778 |
| Z1 | 808 |

The nominal impeller diameter of 500 mm is used as the initial reference for the theoretical fan design. The detailed rotor geometry will be defined in the next stages of the project.

## 2.- Performance

The project uses the SODECA THT/IMP-LS-UNI-50-2/4T-6-F400 as a commercial reference for the theoretical design of an axial jet fan for tunnel ventilation. The fan generates an axial air jet that transfers momentum to the surrounding air, promoting longitudinal airflow through the tunnel.

The selected fan operates at two rotational speeds, providing different airflow rates and thrust levels. The manufacturer specifies the following performance characteristics:

| Parameter | High speed | Low speed |
|-----------|------------|-----------|
| Rotational speed (rpm) | 2915 | 1445 |
| Volumetric flow rate (m³/h) | 19700 | 9766 |
| Outlet air velocity (m/s) | 26.4 | 13.09 |
| Thrust (N) | 165 | 40.55 |

*Table 1. Performance characteristics of the SODECA THT/IMP-LS-UNI-50-2/4T-6-F400. Source: SODECA QuickFan selection software.*

For the preliminary theoretical design, the low-speed operating condition (1445 rpm) is selected as the reference point. This operating condition provides a volumetric flow rate of approximately 9770 m³/h and a jet thrust of 40.55 N.

The dynamic pressure of the air jet can be estimated using:

$$
p_d = \frac{1}{2}\rho v^2
$$

Assuming an air density of 1.2 kg/m³ and an outlet velocity of 13.09 m/s:

$$
p_d = \frac{1}{2}(1.2)(13.09)^2 \approx 103\ \mathrm{Pa}
$$

This value represents the estimated jet dynamic pressure and should not be interpreted as the total pressure rise across the fan.

Fan characteristic curves describe the relationship between pressure and airflow at a given rotational speed. They can also show how efficiency changes across the operating range.

Figure 2 illustrates this general concept. It is included as a theoretical reference and does not represent the performance of the selected SODECA fan.

<img width="329" height="297" alt="image" src="https://github.com/user-attachments/assets/dff147b8-1ce6-42f5-a30b-d37b3cbed890" />

*Figure 2. Generic fan characteristic curves.*


## 3.- Estimated power consumption

A preliminary estimate of the electrical power consumption is obtained from the reference airflow rate and the estimated dynamic pressure of the air jet.

The selected low-speed operating condition corresponds to a volumetric flow rate of 9766 m³/h, an outlet velocity of 13.09 m/s and a rotational speed of 1445 rpm.

The dynamic pressure of the jet, calculated in Section 2, is approximately 103 Pa.

The aerodynamic power associated with the air jet can be estimated as:

$$
P_{\mathrm{jet}} = Q p_d
$$

where Q is the volumetric flow rate in m³/s and p_d is the jet dynamic pressure in Pa.

Using the reference operating conditions:

$$
Q = \frac{9766}{3600} = 2.713\ \mathrm{m^3/s}
$$

$$
P_{\mathrm{jet}} = 2.713 \times 103
\approx 279\ \mathrm{W}
$$

To obtain a preliminary estimate of the electrical power consumption, an overall jet-power efficiency of 50% is assumed. This is a simplified design assumption and not a value provided by the manufacturer.

$$
P_{\mathrm{electrical,est}}
= \frac{P_{\mathrm{jet}}}{\eta_{\mathrm{overall}}}
= \frac{279}{0.50}
\approx 558\ \mathrm{W}
$$

The estimated electrical power consumption is therefore approximately 0.56 kW under the assumed efficiency.

According to the SODECA technical catalogue, the selected fan has a nominal motor power of 1.30 kW at low speed. This represents the installed motor power rating and should not be interpreted as the actual electrical power consumption at the operating point.

The estimated consumption of 0.56 kW is preliminary and will be reviewed during the next design stages.


## 4.-Applications

According to the manufacturer, the SODECA THT/IMP series consists of axial jet fans designed to generate high-velocity air jets for ventilation and smoke control in enclosed spaces, particularly car parks.

These fans transfer momentum to the surrounding air, promoting airflow over long distances without requiring conventional air distribution ductwork.

This project focuses on tunnel ventilation, using the SODECA THT/IMP-LS-UNI-50-2/4T-6-F400 as a commercial reference. In tunnels, jet fans can be used to promote longitudinal airflow, dilute pollutants during normal operation and assist smoke management in emergency situations.

The selected model is unidirectional and has an F400 classification, indicating that the commercial fan is certified for operation at 400°C for two hours according to EN 12101-3. This certification applies to the commercial product and is not claimed for the theoretical design developed in this project.

Source: [SODECA — THT/IMP Technical Catalogue](https://www.sodeca.com).

## 5.- Examples of different axial fans dedicated to tunnel ventilation

SOLER & PALAU (TJHT/2/4-500-C)
- VELOCIDAD: 1440 RPM
- PRESIÓN: 94 Pa (Ø500 mm)
- CAUDAL: 8800 m^3/h

ZITRÓN (JZp 4/H-1,5/0,37-2/4 RE F400)
- VELOCIDAD: 2845 RPM
- PRESIÓN: 220 Pa (Ø400 mm)
- CAUDAL: 8700 m^3/h

NOVOVENT (JET WINDER 4-560T-4 0.55 kW)
- VELOCIDAD: 1500 RPM
- PRESIÓN: 78 Pa (Ø490 mm)
- CAUDAL: 10087 m^3/h
