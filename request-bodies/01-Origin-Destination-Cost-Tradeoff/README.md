# Origin Destination and Waypoints

The `/origin-destination-waypoints` endpoint provides route details, toll information, fuel costs, etc., about a particular route by specifying its origin and destination and a list of waypoints. Some examples for the different ways a request to this endpoint can be customized are as follows:


| ID | Name                                        | Request                                | Response                                  |
|----|---------------------------------------------|----------------------------------------|-------------------------------------------|
| 01 | Address as String                           | [View](./01-Origin-Destination-Cost-Tradeoff/01-address-as-string.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/01-address-as-string.json) |
| 01b | Address as Geocoordinates                 | [View](./01-Origin-Destination-Cost-Tradeoff/01b-address-as-geocoordinates.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/01b-address-as-geocoordinates.json) |
| 01c | Address as ZIP Codes                       | [View](./01-Origin-Destination-Cost-Tradeoff/01c-address-as-zip-codes.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/01c-address-as-zip-codes.json) |
| 02 | Add Waypoints                               | [View](./01-Origin-Destination-Cost-Tradeoff/02-add-waypoints.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/02-add-waypoints.json) |
| 03 | Specify Map Providers                       | [View](./01-Origin-Destination-Cost-Tradeoff/03-specify-map-providers.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/03-specify-map-providers.json) |
| 04 | Specify Departure Time                      | [View](./01-Origin-Destination-Cost-Tradeoff/04-specify-departure-time.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/04-specify-departure-time.json) |
| 05 | Specify Currency                            | [View](./01-Origin-Destination-Cost-Tradeoff/05-specify-currency.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/05-specify-currency.json) |
| 06a | Specify Vehicle Type                       | [View](./01-Origin-Destination-Cost-Tradeoff/06a-specify-vehicle-type.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/06a-specify-vehicle-type.json) |
| 06b | Height-Based Toll                          | [View](./01-Origin-Destination-Cost-Tradeoff/06b-height-based-toll.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/06b-height-based-toll.json) |
| 06c | Weight-Based Toll                          | [View](./01-Origin-Destination-Cost-Tradeoff/06c-weight-based-toll.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/06c-weight-based-toll.json) |
| 07a | Specify Fuel Costs                         | [View](./01-Origin-Destination-Cost-Tradeoff/07a-specify-fuel-costs.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/07a-specify-fuel-costs.json) |
| 07b | Specify Fuel Efficiency                    | [View](./01-Origin-Destination-Cost-Tradeoff/07b-specify-fuel-efficiency.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/07b-specify-fuel-efficiency.json) |
| 08 | Receive Turn-by-Turn Instructions           | [View](./01-Origin-Destination-Cost-Tradeoff/08-receive-turn-by-turn-instructions.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/08-receive-turn-by-turn-instructions.json) |
| 09 | Receive State Mileage and Toll Distances     | [View](./01-Origin-Destination-Cost-Tradeoff/09-receive-state-mileage-and-toll-distance.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/09-receive-state-mileage-and-toll-distance.json) |
| 10 | Add Driver Costs                            | [View](./01-Origin-Destination-Cost-Tradeoff/10-add-driver-costs.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/10-add-driver-costs.json) |
| 11 | Receive Hours of Service                    | [View](./01-Origin-Destination-Cost-Tradeoff/11-receive-hours-of-service.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/11-receive-hours-of-service.json) |
| 12 | Receive EV Locations on the Route           | [View](./01-Origin-Destination-Cost-Tradeoff/12-receive-ev-locations-on-the-route.json) | [View](../../responses/01-Origin-Destination-Cost-Tradeoff/12-receive-ev-locations-on-the-route.json) |