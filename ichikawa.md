
flowchart LR
    %% Problema central
    A([Falla en la activación<br/>de los motores (0 RPM)<br/>en banco de pruebas])

    %% PERSONAS
    subgraph P[PERSONAS]
        P1[Desconocimiento de componentes]
        P2[Manipulación incorrecta del cableado]
        P3[Errores en conexión PCB]
        P4[Cambio de responsable]
    end

    %% MÉTODO
    subgraph M[MÉTODO]
        M1[Omisión de validación final del sistema]
        M2[Secuencia dependiente de tierra manual]
        M3[Protocolos de prueba no seguidos completamente]
    end

    %% COMUNICACIÓN
    subgraph C[COMUNICACIÓN]
        C1[Interferencias inalámbricas]
        C2[Respuesta parcial control-barco]
        C3[Señal intermitente a distancia]
    end

    %% TECNOLOGÍA
    subgraph T[TECNOLOGÍA]
        T1[Voltajes fuera de rango esperado]
        T2[Falla aparente INA219]
        T3[Posible fallo puente H]
        T4[Errores PCB / energía]
        T5[Integración ESP32-motores]
    end

    %% ENTORNO
    subgraph E[ENTORNO]
        E1[Entorno de prueba diferente al real]
        E2[Pruebas realizadas solo fuera del agua]
        E3[Ruido electromagnético del laboratorio]
    end

    %% GESTIÓN / CONTROL
    subgraph G[GESTIÓN / CONTROL]
        G1[Falta de validación final completa]
        G2[Cambio de encargado de pruebas]
        G3[Supervisión insuficiente]
    end

    %% Conexiones al problema central
    P --> A
    M --> A
    C --> A
    T --> A
    E --> A
    G --> A
