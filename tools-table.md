## Tools used by prototype v0.1

### Cloud computing (OpenStack v6.2.0)

| **Technology**                    | **Function in the prototype**                                        |
| Zun (v11.1.0.dev5)            | Manage Docker containers                                         |
| Nova (v18.3.0)                | Manages computing resources                                      |
| Heat (v20.1.0.dev42)          | Orchestra services                                               |
| Octavia (v12.1.0.dev44)       | Load Balancer                                                    |
| Neutron (v23.0.0.0b3.dev50)   | Network Manager                                                  |
| Mosquitto server              | MQTT Broker                                                      |
| Glance (v.4.3.0)              | Image Manager                                                    |
| Keystone (v.23.1.0)           | Access Manager                                                   |
| Horizon (23.2.0)              | Dashboard for OpenStack management                               |
| Ceilometer (v20.1.0.dev19)    | Log and metrics manager                                          |
| MongoDB                       | Database                                                         |
| Apache Superset               | Dashboard for resource data                                      |
| Webhook                       | Event notification                                               |
| REST                          | Communication                                                    |
| Microsserviços                | Isolation of AI algorithms                                       |


### Fog computing

| **Technology**                    | **Function in the prototype**                                        |
| Mosquitto server (v2.0.15)    | MQTT Broker                                                      |
| Fuseki (SPARQL 1.1)           | SPARQL Server                                                    |
| Elasticsearch (v8.1.2)        | Log analysis and metrics                                         |
| Kibana (v8.1.2)               | Views and queries on log data                                    |
| MongoDB (v6.0.6)              | Database                                                         |
| Mongo Express (1.0.0-alpha.4) | MongoDB data visualization                                       |
| Esper CEP (v7.1.0)            | Pattern tracking engine in data stream                           |
| IoT-Stream (v1.0)             | Base ontology for semantic annotation                            |
| FluentD (v1.12.0-debian-1.0)  | Container log capture                                            |
| Data processing (v0.1)        | Own implementation (data processing)                             |
| Semantic (v0.1)               | Own implementation (semantic annotation)                         |
| Data flow tracking (v0.1)     | Own implementation (uses Esper CEP to track patterns)            |
| Paho MQTT (v1.2.1)            | MQTT client used in containers                                   |
| SnakeYAML (v2.0)              | YAML parser present in containers                                |
| GSON (v2.10.1)                | JSON parser present in containers                                |


### Edge computing

| **Technology**                | **Function in the prototype**                                    |
| Nlohmann (v3.11.2)            | JSON parser                                                      |
