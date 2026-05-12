# Monica_Assistant2.0
Proyecto Monica Assistant V 2.0


Por temas de confidencialidad con la compañía, no puedo compartir el código ni una prueba del código de la solución desarrollada.

**MONICA Assistant 2.0** es una plataforma web interna desarrollada para **Flextronics North**, utilizada por múltiples áreas del campus para la gestión de recursos de software, instalaciones y consultas automatizadas mediante una asistente virtual.  
El proyecto aborda problemas críticos de **rendimiento, saturación del servidor y obsolescencia tecnológica**, proponiendo una **migración del frontend a React.js** como solución estratégica, técnica y financiera.

---

## 📖 Descripción

MONICA Assistant es una solución web corporativa que centraliza:

- Solicitudes de instalación de software.
- Consultas a la base de datos corporativa mediante APIs.
- Ejecución de procesos internos automatizados.
- Interacción mediante asistente virtual.

La plataforma es utilizada por **cientos de empleados** y depende de una arquitectura web conectada a servicios backend y bases de datos corporativas.

---

## ❗ Problema Identificado

Se detectaron los siguientes problemas clave:

1. **Saturación del servidor**, provocando procesos colgados durante registros de instalación.
2. **Framework frontend obsoleto**, sin soporte ni compatibilidad moderna.
3. **Lenguaje propietario con costos de licencia**, no alineado con la infraestructura actual.
4. **Baja escalabilidad** debido a un backend monolítico y frontend poco optimizado.

### Impacto
- Procesos detenidos hasta 10 minutos.
- Afectación directa al flujo operativo de los usuarios.
- Incremento de costos operativos y de licencias.
- Limitación para innovar o integrar nuevas tecnologías.

---

## ✅ Solución Propuesta

La solución implementada consiste en:

- **Reescritura de componentes críticos en React.js**
- **Migración progresiva del frontend completo al stack React**
- Optimización de llamadas a la API (Axios / fetch optimizado)
- Uso de renderizado bajo demanda
- Eliminación de frameworks propietarios

### Resultados Clave
- ✅ Reducción del **56% en procesos colgados**
- ✅ Mejora del **50% en tiempo de respuesta**
- ✅ Eliminación del **100% del costo de licencias**
- ✅ ROI estimado del **43.6% en el primer semestre**

---

## 🏗 Arquitectura

### Arquitectura General

- **Frontend:** React.js + Vite + Tailwind CSS
- **Backend:** API corporativa (modelo modular)
- **Base de datos:** Base de datos corporativa interna
- **Autenticación:** JWT / LDAP
- **Infraestructura:** Servidor web interno

### Enfoque Arquitectónico

