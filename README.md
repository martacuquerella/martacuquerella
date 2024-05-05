flowchart TD
    A[("Cliente: Define necesidades y especificaciones")]
    B[("Proveedor de Tecnología/Instalador: Implementa hardware y software")]
    C[("Operario/Técnico: Calibra cámaras y ajusta software")]
    D[("Visión por Computadora: Monitorea y detecta actividades sospechosas")]
    E[("Visión por Computadora: Envía alertas automáticas")]
    F[("Operario: Verifica alertas y confirma sospechas")]
    G[("Acción Automática de Peligro: Activa medidas de seguridad y alerta a equipos")]
    H[("Operario: Toma acciones según protocolo")]
    I[("Cliente: Informado sobre incidentes y acciones")]
    J[("Visión por Computadora: Guarda registros de incidentes")]
    K[("Cliente: Accede a registros")]
    L[("Cliente y Operario: Evalúan y ajustan sistema")]
    M[("Proveedor de Tecnología: Actualiza software y mantiene hardware")]
    
    A --> B --> C --> D --> E --> F --> G
    G --> H --> I
    E --> J --> K
    L --> M

    classDef inicioend fill:#f9f,stroke:#333,stroke-width:2px;
    class A inicioend;
    class I inicioend;
