# Colombia: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Colombia: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

The text read is Ley 820 de 2003 (urban housing leases) as published by the Ministerio de Vivienda; amendments after 2003 and the Código Civil and Código de Comercio rules that apply where the Act is silent were not checked. The Spanish text prevails.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Ley 820 of 10 July 2003 sets the regime for leases of urban property used as housing (Arts. 1-2). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| contract_form | Form of the contract | A housing lease may be verbal or written; the parties must agree at least on identity, the property, price, rent, payment, term and similar points (Art. 3). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| lease_term | Extension | A lease is deemed extended on the same conditions and for the same initial term if each party has met its obligations and the tenant accepts the rent adjustments allowed by the law (Art. 6). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| deposit | Ban on cash deposits | In urban housing leases the landlord may not demand cash deposits or other real security (cauciones reales) to guarantee the tenant's obligations, directly or through another person (Art. 16). A guarantee for utility bills may be required but may not exceed the value of the utility charges for the last 3 months (Art. 15). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| rent_increase | Monthly rent cap | The monthly rent set by the parties may not exceed 1% of the commercial value of the property, and the commercial value for this purpose may not exceed twice the current cadastral value (Art. 18). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| rent_increase | Annual increase cap | After every 12 months at the same price the landlord may raise rent by no more than 100% of the CPI change in the previous calendar year, provided the new rent stays within the 1% cap; the landlord must tell the tenant the amount and the date it takes effect (Art. 20). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| rent_payment | Currency | Rent may be set in any currency but is paid in Colombian pesos at the market representative exchange rate on the date the obligation arose, unless the parties agree a different date or rate (Art. 19). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |
| termination | Tenant repair deduction | Subject to Civil Code Art. 1993 and unless otherwise agreed, the tenant may deduct the cost of indispensable non-routine repairs from rent, but not more than 30% of the rent (Art. 27). | [Ministerio de Vivienda, Ciudad y Territorio (Colombia)](https://www.minvivienda.gov.co/sites/default/files/normativa/0820%20-%202003.pdf) |

## Español

**Colombia.** Datos abiertos sobre el alquiler y las obligaciones del arrendador: fianza, subida de renta, plazos de preaviso y contrato, con enlace a la fuente oficial de cada valor.

*Los datos se ofrecen tal cual, sin ninguna responsabilidad. Solo ordenamos lo que publican las fuentes oficiales. Las leyes cambian: compruebe cada valor en la fuente primaria enlazada.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `colombia_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Colombia: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-colombia-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
