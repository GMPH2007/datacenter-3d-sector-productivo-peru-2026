# GUÍA MAESTRA DE SUSTENTACIÓN FINAL - GRUPO 01
## PROYECTO: «DISEÑO INTERACTIVO 3D PARA LA GESTIÓN EFICIENTE EN ESPACIOS DE SERVIDORES PARA EMPRESAS DEL SECTOR PRODUCTIVO, PERÚ 2026»

**Programa de Estudios:** Arquitectura de Plataformas y Servicios de Tecnologías de la Información (APSTI VI - 2026)  
**Unidad Didáctica:** Tutoría APSTI VI / Proyecto Final Integrador  
**Docente Asesor:** Prof. Javier Eduardo Jaramillo Atoche  
**Entorno de Ejecución:** WebGL / Three.js 60 FPS nativo (Archivo interactivo: [`index.html`](file:///c:/Users/Misael%20P/Downloads/Trabajo%20jRAMAILLO/index.html))

---

## 👥 DISTRIBUCIÓN DE ROLES Y DEFENSA ANTE EL JURADO

### 1. Gerson Misael Pintado (Tú) — *Líder de Proyecto & Operador del Gemelo Digital 3D*
- **Qué expones:** 
  - Apertura formal del proyecto: Presentación del equipo y del objetivo del Gemelo Digital 3D en el sector productivo del Perú.
  - Demostración en vivo en pantalla completa del software interactivo ([`index.html`](file:///c:/Users/Misael%20P/Downloads/Trabajo%20jRAMAILLO/index.html)).
  - **Sistema Interactivo CCTV PTZ 4K (POV Primera Persona)**:
    - Haz clic directo en cualquiera de las 4 cámaras de seguridad en la sala 3D o en el botón **`📹 Cámaras CCTV PTZ (Vista 4K POV)`** del panel lateral.
    - Muestra al jurado cómo la vista del usuario se ancla en el lente de la cámara robótica y oscila en tiempo real siguiendo el motor PTZ.
    - Destaca el **HUD de Vigilancia Industrial**: grabación activa `🔴 REC ● [4K UHD 60FPS]`, reloj sincronizado, retícula óptica central, telemetría de paneo (`PAN: +15.2°`, `TILT: -31.5°`) y conmutación rápida `[CAM-01]`, `[CAM-02]`, `[CAM-03]`, `[CAM-04]` y `[✖ SALIR DE CCTV]`.
  - **Radar Táctico DCIM v2.4 (Planta 2D en Vivo)**:
    - Señala la esquina inferior izquierda: Explica que es un plano de control arquitectónico bidimensional en tiempo real con 31m de longitud.
    - Muestra el **haz de barrido sonar giratorio** y los anillos concéntricos de 5m, 10m y 15m.
    - Muestra la delimitación clara entre la **Sala de Servidores** y la **Sala NOC Externa con sus 3 puestos de PCs**.
    - Pasa el mouse por encima de cualquier rack para mostrar el **Tooltip flotante de telemetría instantánea** (temperatura, potencia en kW, ocupación de RU y porcentaje de carga).
    - Presiona el botón **`🌡️ Temp`** del radar para cambiar al mapa térmico de calor 2D.
  - **Tour Cinemático de 12 Zonas Holgado y Suave**:
    - La cámara se desplaza a una distancia cómoda y amplia (3.0m a 5.5m), evitando acercamientos excesivos o invasivos.

---

### 2. Oscar Eliseo Pizarro — *Especialista en Hardware, Racks y Blade Servers*
- **Qué expones:**
  - **Extracción Doble en Cascada Escalonada (Servidor Inferior + Servidor Superior)**:
    - Al presionar **`🔧 Extraer 3D`**, se extraen **DOS servidores 2U simultáneamente en rieles telescópicos de acero**:
      1. **Servidor 1 (Inferior - U20)**: Servidor de base de datos transaccional Oracle Exadata con 16x bahías Hot-Swap U.2 NVMe Gen5 All-Flash (120TB RAID-10), placa base verde esmeralda, disipadores con cámara de vapor y 6x ventiladores PWM Dual-Rotor girando a 18,000 RPM.
      2. **Servidor 2 (Superior - U26)**: Servidor de procesamiento para Inteligencia Artificial y SAP HANA (Dual CPU AMD EPYC / Intel Xeon con 128 núcleos), que avanza a una posición escalonada (0.78m) para **no tapar al servidor inferior**, permitiendo ver el hardware interno de ambos gabinetes a la vez.
    - **Encuadre Isométrico 3/4 Holgado a 3.2m**: Explica que la cámara se posiciona con suficiente margen para que el radar táctico de la esquina inferior y el panel lateral no obstruyan las etiquetas de los componentes.
    - Botón **`👁️ Ocultar / Mostrar Badges`** para retirar las etiquetas y admirar el hardware limpio.
  - **Cableado Estructurado en Racks**:
    - Cepillos pasamuros superiores, cascadas curvas de cableado (waterfall drops) desde las escalerillas amarillas a 3.6m hacia los gabinetes, latiguillos Cat6A/fibra y barras verticales PDU A/B con LEDs de telemetría.

---

### 3. Pedro Miguel Aguilar — *Especialista en Infraestructura, Climatización y Seguridad Física*
- **Qué expones:**
  - **Segregación Física: Sala NOC Externa de Operaciones (PCs Fuera de Servidores)**:
    - Enfatiza la norma TIA-942: Los operadores humanos y sus computadoras **no deben convivir en el ambiente hostil de los servidores** (85 dB de ruido y 19°C de frío constante).
    - Por ello, la **Sala NOC se sitúa totalmente afuera** (de Z = -9.5m a Z = -18.0m, con 8.5 metros de profundidad), separada por un muro acústico con ventanal panorámico estanco y puerta con control biométrico.
    - **Puestos de Trabajo de Operadores con Computadoras**: 3 estaciones de trabajo ergonómicas completas con monitores curvos duales de 32", computadoras torre con ventiladores iluminados RGB, teclados, ratones y sillas de malla.
    - **Videowall Panorámico 8K a Z = -17.85m**: Pantalla gigante de 9.4m de ancho con telemetría unificada.
    - **Conectividad Estructurada Pasante**: Pasamuros estancos Roxtec a 3.6m por donde cruzan las bandejas amarillas de cable azul Cat6A y fibra naranja desde los servidores hacia el rack de telecomunicaciones de la Sala NOC.
  - **Sala de Fuerza Segregada (UPS y Generador Caterpillar 500kVA)**:
    - Separada a X = 7.6m con bolardos industriales de impacto a X = 5.8m y franjas perimetrales de advertencia OSHA.
  - **Climatización y Protección Contra Incendios**:
    - Confinamiento de pasillo frío a 19.8°C y red de extinción de gas limpio FM-200 a 4.6m con boquillas difusoras de bronce (NFPA 2001).

---

### 4. Mariana Juliet Clavijo — *Gestora de Documentación, Realidad Problemática y Normativa*
- **Qué expones:**
  - **La Realidad Problemática en el Perú**: Empresas agroindustriales, pesqueras y manufactureras pierden más de $5,600 USD por cada minuto de inactividad de sus servidores centrales.
  - **Fallas Históricas Resueltas**: Fin a las hojas de Excel desactualizadas y al riesgo de incendio no controlado.
  - **Marco Normativo Internacional Aplicado**:
    - **ANSI/TIA-942 Tier III**: Redundancia 2N en potencia y climatización con mantenimiento concurrente.
    - **NFPA 2001**: Estándar para sistemas de extinción de incendios mediante agentes limpios (gas FM-200 sin agua).
    - **ASHRAE TC 9.9**: Guía térmica de temperatura recomendada (18°C a 27°C).

---

### 5. Manuel Danilo López Garay — *Diseñador de Diapositivas, Beneficios Empresariales & ROI*
- **Qué expones:**
  - Coordinación de las diapositivas de soporte proyectadas junto al Gemelo Digital 3D.
  - **Retorno de Inversión y Beneficios Cuantificables**:
    - **-65% en Tiempo Medio de Reparación (MTTR)**: De 45 min a 15 min al visualizar exactamente qué rack y qué servidor está fallando en el modelo 3D, en el Radar Táctico y en las cámaras CCTV.
    - **$42,500 USD de Ahorro Eléctrico Anual**: Optimización del PUE a 1.22 gracias al confinamiento de pasillo frío.
    - **Amortización en 3.8 Meses**: Al prevenir paradas críticas de producción no planificadas.

---

## 🎬 GUION DE DEMOSTRACIÓN RÁPIDA (PASO A PASO EN VIVO)

1. **Apertura:** Iniciar con [`INICIAR_PROYECTO_3D.bat`](file:///c:/Users/Misael%20P/Downloads/Trabajo%20jRAMAILLO/INICIAR_PROYECTO_3D.bat) y presionar pantalla completa (**F11**).
2. **Paso 1 (Extracción Doble de Servidores):** Clic en **RACK-01** y luego en **`🔧 Extraer 3D`**. Mostrar al jurado cómo se abren simultáneamente el **Servidor 1 (Inferior U20)** y el **Servidor 2 (Superior U26)** en cascada escalonada en rieles telescópicos sin taparse.
3. **Paso 2 (Sala NOC Externa con PCs):** Clic en **`🖥️ Sala Monitoreo NOC`** en la botonera lateral o en el radar. Mostrar los 3 puestos de PCs de los operadores con sus monitores, torres RGB, teclados, sillas y el cableado pasamuros que viene desde los servidores.
4. **Paso 3 (Vista CCTV POV 4K):** Hacer clic en cualquier cámara de seguridad en el techo o en **`📹 Cámaras CCTV PTZ (Vista 4K POV)`**. Mostrar el movimiento robótico en primera persona y alternar entre `[CAM-01]`, `[CAM-02]`, `[CAM-03]` y `[CAM-04]`.
5. **Paso 4 (Tour Automático Suave):** Clic en **`🎬 Tour Curvas Bezier`**. Destacar que la cámara mantiene siempre una distancia amplia y cómoda (3.0m a 5.5m) sin acercamientos invasivos ni bloqueos.
6. **Paso 5 (Simulador de Incendio y FM-200):** Clic en **`🔥 Incendio en Servidor`**. Observar la propagación térmica hacia RACK-02 y las alertas en el radar y cámaras. Presionar **`🧯 ACTIVAR GAS FM-200`** para extinguirlo con gas limpio.
7. **Paso 6 (Corte de Luz y Respaldo):** Clic en **`⚡ Corte de Luz`**. Las cámaras y el radar pasan a modo rojo de visión nocturna y el generador Caterpillar arranca. Clic en **`✅ Normalizar Sala`** para finalizar con éxito la defensa.
