# 🔐 WEB3-DFS — Distributed File Storage System for IoT with Blockchain

**TFG - Diseño e implementación de un sistema de almacenamiento distribuido WEB 3.0**

Este proyecto es una prueba de concepto de un sistema de almacenamiento descentralizado pensado para entornos IoT. Se apoya en tecnologías blockchain, redes peer-to-peer y dispositivos de bajo consumo (como Orange Pi Zero), con el objetivo de garantizar la integridad, trazabilidad y disponibilidad de los datos sin depender de servidores centralizados.

---

## 🧱 Características principales

- 🌐 **Arquitectura distribuida P2P** entre nodos IoT (Orange Pi).
- 🔐 **Identificación por hash de contenido** (SHA-512).
- 📄 **Metadatos en formato JSON**, con permisos, propietario y timestamp.
- 🔁 **Redundancia basada en erasure coding o replicación** configurable.
- 📦 **Almacenamiento local con publicación IPFS** opcional.
- 🧾 **Registro de operaciones en blockchain** (Cardano en pruebas).
- 🔧 **API RESTful** para interacción entre nodos y gestión de archivos.
- 🌱 Código abierto, modular y extensible.

---

## 📦 Requisitos

- Python 3.10+
- Orange Pi Zero (o Raspberry Pi)
- Linux (Debian/Ubuntu recomendado)
- Docker (opcional para nodos virtualizados)
- [Cardano Node](https://docs.cardano.org) o simulador
- [IPFS](https://docs.ipfs.tech) (opcional)

---

## 🚀 Instalación

```bash
git clone https://github.com/usuario/web3-dfs.git
cd web3-dfs
pip install -r requirements.txt
```

---

## 🧪 Ejecución de la prueba de concepto

```bash
python3 node.py --config=config/node1.json
```

> Puedes lanzar múltiples nodos con configuraciones distintas simulando una red distribuida.

---

## 📁 Estructura del proyecto

```
web3-dfs/
│
├── node.py                # Nodo principal con API REST
├── storage/               # Módulo de almacenamiento local
├── blockchain/            # Lógica de integración con Cardano
├── metadata/              # Gestión y validación de metadatos JSON
├── network/               # Comunicación P2P entre nodos
├── config/                # Archivos de configuración por nodo
└── docs/                  # Documentación técnica y académica
```

---

## 🧠 Motivación académica

Este proyecto se desarrolla como parte del Trabajo de Fin de Grado en Ingeniería Informática, con el objetivo de aplicar principios de la Web 3.0 al diseño de un sistema de almacenamiento distribuido orientado a IoT, bajo un enfoque seguro, abierto y trazable.

---

## 📚 Referencias

- [IPFS Whitepaper](https://ipfs.io/ipfs/Qm.../whitepaper.pdf)
- [Filecoin Spec](https://spec.filecoin.io)
- [Cardano Research](https://iohk.io/en/research/)
- [Erasure Coding IEEE Paper](https://doi.org/10.1109/TIT.2010.2054295)

---

## 📄 Licencia

Este proyecto está bajo licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

---

## ✉ Contacto

Desarrollado por **José Ignacio**  
📧 Contacto: [tu-email@ejemplo.com]
