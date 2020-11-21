# Country Standard Numbers

![Build](https://github.com/koblas/stdnum-js/workflows/Node.js%20CI/badge.svg)

JavaScript (TypeScript) package to validate most all national numbers, with a focus on
VAT, Person and Tax identifiers.

## Supported Countries and Numbers

| Country   | Code | Name       | Group    | Meaning                                                          |
| --------- | ---- | ---------- | -------- | ---------------------------------------------------------------- |
| Andorra   | AD   | NRT        | Tax      | Tax Identifier (Número de Registre Tributari)                    |
| Albania   | AL   | NIPT       | Vat      | Vat Identifier (Numri i Identifikimit për Personin e Tatueshëm)  |
| Argentina | AR   | CBU        | Bank     | Bank Account (Clave Bancaria Uniforme)                           |
| Argentina | AR   | CUIT       | Tax      | Tax Identity (Código Único de Identificación Tributaria)         |
| Argentina | AR   | DNI        | Person   | National Identity (Documento Nacional de Identidad)              |
| Austria   | AT   | Businessid | Business | Austrian Company Register Numbers                                |
| Austria   | AT   | TIN        | Tax      | Austrian tax identification number (Abgabenkontonummer)          |
| Austria   | AT   | UID        | VAT      | Austrian VAT number (Umsatzsteuer-Identifikationsnummer)         |
| Austria   | AT   | VNR        | Person   | Austrian social security number(Versicherungsnummer)             |
| Brazil    | BR   | CPF        | Person   | Brazilian identity number (Cadastro de Pessoas Físicas)          |
| Brazil    | BR   | CNPJ       | Company  | Brazilian company number (Cadastro Nacional da Pessoa Jurídica)  |
| Chile     | CL   | RUT        | Tax      | Tax Identifier (Rol Unico Tributario) [RUN]                      |
| Columbia  | CO   | NIT        | Tax      | Tax Identifier (Número de Identificación Tributaria)             |
| Spain     | ES   | CIF        | Tax/Vat  | Tax Identifier (Código de Identificación Fiscal)                 |
| Spain     | ES   | DNI        | Person   | Identity code (Documento Nacional de Identidad)                  |
| Spain     | ES   | NIE        | Person   | Identity code foreigner (Número de Identificación de Extranjero) |
| Spain     | ES   | NIF        | Tax      | Tax Identifier (Número de Identificación Fiscal)                 |
| Mexico    | MX   | RFC        | Tax/Vat  | Tax Identifier (Registro Federal de Contribuyentes)              |
| Mexico    | MX   | CURP       | Person   | Individual Identifier (Clave Única de Registro de Población)     |
| Mexico    | MX   | CLABE      | Bank     | Bank Account (Clave Bancaria Estandarizada)                      |
| Paraguay  | PY   | RUC        | Tax/Vat  | Tax Identifier (Registro Único de Contribuyentes)                |
| Russia    | RU   | INN        | Tax/Vat  | Tax Identifier (Идентификационный номер налогоплательщика)       |

### Examples

TODO -- Usage examples

### Credits

Thanks to [python-stdnum](https://arthurdejong.org/python-stdnum/) for providing the inspiration and
many of the checksum algorithm sources

### References

https://wiki.scn.sap.com/wiki/display/CRM/Country+Tax+Category+check
