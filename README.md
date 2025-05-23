# man-certificate-policies

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Welcome to the APNF MAN Certificate Policies repository.

The APNF MAN platform is responsible for the generation of STI certificates to service providers
in order to sign their calls per the STIR/SHAKEN standard.

The generation of these STI certificates complies with a Certificate Policy that can be found in this repository.


## Certificate Policies extension in STI certificate

Each STI certificate generated by the MAN platform shall include the version
of the Certificate Policy it relies on. This information is stored in the
"Certificate Policies" extension of the certificate.

Note that first STI certificates generated by the MAN platform do not have such
extension available. These certificates rely on Certificate Policy, version 1.0.


## Certificate Policy OIDs

An OID is assigned to each version of the Certificate Policy. These OIDs use the format
`1.2.250.1.695.1.1.X.Y`, where `X.Y` corresponds to the version 1.0.


# Licensing

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
