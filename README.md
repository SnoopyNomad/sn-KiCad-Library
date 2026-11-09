# SnoopyNomad KiCad Library

Personal KiCad 9 symbol and footprint library.

## Layout

| Path | Contents |
| --- | --- |
| `SnoopyNomad_Symbols/` | Symbol libraries (`.kicad_sym`) |
| `SnoopyNomad_Footprints.pretty/` | Footprint library |

### Symbols

| Library | Parts |
| --- | --- |
| `sn_Antenna` | RFECA3216060A1T |
| `sn_Battery` | 1043P |
| `sn_Battery_Management` | BQ76907RGRR, ETA3000D2I |
| `sn_Buffers` | SN74AHCT1G125DBVR |
| `sn_Connectors` | B02B-XASK-1, B03B-XASK-1, B05B-XASK-1, B06B-XASK-1, L-KLS1-DC-005A-2.5-5A, TYPE-C-31-M-12 |
| `sn_Device` | 0451004.MRL, 0452005.MRL, MLT-7525 |
| `sn_Diode` | BZT52C12 |
| `sn_Interface_UART` | CA-IS3080WX |
| `sn_Isolator` | EL817S1, ISO1640BDR, LTV-827S-TA1 |
| `sn_MCU` | ESP32-U4WDH |
| `sn_Reference_Current` | LM234DT |
| `sn_Regulator_Linear` | HT7333-A |
| `sn_Regulator_Switching` | TPS55289RYQR, TPS61033DRLR, TPS631000DRLR |
| `sn_Transistor_FET` | AO4407A |

### Footprints

`1043P`, `B02B-XASK-1`, `B03B-XASK-1`, `B05B-XASK-1`, `B06B-XASK-1`, `BQ76907RGRR`, `EL817S1`, `ESP32-U4WDH`, `ETA3000D2I`, `Fuse_2410`, `L-KLS1-DC-005A-2.5-5A`, `LTV-827S-TA1`, `MAX17048G+T10`, `MLT-7525`, `PEC11R-4215F-S0024`, `RFECA3216060A1T`, `TPS55289RYQR`, `TYPE-C-31-M-12`

## Use in KiCad

Clone the repository, then add the libraries from **Preferences**.

**Symbols:** Manage Symbol Libraries → add each `SnoopyNomad_Symbols/*.kicad_sym` file. Use the filename (without extension) as the nickname, for example `sn_MCU`.

**Footprints:** Manage Footprint Libraries → add the `SnoopyNomad_Footprints.pretty` folder. Nickname: `SnoopyNomad_Footprints`.

Global libraries are available in every project. Project libraries apply only to the open project.

## License

[MIT](LICENSE)
