# Theoretical design of an axial fan for tunnel ventilation (TJHT/2/4-500-C)

## 1.-Dimensions

The reference fan is the SODECA THT/IMP-LS-UNI-50-2/4T-6-F400, a unidirectional axial jet fan with a nominal impeller diameter of 500 mm, designed for tunnel and car park ventilation.

The commercial assembly consists of a galvanized steel casing with reduced length, an axial impeller, an electric motor, silencers, a protective grille, an outlet deflector and mounting supports.

The manufacturer provides the following dimensions for the THT/IMP-LS-50 model. The symbols correspond to the dimensional drawing shown in Figure 1. All dimensions are expressed in millimetres.

<img width="382" height="137" alt="Dimensions Fan" src="https://github.com/user-attachments/assets/c1c9b665-8b0b-4547-bff5-b25fd3dc717a" />

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

The project uses the Soler & Palau TJHT/2/4-500-C as a commercial reference for the design of a reversible axial fan for tunnel ventilation. The fan produces an axial air jet that transfers momentum to the surrounding air, promoting longitudinal airflow through the tunnel.

The following preliminary design targets have been adopted by the team, as stated in the constitutive minutes:

| Parameter | Target value |
|-----------|--------------|
| Volumetric flow rate | 8800 m³/h (2.44 m³/s) |
| Estimated jet dynamic pressure | 94 Pa |
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

According to the manufacturer, the TJHT–TJHU series consists of axial jet fans intended to move large volumes of air in tunnels, enclosed car parks and other large spaces.

This project focuses on tunnel ventilation, using the TJHT/2/4-500-C as its commercial reference. The TJHT series is reversible, allowing operation in either airflow direction.

The manufacturer states that these fans are suitable for smoke extraction and operation at 400°C for two hours and 300°C for two hours. These capabilities apply to the commercial product and are not claimed for the theoretical design developed in this project.

Source: [Soler & Palau — TJHT–TJHU technical catalogue, page 1](https://solerpalau.com.br/biblioteca/produto/039/ES_TJHT-TJHU.pdf).


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
