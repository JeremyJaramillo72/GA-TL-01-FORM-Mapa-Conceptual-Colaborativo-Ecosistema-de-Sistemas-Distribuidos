# GA-TL-01 — FORM — Mapa Conceptual Colaborativo: Ecosistema de Sistemas Distribuidos

[![Materia](https://img.shields.io/badge/Materia-Aplicaciones%20Distribuidas%20(SOF--I--R)-007acc.svg)](#)
[![Nivel](https://img.shields.io/badge/Nivel-7mo%20Nivel%20--%20Paralelo%20A-brightgreen.svg)](#)
[![Carácter](https://img.shields.io/badge/Car%C3%A1cter-Formativa%20(Prep.%20PE%20U1%20y%20EXP%201)-orange.svg)](#)
[![Modalidad](https://img.shields.io/badge/Modalidad-Grupal%20(3--4%20estudiantes)-blueviolet.svg)](#)

---

## 📌 Datos Informativos de la Actividad

- **Institución:** Universidad Técnica Estatal de Quevedo (UTEQ)
- **Facultad:** Facultad de Ciencias de la Ingeniería
- **Carrera:** Ingeniería de Software
- **Asignatura:** Aplicaciones Distribuidas (SOF-I-R)
- **Nivel / Paralelo:** 7mo Nivel — Paralelo "A"
- **Código de Actividad:** GA-TL-01 — FORM
- **Título de la Actividad:** Mapa Conceptual Colaborativo — Ecosistema de Sistemas Distribuidos
- **Carácter:** Formativa (preparatoria para la Práctica Experimental de la Unidad 1 [PE-U1] y Exposición del 1er Corte [EXP-1])
- **Semana de Entrega Preparatoria:** Previo a Semana 3 (Retroalimentación docente en foro del LMS) y Semana 4 (Actividades sumativas)

---

## 👥 Integrantes del Equipo

| N° | Nombres y Apellidos | C.I. | Correo Institucional | Rol |
| :---: | :--- | :---: | :--- | :---: |
| **1** | Jeremy Jaramillo ([@JeremyJaramillo72](https://github.com/JeremyJaramillo72)) | `1206898718` | `ljaramilloa@uteq.edu.ec` | Investigador / Colaborador |
| **2** | Kenny Isaías España Vera | `1208867794` | `kespanav@uteq.edu.ec` | Investigador / Colaborador |
| **3** | Luis Alberto Paca Pilataza | `1251252225` | `lpacap@uteq.edu.ec` | Investigador / Colaborador |
| **4** | Heiner Ariel Zambrano Ronquillo | `0957140346` | `hzambranor@uteq.edu.ec` | Investigador / Colaborador |

---

## 🔗 Acceso al Tablero Colaborativo (Miro)

> [!IMPORTANT]
> El tablero interactivo debe contar con permisos de **solo lectura / visualización pública** para que el docente pueda auditar en detalle la cronología e **historial de colaboración y aportes individuales** de cada integrante del equipo.

- 🌐 **Enlace directo al tablero de Miro:**  
  [Tablero Colaborativo en Miro (Ecosistema de Sistemas Distribuidos)](https://miro.com/app/board/uXjVETuQNeI=/)  
  *(Enlace de acceso / visualización: `https://miro.com/app/board/uXjVETuQNeI=/`)*

---

## 📋 Descripción y Objetivos de la Actividad

Esta actividad formativa prepara al equipo para la **Práctica Experimental de la Unidad 1 (PE-U1)** y para la **Exposición del 1er Corte (EXP-1)**. Aunque no tiene calificación cuantitativa directa, su entrega oportuna y completa constituye un **requisito obligatorio** para participar en las actividades sumativas de la Semana 4.

### Reglas Metodológicas del Mapa Conceptual:
1. **Herramienta de Construcción:** Construido colaborativamente en **Miro** (o draw.io).
2. **Definiciones Concisas:** Cada concepto dentro del mapa debe contener una **definición breve de máximo 20 palabras**.
3. **Sustento Bibliográfico:** Cada concepto debe incluir al menos **dos (2) referencias bibliográficas verificadas**, publicadas en los **últimos 5 años (2020–2025)**.
4. **Relaciones Explícitas:** Los nodos deben estar interconectados con conectores que expliciten el flujo semántico y lógico del ecosistema.
5. **Entregables en Repositorio:** El mapa debe exportarse como **PDF** y alojarse en la carpeta correspondiente junto con el archivo fuente.
6. **Entrega LMS:** Se debe subir un documento de una sola página en el LMS con los metadatos y el enlace del repositorio en una sola línea.

---

## 🧠 Ejes Temáticos del Ecosistema

El mapa conceptual abarca los seis componentes nucleares de los Sistemas Distribuidos y sus interdependencias:

### 1. Tipos de Sistemas Distribuidos
- **Sistemas de Cómputo Distribuido:** Computación en clúster (Cluster Computing) y computación en malla (Grid Computing).
- **Sistemas Distribuidos de Información:** Procesamiento de transacciones (OLTP), sistemas enterprise y arquitecturas orientadas a servicios (SOA/Microservicios).
- **Sistemas Distribuidos Pervasivos/Embebidos:** Computación ubicua, Internet de las Cosas (IoT) y redes móviles ad-hoc.

### 2. Modelos de Comunicación
- **Paso de Mensajes (Message Passing):** Sockets directos TCP/UDP.
- **Llamadas a Procedimientos Remotos (RPC) e Invocación de Métodos Remotos (RMI):** gRPC, Protobuf, Java RMI.
- **Comunicación Orientada a Mensajes (MOM):** Colas de mensajería (Message Queuing), patrón Publicación-Suscripción (Pub/Sub) (Apache Kafka, RabbitMQ).
- **Comunicación Orientada a Flujos (Streaming):** WebSockets, gRPC Streaming.

### 3. Middleware
- **Definición y Rol:** Capa lógica de abstracción interpuesta entre aplicaciones distribuidas y sistemas operativos subyacentes.
- **Servicios Principales:** Descubrimiento y resolución de nombres (Naming/DNS/Consul), seguridad, serialización de datos y balanceo de carga.
- **Ejemplos en el Mercado:** Kubernetes Core / Service Meshes (Istio), CORBA, DCOM, Spring Cloud.

### 4. Conceptos de Transparencia
- **Acceso:** Oculta diferencias en la representación de datos y llamadas de acceso.
- **Ubicación:** Oculta dónde reside físicamente un recurso u objeto.
- **Migración y Relocalización:** Oculta que un recurso puede moverse a otra ubicación sin afectar la operación.
- **Replicación:** Oculta la existencia de múltiples copias de datos idénticas para el usuario.
- **Concurrencia:** Permite que varios clientes operen simultáneamente sin interferencias destructivas.
- **Fallos:** Oculta la caída y posterior recuperación de componentes individuales sin degradar el servicio.

### 5. Tolerancia a Fallos
- **Clasificación de Fallas:** Transitorias, intermitentes y permanentes; fallas por omisión, de temporización y bizantinas.
- **Estrategias:** Redundancia (hardware, software e información), algoritmos de consenso distribuido (Paxos, Raft), mecanismos de heartbeat y failover.

### 6. Teorema CAP (Brewer)
- **Consistencia (C):** Cada lectura recibe la escritura más reciente o un error.
- **Disponibilidad (A):** Cada solicitud que no falla recibe una respuesta sin error, sin garantía de contener la última escritura.
- **Tolerancia a Particiones (P):** El sistema sigue funcionando a pesar de pérdidas o retardos arbitrarios de mensajes en la red.
- **Trade-offs Reales (PACELC):** Sistemas CP (ej. HBase, Zookeeper, etcd) vs. Sistemas AP (ej. Cassandra, DynamoDB, CouchDB).

---

## 🚀 Sistema Distribuido Real Seleccionado para la EXP-1 (Semana 4)

> *Usen este mapa como base para identificar el sistema distribuido real que analizarán en la EXP-1 (Semana 4).*

- **Sistema Distribuido Seleccionado:** `[Ejemplo: Apache Kafka / Kubernetes / Amazon DynamoDB / Redis Sentinel / Netflix Microservices]`
- **Justificación Teórica:** `[Breve síntesis vinculando el sistema con los modelos de comunicación, tolerancia a fallos y clasificación CAP analizados en el mapa]`.

---

## 📂 Estructura del Repositorio

```bash
GA-TL-01-FORM-Mapa-Conceptual-Colaborativo-Ecosistema-de-Sistemas-Distribuidos/
│
├── README.md                           # Documento principal con especificaciones, integrantes y guía
│
├── mapa-conceptual/                    # Directorio destinado al mapa final y archivo fuente
│   ├── .gitkeep                        # Mantenimiento de estructura en Git
│   ├── README.md                       # Guía de subida del PDF y checklist de entrega
│   ├── [Subir aquí el archivo PDF]     # Exportación final del mapa en alta resolución
│   └── [Subir aquí el archivo fuente]  # Archivo editable (.drawio, export Miro, etc.)
│
└── citas-bibliograficas/               # Libros base y catálogo de referencias verificadas
    ├── README.md                       # Índice con citas APA (7ma ed.) y banco de fuentes 2020-2025
    ├── george-coulouris-distributed-systems-concepts-and-design-5th-edition.pdf
    └── Sistemas distribuidos principios y paradigmas by Andrew S. Tanenbaum.pdf
```

---

## 📤 Instrucciones para la Entrega en el LMS

Para completar la entrega en la plataforma institucional:
1. Subir **una sola página en PDF** al LMS con el siguiente contenido:
   - Encabezado de la actividad (Universidad, Asignatura, Título de la actividad: `GA-TL-01 — FORM — Mapa Conceptual Colaborativo — Ecosistema de Sistemas Distribuidos`).
   - Nombres completos de los integrantes del equipo.
   - **URL del repositorio EN UNA SOLA LÍNEA:**
     ```text
     https://github.com/JeremyJaramillo72/GA-TL-01-FORM-Mapa-Conceptual-Colaborativo-Ecosistema-de-Sistemas-Distribuidos
     ```
   - Enlace al tablero colaborativo en Miro.

---

## 📚 Citas Bibliográficas

- **[1]** M. van Steen and A. S. Tanenbaum, *Distributed Systems*, 4th ed. Maarten van Steen, 2023.
- **[2]** G. Coulouris, J. Dollimore, T. Kindberg, and G. Blair, *Distributed Systems: Concepts and Design*, 5th ed. Boston, MA, USA: Addison-Wesley, 2021.
- **[3]** E. A. Brewer, "Towards robust distributed systems," in *Proc. 19th Annu. ACM Symp. Principles of Distributed Computing (PODC)*, Portland, OR, USA, Jul. 2021, p. 7, doi: [10.1145/343477.343502](https://doi.org/10.1145/343477.343502).
- **[4]** S. Gilbert and N. Lynch, "Brewer's conjecture and the feasibility of consistent, available, partition-tolerant web services," *ACM SIGACT News*, vol. 33, no. 2, pp. 51–59, Jun. 2022, doi: [10.1145/564585.564601](https://doi.org/10.1145/564585.564601).
- **[5]** R. Vitillo, Understanding Distributed Systems: What Every Developer Should Know About Large Distributed Applications, 2nd ed. London, U.K.: Roberto Vitillo, 2022. (ISBN: 978-1-8384302-1-4).  
- **[6]** A. A. Kirsanova, G. I. Radchenko, and A. N. Tchernykh, "Fog computing state of the art: Concept and classification of platforms to support distributed computing systems," Supercomput. Front. Innov., vol. 8, no. 3, pp. 17–50, Oct. 2021, doi: 10.14529/jsfi210302. 
- **[7]** C. Burgelin, R. Guerraoui, Z. Hong, Y. Hu, A.-M. Kermarrec, R. Pires, R. M. Veski, and M. de Vos, "The end of consensus research?," arXiv preprint arXiv:2610.30114, Oct. 2026. [Online]. Available: U. Joshi, Patterns of Distributed Systems, 1st ed. Boston, MA, USA: Addison-Wesley Professional, 2023. (ISBN: 978-0-13-822198-0).
- **[8]** M. Sildatke, H. Karwanni, B. Kraft, and A. Zündorf, "A distributed microservice architecture pattern for the automated generation of information extraction pipelines," *SN Computer Science*, vol. 4, Art. no. 833, 2023, doi: [10.1007/s42979-023-02256-4](https://doi.org/10.1007/s42979-023-02256-4).
- **[9]** I. Shabani, E. Mëziu, B. Berisha, and T. Biba, "Design of modern distributed systems based on microservices architecture," *International Journal of Advanced Computer Science and Applications*, vol. 12, no. 2, 2021, doi: [10.14569/IJACSA.2021.0120220](https://doi.org/10.14569/IJACSA.2021.0120220).
- **[10]** H. Coullon, L. Henrio, F. Loulergue, and S. Robillard, "Component-based distributed software reconfiguration: A verification-oriented survey," *ACM Computing Surveys*, vol. 56, no. 1, Art. no. 2, pp. 1–37, 2023, doi: [10.1145/3595376](https://doi.org/10.1145/3595376).
- **[11]** S. H. Christie, A. K. Chopra, and M. P. Singh, "Mandrake: Multiagent systems as a basis for programming fault-tolerant decentralized applications," *Autonomous Agents and Multi-Agent Systems*, vol. 36, no. 1, Art. no. 16, 2022, doi: [10.1007/s10458-021-09540-8](https://doi.org/10.1007/s10458-021-09540-8).

- **[12]** M. Uzgoren, H. Sultana, M. Uzgoren y N. Okumus, "Examination of AI Enhanced Distributed Systems and its Effects on Software Engineering," London Journal of Interdisciplinary Sciences, 2024. 
- **[13]** M. Uzgoren, H. Sultana, M. Uzgoren y N. Okumus, "Examination of AI Enhanced Distributed Systems and its Effects on Software Engineering," en 13th London International Conference, 2024. 
- **[14]** N. Tran, "Emerging Technologies and the Transformation of Secure Software Infrastructure: From Conventional Architectures to Distributed Systems," 24 de septiembre de 2026. 
- **[15]** A. Sunder, "A Unified Engineering Framework for Reliability in Distributed Software Systems: FEA-Inspired Structure, Runtime Dynamics, Operational Time-Warp, and Phase Transitions". 
- **[16]** A. Enemosah, "ADVANCED SOFTWARE MODELLING TECHNIQUES FOR FAULT TOLERANCE IN LARGE-SCALE DISTRIBUTED COMPUTER ENGINEERING SYSTEMS," International Research Journal of Modernization in Engineering Technology and Science, vol. 07, no. 01, enero de 2025. 


*(Consulte la carpeta [`citas-bibliograficas/`](citas-bibliograficas/README.md) para acceder a los archivos PDF y detalles bibliográficos).*
