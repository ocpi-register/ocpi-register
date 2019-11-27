The goal of this project is to provide a way to discover the location of every charge point across all networks and operators by maintaining a register of federated open [OCPI Location module](https://github.com/ocpi/ocpi/blob/master/mod_locations.asciidoc) API implementations.

[https://char-gy.github.io/ocpi-register/register.json](https://char-gy.github.io/ocpi-register/register.json)

## Why

So far the industry has been unable provide a sustainable and reliable central repository of charge points. The source of funding, the scope of the service, conflicting corporate interests, and data formats have all slowed progress.

*A federated model* - A [federated architecture](https://en.wikipedia.org/wiki/Federated_architecture) distributes the complexity and therefore the cost.

*Open locations as a minimum* - The minimum requirement to use a charge point is to know where and what it is. Not even dynamic status/occupancy data is an absolute requirement. Other modules provided by an operator may require authorisation, but the locations must be available without authorisation.

*OCPI* - The module approach allows an operator to implement the minimum requirement - location data - without building out the dynamic data or roaming aspects, keeps costs low for small operators and allows businesses to avoid features incompatible with their strategy.

## How to contribute

Create an [issue](https://github.com/char-gy/ocpi-register/issues) or a [pull request](https://github.com/char-gy/ocpi-register/pulls).
