### Description
* Ollama and OpenWebU's docker compose for WSL2 (GPU support).

### Prerequisites

* Windows 11(196GB) + NVidia video card (RTX3060 12GB)
* Windows 11(128GB) + NVidia video card (RTX5070ti 16GB)
* WSL2 (32GB and operation confirmed on Ubuntu 20.04 or 24.04)

*Not confirmed in other configurations than those listed above.

## Usage

* Initial start.
```
docker compose up -d
```
* After docker compose up -d, access the following.
```
http://localhost:8080
```
* docker compose stop to exit.

## Version

* 2025/04/29 Initial commits.

## Acknowledgments

