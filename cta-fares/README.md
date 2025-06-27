# CTA fares data

## TODO

* Finish implementing CTA fare rules
* Add transfers to Pace and Metra
* Make script to maintain `route_networks.txt`
  * Manually list the 'L' lines and put everything into the bus network
* Make script to maintain `areas.txt`
  * Put everything except O'Hare Blue Line station into the main farezone `cta`

## Notes and questions

### Fare media

* Should Ventra Cards and bankcards on Google Pay/Apple Pay be given separate categories in fare_media.txt?

### Fare products

* Single-ride tickets can be purchased up to 90 days before they're used, and are valid for entering at O'Hare, but the cost to buy them is higher at O'Hare
  * Meanwhile, single-ride fare by Ventra or bankcard is higher entering at O'Hare
* Fare products involving Metra are not included in the list

### route_networks.txt

* Soldier Field Express is not included because it's not in routes.txt
