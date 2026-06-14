# American Airlines GraphQL Schema

## Overview

This conceptual GraphQL schema models the American Airlines travel and flight API domain. It covers the full lifecycle of air travel including flight search, booking, reservations, passenger management, AAdvantage loyalty, aircraft, airport infrastructure, and in-flight services.

The schema is derived from publicly available information about the American Airlines developer platform (https://developer.aa.com/), the AAdvantage loyalty program, and the airline's operational data capabilities documented across their developer portal and open-source tooling.

## Schema Source

- **Provider:** American Airlines
- **Developer Portal:** https://developer.aa.com/
- **Type:** Conceptual / Community-contributed
- **Base API Style:** REST (American Airlines Runway Developer API)
- **Schema Style:** GraphQL SDL (Schema Definition Language)

## Coverage

The schema includes 60+ named GraphQL types organized into the following domains:

### Flight Operations
- `Flight`, `FlightNumber`, `FlightRoute`, `FlightStatus`
- `Departure`, `Arrival`, `Gate`, `Terminal`
- `Delay`, `Cancellation`
- `Codeshare`, `OneWorldPartner`, `AlaskaPartner`

### Aircraft
- `Aircraft`, `AircraftType`
- `Seat`, `SeatMap`, `SeatAvailability`
- `Cabin`

### Passengers & Identity
- `Passenger`, `KnownTraveler`

### AAdvantage Loyalty
- `AAdvantageAccount`, `AAdvantageStatus`
- `MileageEarning`, `StatusPoint`, `MileagePoint`
- `UpgradeCertificate`, `AAdvantageAward`
- `AAdvantageStatusTier` (Gold, Platinum, PlatinumPro, ExecutivePlatinum, ConciergeKey)

### Booking & Ticketing
- `Booking`, `Reservation`, `PNR`, `Itinerary`
- `Ticket`, `ETicket`, `BoardingPass`

### Fares & Pricing
- `Fare`, `FareBasis`, `FareClass`
- `AAnytimeFare`, `SaverFare`, `SpecialFare`

### Airport & Lounge
- `Airport`, `Lounge`, `AdmiralsClub`

### Baggage
- `BaggageAllowance`, `BaggageItem`

### Ancillary Services
- `InFlightWifi`, `InFlightEntertainment`, `Meal`
- `UpgradeRequest`, `MobileKey`

### Auth & Access
- `APIKey`, `AuthToken`

## Usage

This schema is intended for:

1. **API design reference** — understanding how American Airlines travel data relates structurally
2. **Mock server setup** — generating test data for development against the Runway API
3. **GraphQL gateway layer** — wrapping American Airlines REST endpoints in a GraphQL API
4. **Client tooling** — generating typed SDKs via GraphQL code generators

## Files

| File | Description |
|------|-------------|
| `american-airlines-schema.graphql` | Full GraphQL SDL with 60+ types |
| `american-airlines-graphql.md` | This documentation file |

## References

- American Airlines Developer Portal: https://developer.aa.com/
- Flight Engine Mock API: https://github.com/AmericanAirlines/Flight-Engine
- AAdvantage Program: https://www.aa.com/aadvantage
- American Airlines GitHub: https://github.com/AmericanAirlines
- Runway Developer Platform (Backstage): https://github.com/AmericanAirlines/backstage
