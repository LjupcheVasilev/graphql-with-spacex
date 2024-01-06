# GraphQL API with SpaceX
This project is a simple GraphQL server that uses SpaceX and GeoDataSource APIs to fetch data about launchpads and cities.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
What things you need to install the software and how to install them:
- Node.js
- npm

### Installing
A step by step series of examples that tell you how to get a development environment running:
1. Clone the repository
2. Navigate to the project directory
3. Install the dependencies with `npm install`
4. Start the server with `npm start`

## Usage
The server provides the following GraphQL resolvers:
- `Launchpad.city`: Fetches city data based on the latitude and longitude of the launchpad.
- `Query.launchpads`: Fetches data about all SpaceX launchpads.
- `Query.launchpad`: Fetches data about a specific SpaceX launchpad based on its ID.
- `Query.city`: Fetches city data based on provided latitude and longitude.

## Built With
- Node.js
- GraphQL

## Acknowledgments
- [SpaceX API](https://github.com/r-spacex/SpaceX-API)
- [GeoDataSource API](https://www.geodatasource.com/web-service/location-search)
