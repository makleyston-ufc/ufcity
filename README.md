# UFCity

---

The UFCity project offers a software ecosystem to efficiently interconnect the city's resources.

The UFCity platform comprises a computer network architecture comprising three layers: edge, fog, and cloud computing. Each of these layers has software elements dedicated to data processing, storage, and analysis.

Some features of this platform are:
* Processing at each layer (de-overloading network nodes).
* Distributed storage.
* Data analysis according to semantics and context.
* Scalability and elasticity of services.
* Open source.
* Management of city resources: monitoring and activation.
* Support for Artificial Intelligence (AI), including machine learning (ML) analysis and intelligent decision-making.
* Data flow analysis.
* Instant actions based on patterns in data flow.
* Expansion and adaptation of AI-based on-demand functionalities.
* Combination of data flow to compose new services.
* Complex event processing.
* Data stratification for precise management.
* Sharing city data and resources between subdomains (multi-domains).
* Easy integration with other tools and systems.
* Many other features.

---

## UFCity platform components


All components must be implemented in the city. Edge computing components deal with data closest to users, having knowledge restricted to the local context and offering services that help process and respond to the user.

Fog computing has a slightly broader knowledge than edge computing nodes. In this case, more complex services are available, such as semantic data annotation, complex event processing, and data flow combination.
Cloud computing has holistic knowledge of the city, allowing it to offer strategic and intelligent services. The insertion and adaptation of services in cloud computing are facilitated by the enabling technologies adopted and by the design strategy based on expansion via AI.

To learn more about these layers and initialize them in your project, see them in their respective repositories below.


---

### Edge computing

The [Edge Module](https://makleyston-ufc.github.io/ufcity-edge-module/) is a lightweight component developed in C++ and efficient for processing, grouping, filtering, and summarizing data, in addition to introducing contextual elements of space. Because it is developed in C++, it can be run on different devices, such as smartphones and Raspberry Pi.

![Static Badge](https://img.shields.io/badge/Edge_module-gray?style=flat&logo=cplusplus&logoColor=white&link=https%3A%2F%2Fgithub.com%2Fmakleyston-ufc%2Fufcity-edge-module)


---

### Fog computing

Fog computing was designed from the perspective of containerized services. Therefore, we adopted Docker to manage these containers.
In this layer, there are several software components, including those developed within this project: [UFCity-Handler](https://makleyston-ufc.github.io/ufcity-fog-handler/), [UFCity-CEP](https://makleyston-ufc.github.io/ufcity-fog-cep/) and [UFCity-Semantic](https://makleyston-ufc.github.io/ufcity-fog-semantic/).

Other components are introduced from their official vendors, such as [Mosquitto](https://hub.docker.com/_/eclipse-mosquitto), [FluentD](https://hub.docker.com/_/fluentd ), [MongoDB](https://hub.docker.com/_/mongo), [Elasticsearch](https://hub.docker.com/_/elasticsearch) and [Kibana](https://hub. docker.com/_/kibana).
To deploy all components easily, use the following [`docker compose`](https://makleyston-ufc.github.io/ufcity-fog-docker/).


![Static Badge](https://img.shields.io/badge/Bash%20installer-gray?style=flat&logo=powershell&logoColor=white&link=https%3A%2F%2Fgithub.com%2Fmakleyston-ufc%2Fufcity-fog-docker)


---

### Cloud computing

Cloud computing has extensive knowledge of the city, making it possible to manage resource services across the entire city.
This layer was developed using the [OpenStack]() infrastructure for clouds.

AI-based intelligent processing and decision-making elements play an important role at this layer. To this end, UFCity adopts the [Zun]() tool for managing microservices containers equipped with AI resources. Other tools manage load distribution and elasticity, allowing processing and storage suitable for any city model.

A cloud boot file via OpenStack can be found [HERE]().


---

## Publications

Waiting for publication data

---

## Cite us

Waiting for publication data

---

