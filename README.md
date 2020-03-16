[![Build status](https://github.com/navikt/egenmeldt-sm-backendproxy/workflows/Deploy%20to%20dev%20and%20prod/badge.svg)](https://github.com/navikt/egenmeldt-sm-backendproxy/workflows/Deploy%20to%20dev%20and%20prod/badge.svg)

# egenmeldt-sm-backendproxy

## Om egenmeldt-sm-backendproxy
Denne appen setter opp en proxyapp med nginx. Prosjektet bygger og deployer et dockerimage som heter `egenmeldt-sm-backendproxy`, dette
imaget kjører opp en enkel nginx-server som proxyer alle kall videre til en api-gateway-url med en gatewaykey i header.


## Oppsett
### Api-gateway oppsett
For å sette opp api-gateway se https://github.com/navikt/api-management

## Kontakt oss
### kode/prosjektrelaterte spørsmål kan sendes til 
* Joakim Kartveit, `joakim.kartveit@nav.no`
* Andreas Nilsen, `andreas.nilsen@nav.no`
* Sebastian Knudsen, `sebastian.knudsen@nav.no`
* Tia Firing, `tia.firing@nav.no`
* Jonas Henie, `jonas.henie@nav.no`
* Mathias Hellevang, `mathias.hellevang@nav.no`

### For NAV ansatte
Vi er tilgjengelige på Slack-channel #team-sykmelding