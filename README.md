# In-house Mass Spectral Library — CBIO

## Description

LC-MS/MS spectral library of in-house measured compounds, converted from
Bruker `.library` format to NIST MSP format with spectral entropy annotation.
This library is an ongoing collection and will be updated as new compounds
are measured.

## Repository Contents

| File | Description |
|------|-------------|
| `library/CBIO_Standards.library` | Original Bruker library file |
| `library/CBIO_Standards.msp` | Final NIST MSP file |


## Instrument

- **Instrument:** Bruker maXis HD (QTOF)
- **Ionization:** ESI positive and negative mode
- **MS levels:** MS1 and MS2



## MSP Format

Each entry contains the following fields:

```
Name: C9-HQ
Formula: C18H25NO
ExactMass: 271.19361442611
MW: 271
Ion_mode: POSITIVE
Spectrum_type: MS2
Instrument_type: ESI-TOF
Instrument: maXis HD
Ionization_method: ESI
PrecursorMZ: 272.2018
Precursor_type: [M+H]+
Collision_energy: 26.4577
RetentionTime: 918
InChIKey: KKRXDNYRUZGPFM-UHFFFAOYNA-N
InChI: ...
Comments: Contributor=XXX Institute
Num Peaks: 43
120.0442 0.1001
130.0652 0.2002
...
```


## License

CC0 1.0 Universal — Public Domain.
You are free to use, share, and build upon this data without restriction.
Attribution is not legally required but is appreciated — please cite the
associated publication if you use this library in your work.
