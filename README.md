# QuantumEngineering

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This repository contains Documentation on Quantum Engineering.

The ... is hosted through GitHub Pages.

## How to generate the repo locally

Clone the repository to your local machine:

```shell
git clone https://github.com/RichardVersluisTNO/QuantumEngineering.git
```

We recommend to create a virtual environment (_e.g._, [venv](https://docs.python.org/3/library/venv.html)),
run it, and install the requirements:

```shell
pip install -r requirements.txt
```

Once the required dependencies are installed,
the language specification can be served locally at <http://localhost:8000> by running:

```shell
mkdocs serve
```

The language specification can also be viewed via a provisioned Docker container.
No virtual environment is required in this case. Run the Docker container with the following command:

```shell
docker compose up -d
```

The language specification can now be viewed at <http://localhost:8106>.

## License

The quantum engineering repor is licensed under the Apache License, Version 2.0.

## Authors

Richard Versluis
