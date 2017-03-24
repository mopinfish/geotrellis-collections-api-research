# geotrellis-collections-api-research

A research project to set up and use GeoTrellis as a REST service.

### Requirements

* Docker
* Rake

### Getting started

#### Setup

Clone the project, ensure Docker's running, then run:

```sh
rake
```

This will build Docker containers for the app and API.

#### Server

To start the app and API servers, run:

```
rake server
```

This will start servers to run the app on port `9555` and the API on port `7000`.

### Ports

| Port | Service |
| --- | --- |
| [9555](http://localhost:9555) | Webpack dev server |
| [7000](http://localhost:7000) | GeoTrellis API |

### Rake commands

| Command | Description |
| --- | --- |
| `rake build` | Build project containers |
| `rake server` | Start servers |
| `rake tmux` | Setup project Tmuxinator configuration |
