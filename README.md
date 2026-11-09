<p align="center">
  <h1 align="center">👑 CYWUU PRIVATE CLIENT 👑</h1>
  <p align="center">
    <strong>Ghost Client de C++ Avanzado para Minecraft 1.8.9 (Lunar Client / Forge / Vanilla)</strong>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/Language-C%2B%2B17-7c3aed?style=for-the-badge&logo=c%2B%2B" alt="C++17">
    <img src="https://img.shields.io/badge/Platform-Windows%20x64-6d28d9?style=for-the-badge&logo=windows" alt="Windows x64">
    <img src="https://img.shields.io/badge/Target-Lunar%20%2F%201.8.9-8b5cf6?style=for-the-badge&logo=minecraft" alt="1.8.9">
    <img src="https://img.shields.io/badge/Theme-Royal%20Violet-a855f7?style=for-the-badge" alt="Royal Violet">
    <img src="https://img.shields.io/badge/Status-Undetected-10b981?style=for-the-badge" alt="Undetected">
  </p>
</p>

---

## 🌟 Resumen del Cliente

**Cywuu Private Client** es una solución interna en DLL de alto rendimiento desarrollada en C++ nativo. Incorpora algoritmos de humanización matemática avanzada, una interfaz moderna y sofisticada con estética **Frosted Glass & Royal Violet**, y ganchos de nivel de sistema para una experiencia indetectable, fluida y sin interrupciones.

---

## 🎨 Interfaz de Usuario (UI & UX)

- **Estética Obsidian & Royal Violet**: Tonos oscuros profundos acentuados con violeta neón (`#A855F7` y `#7C3AED`) y tipografía Inter limpia.
- **Header Premium**: Tipografía minimalista con insignia de cliente privado.
- **Contador de Módulos Activos**: Muestra en vivo cuántos módulos tienes activados en cada categoría (ej. `3 / 5`).
- **Cursor Guard 2.0**: Bloqueo preventivo de captura de cursor que evita que el ratón se quede centrado en el medio de la pantalla al entrar o salir de menús e inventarios.
- **Tecla de Menú**: Abrir / Ocultar el menú con la tecla **Flecha Arriba** (`↑`).

---

## ⚡ Módulos y Funciones

### ⚔️ Combat

| Módulo | Descripción |
| :--- | :--- |
| **Aim Assist (Humanized)** | Asistencia de puntería avanzada con curva de desaceleración *Hermite smoothstep*, vector dinámico de altura (pecho a ojos `1.20m` - `1.45m`), zona muerta configurable (*deadzone*) y micro-temblores gaussianos para emular el pulso natural de la mano. |
| **AutoClicker (Humanized)** | Generación de clics con distribución normal (Box-Muller) para evitar intervalos rígidos o patrones mecánicos. Incluye micro-fatiga, fluctuación orgánica del ritmo (*pace drift*) y **Right-Click AutoClicker** independiente para *fast bridging*. |
| **Reach** | Expansión milimétrica y personalizable del rango de impacto con porcentaje de acierto estocástico (*rare chance*). |
| **Velocity** | Control porcentual de reducción de knockback horizontal y vertical para mantenerse firme en combate sin activar alertas. |
| **Triggerbot** | Disparo automático en el momento exacto en que la mira hace contacto con la hitbox del oponente. |
| **W-Tap** | Reseteo automático de sprint con temporización matemática tras conectar un impacto para infligir el máximo empuje al rival. |
| **Criticals** | Sincronización de micro-paquetes de posición para infligir golpes críticos constantes en el suelo. |

---

### 🏃 Movement

| Módulo | Descripción |
| :--- | :--- |
| **Sprint** | Sprint continuo y omnidireccional inteligente sin pérdida de inercia al golpear. |
| **Strafe** | Control dinámico del movimiento en el aire con aceleración personalizable. |
| **SafeWalk / Eagle** | Detiene el avance en los bordes de los bloques para construir puentes a toda velocidad sin riesgo de caída. |
| **NoSlowdown** | Suprime la penalización de lentitud al tensar el arco, comer, tomar pociones o cubrirse con la espada. |
| **InvWalk** | Permite desplazarse, saltar y esprintar libremente mientras se gestiona el inventario o la interfaz de cofres. |
| **NoFall** | Anula el daño por caída mediante manipulación de la bandera en tierra en momentos precisos. |
| **Step** | Permite subir alturas de bloques de forma suave y sin necesidad de salto continuo. |

---

### 👁️ Render & Visuals

| Módulo | Descripción |
| :--- | :--- |
| **Target HUD** | *¡Nuevo!* Elegante tarjeta flotante estilo *frosted glass* con avatar del objetivo, barra de salud interpolada con gradiente violeta a fucsia (`#A855F7` ➔ `#EC4899`), distancia en metros y medidor táctico `WINNING` / `LOSING`. |
| **ModOverlay & Watermark** | Píldora superior translúcida con la marca **CYWUU PRIVATE CLIENT**, monitor de FPS y Ping en tiempo real, junto a una lista de módulos activos (ArrayList) ordenada por anchura con bordes neón. |
| **ESP** | Cajas delimitadoras (*Bounding Boxes*) 2D/3D con esquemas de color configurables para rastrear rivales a través de paredes. |
| **Tracers** | Trazado de líneas vectoriales directas hacia los jugadores circundantes. |
| **Nametags** | Etiquetas de jugador escaladas, claras y de alta resolución con barra de vida, armadura y distancia. |
| **Hitboxes** | Visualización tridimensional del volumen de colisión de las entidades. |
| **Fullbright** | Iluminación gamma permanente para visibilidad total en cuevas y combate nocturno. |
| **NoHurtCam** | Elimina la sacudida violenta de la cámara al sufrir daño. |

---

### 🛠️ Utils & Configs

| Módulo | Descripción |
| :--- | :--- |
| **FastPlace** | Reduce el retardo de colocación de bloques a cero milisegundos para construcciones ultra-rápidas. |
| **Configs System** | Guardado, exportación y carga instantánea de perfiles de configuración almacenados en `%APPDATA%\CywuuClient\configs`. |
| **Auth Shield** | Verificación segura en el inicio con soporte de clave personalizada (`%APPDATA%\CywuuClient\key.txt`). |

---

## 💉 Guía de Inyección con Process Hacker

Para garantizar una inyección limpia, indetectable y sin interferencias:

1. **Abrir el Juego**:
   - Inicia **Lunar Client**, Forge o tu cliente preferido de Minecraft 1.8.9 (en 64 bits).
   - Entra al menú principal o a cualquier servidor/mundo de práctica.

2. **Ejecutar Process Hacker**:
   - Descarga e inicia **Process Hacker 2** (o **System Informer**) con **Permisos de Administrador** (clic derecho ➔ *Ejecutar como administrador*).

3. **Inyectar la DLL**:
   - En la lista de procesos, busca y selecciona **`javaw.exe`** (el proceso correspondiente a Minecraft).
   - Haz clic derecho sobre `javaw.exe` ➔ navega a **`Miscellaneous`** ➔ haz clic en **`Inject DLL...`**.
   - Busca y selecciona el archivo compilado:
     ```text
     cywuu-client\x64\Release\CywuuClient.dll
     ```
     *(o `WellLovely.dll` si utilizas un cargador automatizado legacy)*.

4. **Autenticación en Pantalla**:
   - Aparecerá la ventana de seguridad solicitando tu clave de acceso.
   - Introduce tu clave privada (por defecto: `Cywuu2026` o tu clave guardada en `key.txt`) y presiona **Desbloquear**.

5. **¡Listo para Jugar!**:
   - Regresa a la ventana de Minecraft.
   - Presiona la tecla **Flecha Arriba** (`↑`) en tu teclado para desplegar el menú de **Cywuu Private Client**.

---

## 🔨 Compilación desde el Código Fuente

Si realizas modificaciones al código y deseas compilar una nueva versión:

```powershell
# Compilar con MSBuild en modo Release x64
& "C:\Program Files\Microsoft Visual Studio\18\Community\MSBuild\Current\Bin\MSBuild.exe" CywuuClient.vcxproj /p:Configuration=Release /p:Platform=x64
```

Los binarios se exportan automáticamente a:
- `x64\Release\CywuuClient.dll`
- `x64\Release\WellLovely.dll` *(copia de compatibilidad)*

---

<p align="center">
  <sub>Desarrollado exclusivamente para Cywuu Private Client • 2026</sub>
</p>
