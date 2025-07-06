# Forense-Chain-
Sistema decentralizado de registro forense 
---

# Forense Chain – Custodia de Evidencia con Seguridad Blockchain

**Por: LAEV (Lerry Alexander Elizondo Villalobos) – El Cartel de Bitcoiners**

## 🧠 Visión General

_Forense Chain_ es una arquitectura descentralizada de **registro, verificación y resguardo de evidencia forense** sobre la red Bitcoin. Utiliza la inmutabilidad de la cadena de bloques para construir una **cadena de custodia digital** verificable, a prueba de alteraciones, manipulaciones y omisiones.

Diseñado para operar tanto de forma **autónoma** como **integrada a sistemas ya existentes**, Forense Chain actúa como **candado criptográfico de seguridad**, capaz de registrar desde el evento más mínimo (una apertura de puerta) hasta interacciones críticas con pruebas sensibles.

---

## 🛠️ ¿Cómo Funciona?

Forense Chain opera bajo una lógica de **registro progresivo con hashes encadenados**, verificados públicamente en la red Bitcoin. Puede funcionar en dos modos:

### 🔁 Modalidad Adaptativa
Integra Forense Chain a sistemas tradicionales (laboratorios, software de criminalística, cámaras, etc.) y utiliza Bitcoin para firmar y certificar eventos clave.

### 🧱 Modalidad Propositiva
Implementación desde cero. Cada evento se registra directamente sobre Bitcoin como una transacción `OP_RETURN` o a través de soluciones de segunda capa (L2, timestamping, sidechains).

---

## 🔐 Candado Forense: Registro Progresivo

1. **Ingreso a la escena o laboratorio**
   - Se genera Hash-A (ej: escaneo de ID, ingreso físico).
2. **Interacciones sucesivas**
   - Hash-B, C, D… Cada acción (abrir caja, extraer objeto, tomar nota) genera un nuevo hash encadenado al anterior.
3. **Evidencia alcanzada**
   - Hash final con ubicación de la prueba, identidad del agente, hora, y estado de integridad.

> Si en cualquier momento un hash intermedio no existe o no coincide, se activa una **alerta de ruptura en la cadena de custodia**.

---

## ⚠️ Verificación de Autenticidad

Forense Chain admite dos flujos de verificación:

- **De adentro hacia afuera:** registros internos del sistema se firman y publican en la red Bitcoin.
- **De afuera hacia adentro:** peticiones externas son validadas contra los registros en blockchain antes de ser admitidas como evidencias.

---

## 🌐 Aplicaciones Reales

- Escenas de crimen / Investigación criminal
- Juicios de alto perfil / Evidencia digital
- Protección de whistleblowers
- Derechos humanos / Periodismo de guerra
- Prisiones, cárceles, arresto domiciliario
- Custodia legal de archivos, servidores y bases de datos

---

## 🧰 Tecnologías y Herramientas

- Bitcoin Mainnet (OP_RETURN / Inscripciones)
- API para broadcasting de transacciones
- Hashing SHA256, HMAC
- Cliente CLI compatible con Termux o Linux
- Opcional: firma multisig para autenticación distribuida

---

## 🧪 Ejemplo de Registro (Simplificado)

```bash
# Registro de entrada a escena
forense_chain register --event "Ingreso Lab 4" --agent "ID:890213" --location "Oficina Judicial A" --timestamp

# Resultado: hash SHA256 generado y firmado
# Transacción OP_RETURN enviada a la red Bitcoin


---

📄 Licencia

Este proyecto está licenciado bajo la Licencia LAEV – Código con Honor.
No se autoriza su uso para fines autoritarios, corporativos opresivos o vigilancia estatal sin auditoría pública.
Todo uso debe respetar la soberanía del individuo y los principios del Cartel de Bitcoiners.


---

🤝 Autor y Contacto

LAEV (Lerry Alexander Elizondo Villalobos)
Fundador de El Cartel de Bitcoiners
📧 laev.lab@proton.me | laev.lab.ele@gmail.com
🌍 GitHub
📞 +50671148872


---

🧭 Roadmap (Próximamente)

[ ] Script CLI para registro en Termux

[ ] Web UI para custodia de evidencia

[ ] Integración con escáner de huellas/QR

[ ] Prueba piloto en laboratorio forense

[ ] Validación jurídica de cadena de custodia blockchain



---

🔥 Manifiesto

La verdad no se negocia.
La evidencia no se pierde.
Y si se pierde... la cadena grita.

#ForenseChain

---

