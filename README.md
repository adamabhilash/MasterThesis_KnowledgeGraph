# MasterThesis_KnowledgeGraph

This repository contains the code for the Master Thesis Knowledge Graph project.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Fuseki Server] (#fuseki_service)

## About

The Master Thesis Knowledge Graph to support IDN Authoring project aims to build a knowledge graph using Django framework. The knowledge graph will be used to represent and organize information related to the IDN authoring process.


## Features


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/MasterThesis_KnowledgeGraph.git
    ```

2. Change into the project directory:

    ```bash
    cd MasterThesis_KnowledgeGraph
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start the Django development server:

    ```bash
    python manage.py runserver
    ```

2. Open your web browser and navigate to `http://localhost:8000` to access the application.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch:

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. Make your changes and commit them:

    ```bash
    git commit -m "Add your commit message here"
    ```

4. Push your changes to your forked repository:

    ```bash
    git push origin feature/your-feature-name
    ```

5. Open a pull request on the original repository.

## Fuseki Service
The `fuseki_service` project is a component of the Master Thesis Knowledge Graph project. It is responsible for hosting and managing the Fuseki server, which is used to store and query the knowledge graph data.

### Installation
To install and configure the Fuseki service, follow these steps:

1. Download the Apache Jena Fuseki distribution from the official website.
2. Extract the downloaded archive to a desired location on your system.
3. Start the Fuseki server by running the following command:

    ```bash
    ./fuseki-server --update --mem /dataset
    ```

    This command starts the Fuseki server with an in-memory dataset named `/dataset`. You can modify the dataset name and storage type according to your requirements.

### Usage
Once the Fuseki server is running, you can interact with it using the Fuseki web interface or by making SPARQL queries programmatically.

To access the Fuseki web interface, open your web browser and navigate to `http://localhost:3030`. From there, you can manage datasets, upload RDF data, and execute SPARQL queries.

To make SPARQL queries programmatically, you can use the Apache Jena API or any other SPARQL client library of your choice. Here's an example of executing a SPARQL query using the Apache Jena API:


