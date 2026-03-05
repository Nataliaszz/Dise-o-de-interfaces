# Design Tokens

Este documento define los átomos visuales del **Sistema de Predicción Longitudinal de Problemas Visuales**, garantizando consistencia y escalabilidad en el diseño.

---

## Paleta de Colores (Color Tokens)

| Token Name | Hex | Color Preview | Uso Principal |
| :--- | :--- | :--- | :--- |
| `primary-color` | `#9FEAE4` | ![#9FEAE4](https://via.placeholder.com/15/9FEAE4?text=+) | Acciones principales y marca. |
| `secondary-color` | `#C0FBFF` | ![#C0FBFF](https://via.placeholder.com/15/C0FBFF?text=+) | Fondos suaves y estados hover. |
| `title-color` | `#00747C` | ![#00747C](https://via.placeholder.com/15/00747C?text=+) | Títulos de alto contraste. |
| `background-color`| `#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/15/FFFFFF?text=+) | Superficie base de la interfaz. |
| `text-color` | `#000000` | ![#000000](https://via.placeholder.com/15/000000?text=+) | Cuerpo de texto y lectura. |

<img width="183" height="318" alt="image" src="https://github.com/user-attachments/assets/e875a78a-7dab-45b4-bf68-dccf48fd4612" />
<img width="185" height="321" alt="image" src="https://github.com/user-attachments/assets/2dc6167c-40da-4c7d-848b-c2a41541efda" />

---


###  Estados del Sistema
*  **Success:** `#4CAF50` | Predicciones positivas o procesos completados.
* **Warning:** `#448FB4` | Alertas informativas o preventivas.
*  **Error:** `#E53935` | Notificaciones de riesgo o errores críticos.
<img width="182" height="315" alt="image" src="https://github.com/user-attachments/assets/0fe99042-176f-4ec9-9ae7-dfb039451683" />

Warning Ejemplo


##  Tipografía y Escala (Typography Tokens)

| Token | Fuente | Tamaño | Aplicación |
| :--- | :--- | :--- | :--- |
| `font-size-title` | **Lato** | `32px` | Títulos de página y secciones. |
| `font-size-large` | **Roboto** | `24px` | Subtítulos y resaltados. |
| `font-size-medium`| **Roboto** | `18px` | Texto de lectura (Body). |
| `size-small` | **Roboto** | `14px` | Notas al pie y captions. |
<img width="186" height="310" alt="image" src="https://github.com/user-attachments/assets/6b09ebf2-c2d1-4f96-a9f5-3bcf116e01e5" />

aqui podemos visualizar todas las fuentes

---

## Estructura y UI (Layout Tokens)

### Bordes (Border Radius)
* `border-radius-small`: **4px** (Componentes pequeños, inputs).
* `border-radius-medium`: **8px** (Tarjetas, modales y botones).
  
  <img width="116" height="39" alt="image" src="https://github.com/user-attachments/assets/69e210a9-132c-4f6f-96ca-176bfe372931" />
<img width="173" height="267" alt="image" src="https://github.com/user-attachments/assets/dd00cda4-f4c3-4070-a78e-60fc94b80027" />


# Patterm library 

Coleccion de compones reutilizables 

## 1. Botones (Buttons)

| Componente | Especificaciones Visuales | Uso y Comportamiento |
| :--- | :--- | :--- |
| **Botón Entrar** | **Fondo:** `#C0FBFF` (Secondary)<br>**Texto:** Negro (`#000000`) <br>**Bordes:** `border-radius-medium` (8px) | Utilizado para confirmar citas y acciones principales tras completar formularios. |

<img width="109" height="38" alt="image" src="https://github.com/user-attachments/assets/a570cf19-5e2e-4507-b33b-af22261bbfba" />

---

## 2. Campos de Formulario (Inputs & Login)

**Nombre del Módulo:** Inicio de Sesión
Este componente gestiona el acceso seguro de los especialistas al sistema.

* **Campos:** Documento y Contraseña.
    * **Fondo de Input:** `#FFFFFF` (Blanco).
    * **Color de Títulos:** `#00747C` (Title Color).
* **Contenedor (Panel):** Fondo `#9FEAE4` (Primary Color).
* **Acciones:** * Botón "Entrar".
    * Enlace: *¿Olvidaste tu contraseña?*
* **Feedback de Error:** * **Mensaje:** Color `#448FB4` con bordes redondeados para notificaciones del sistema.

<img width="249" height="430" alt="image" src="https://github.com/user-attachments/assets/7037d9d4-bc07-4003-972f-9d5aa424e290" />


---

## 3. Tarjetas 

**Nombre:** Citas Programadas
Diseñadas para mostrar la información del paciente de forma rápida y clara.

| Elemento | Detalle |
| :--- | :--- |
| **Fondo** | `#C0FBFF` |
| **Cabecera** | Título con Fecha y Hora del encuentro. |
| **Contenido** | Nombre del Paciente y Cédula (ID). |
| **Acción** | Botón **"Historial"** (Fondo blanco, texto negro). |
| **Estilo** | Bordes redondeados (`8px`) para suavidad visual. |

**Uso:** Visualización rápida de la agenda diaria y acceso al registro histórico del paciente.

<img width="203" height="87" alt="image" src="https://github.com/user-attachments/assets/28a6b86e-4487-41a1-96df-7e8568ba779f" />

---

