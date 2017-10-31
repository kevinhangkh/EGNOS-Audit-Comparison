# EGNOS-Audit-Comparison

Tool developped during Thales Alenia Space internship 2017
Audit Comparison tool

Open Audit_comparison.html with Firefox greater than 34.0

Input:
- current/audit.xml (given by the EGNOS audit tool)
- SWCF/SWCF.xml (given by EGNOS IVQ engineers)

Results displayed in two colors:
- Red for different version
- No color if version is missing in audit
- Green for same version

Comparison is done according to:
- Asset name
- EGNOS address
- File name
- File code
- Version
