# Theoretical design of an axial fan for tunnel ventilation (TJHT/2/4-500-C)

## 1.-Dimensions

The reference fan is the Soler & Palau TJHT/2/4-500-C, a reversible axial jet fan with a nominal diameter of 500 mm. The commercial assembly includes the fan casing, two circular silencers, support feet and protective grilles.

The manufacturer provides the following dimensions for the TJHT size 500. The symbols correspond to the dimensional drawing shown in Figure 1. All dimensions are expressed in millimetres.

<img width="1138" height="407" alt="image" src="https://github.com/user-attachments/assets/49007a6e-48f6-4cdc-94b1-b5ec2528a902" />
<img width="1130" height="29" alt="image" src="https://github.com/user-attachments/assets/d3cf1e19-6fbe-4e20-9304-3e0ed90f3418" />
<img width="1132" height="27" alt="image" src="https://github.com/user-attachments/assets/4cfe9d82-da63-4bdb-9ef1-4879e9105b7f" />

*Figure 1. Dimensional drawing of the TJHT series. All dimensions are in mm. Source: Soler & Palau, TJHT–TJHU catalogue, page 3*


## 2.- Performance

The project uses the Soler & Palau TJHT/2/4-500-C as a commercial reference for the design of a reversible axial fan for tunnel ventilation. The fan produces an axial air jet that transfers momentum to the surrounding air, promoting longitudinal airflow through the tunnel.

The following preliminary design targets have been adopted by the team, as stated in the constitutive minutes:

| Parameter | Target value |
|-----------|--------------|
| Volumetric flow rate | 8800 m³/h (2.44 m³/s) |
| Pressure rise | 94 Pa |
| Rotational speed | 1450 rpm |

These values define the intended operating conditions for the theoretical design. They are project specifications, rather than a verified operating point from the manufacturer's catalogue, and will be reviewed during the design calculations.

Fan characteristic curves describe how pressure varies with airflow at a given rotational speed. They can also show how efficiency changes across the operating range.

Figure 2 illustrates this general concept. It is included as a theoretical reference and does not represent the performance of the TJHT/2/4-500-C.

<img width="329" height="297" alt="image" src="https://github.com/user-attachments/assets/dff147b8-1ce6-42f5-a30b-d37b3cbed890" />

*Figure 2. Generic fan characteristic curves.*

## 3.-Estimated power consumption

A preliminary estimate of the electrical power consumption is obtained from the target airflow and pressure rise.

For this calculation, the specified pressure rise of 94 Pa is assumed to be the total pressure rise across the fan.

The power transferred to the air is:

$$
P_{\mathrm{air}} = Q \Delta p_t
$$

where Q is the volumetric flow rate in m³/s and Δp_t is the total pressure rise in Pa.
Using the project targets:

$$
Q = \frac{8800}{3600} = 2.444\ \mathrm{m^3/s}
$$

$$
P_{\mathrm{air}} = 2.444 \times 94
\approx 230\ \mathrm{W}
$$

To account for aerodynamic and motor losses, an overall efficiency of 50% is assumed for this preliminary estimate. This is a design assumption, not a value provided by the manufacturer.

$$
P_{\mathrm{electrical}}
= \frac{P_{\mathrm{air}}}{\eta_{\mathrm{overall}}}
= \frac{230}{0.50}
\approx 460\ \mathrm{W}
$$

The estimated electrical power consumption at the target operating point is therefore approximately 0.46 kW. This estimate will be revised once the pressure definition and the fan and motor efficiencies have been established.

## 4.-Applications
## 5.- Examples of different axial fans dedicated to tunnel ventilation

SODECA (THT/IMP-LS-UNI-50-2/4T-6)
- VELOCIDAD: 1445 RPM
- PRESIÓN: 103 Pa (Ø500 mm)
- CAUDAL: 9770 m^3/h

ZITRÓN (JZp 4/H-1,5/0,37-2/4 RE F400)
- VELOCIDAD: 2845 RPM
- PRESIÓN: 220 Pa (Ø400 mm)
- CAUDAL: 8700 m^3/h

NOVOVENT (JET WINDER 4-560T-4 0.55 kW)
- VELOCIDAD: 1500 RPM
- PRESIÓN: 78 Pa (Ø490 mm)
- CAUDAL: 10087 m^3/h
