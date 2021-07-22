# Timezone board
By Gabriel C. Ullmann, 2021

## About
Timezone board to help me follow contacts around the world

## How to use?
Open timezones.html on browser and inform the link to a JSON file with the structure below. Timezones names must follow IANA standards: https://en.wikipedia.org/wiki/List_of_tz_database_time_zones

    [
        {
            "name": "Jane Doe"
            "company": "Example.inc"
            "country": "England"
            "timezone": "Europe/London"
        },
        {
            "name": "Gabriel Ullmann"
            "company": "Empresa Ltda."
            "country": "Brazil"
            "timezone": "America/Sao_Paulo"
        }
    ]