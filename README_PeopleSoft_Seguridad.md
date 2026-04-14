# 🔐 Gestión de Seguridad en PeopleSoft HRMS (Capítulo 5)

## 1. ¿Qué es la Seguridad en HRMS?
Controla quién accede, qué ve y qué puede hacer en el sistema.

**Principio:** Acceso mínimo necesario.

---

## 2. Estructura de Seguridad
Usuario → Rol → Lista de Permisos → Acceso a Componentes + Datos

- Usuario: Persona
- Rol: Función
- Permission List: Accesos técnicos
- Row Security: Datos visibles

📊 Gráfico conceptual
        👤 Usuario
            │
            ▼
        🎭 Rol(es)
            │
            ▼
   📜 Lista de Permisos
      │           │
      ▼           ▼
  🔐 Menús     📊 Datos (Row Security)

---

## 3. Tipos de Seguridad

### Seguridad de Aplicación
Acceso a menús y páginas.

### Seguridad de Datos
- Por departamento (árboles)
- Por rol
- Por campos (BU, Location)

---

## 4. Tablas Clave
- SJT_CLASS_ALL
- SJT_OPR_CLS

---

## 5. Flujo
1. Definir roles
2. Asignar permisos
3. Configurar datos
4. Ejecutar procesos
5. Usuario accede

---

## 6. Ejemplo
Analista RRHH:
- Ve solo empleados de RRHH
- No ve Finanzas

---

## 7. Árboles
Control jerárquico de acceso.

---

## 8. Procesos Batch
- Actualización nocturna
- SJT_CLASS_ALL

---

## 9. Seguridad de Usuarios
- Crear
- Bloquear
- Asignar roles

---

## 10. Buenas Prácticas
- Usar roles
- Auditar accesos
- Ejecutar procesos
- Mantener estructuras actualizadas
