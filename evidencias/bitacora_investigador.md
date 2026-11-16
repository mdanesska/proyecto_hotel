# 📝 Bitácora de Investigación - Gran Hotel Olimpo
**Equipo Auditor:** Danesska & Daniela  
**Fecha:** [13/11/2026]

---

## 1. 🔑 Hallazgo Inicial (Puerta 1 - Git Bash)
* **Comando utilizado para encontrar la credencial oculta:** `cat .llave_maestra.txt`
* **Código de la Llave Maestra:** `GH-OLIMPO-DATA-2026-KEY`
* **Primera anomalía detectada en el servidor:**  Revisando la carpeta `data/reservas_raw.csv`, hemos descubierto que el atacante introdujo 10 FILAS TOTALMENTE DUPLICADAS e intencionadamente dejó celdas vacías (NaN) en precios y noches.

---

## 2. 🛡️ Registro de Control de Versiones (Puerta 2 - Git & GitHub)
* **Comando para preparar archivos (Staging):** `git init`
* **Mensaje del primer commit local:** `git commit -m "feat: inicio de investigacion tras ataque al GRAN HOTEL OLIMPO"
On branch main
Your branch is up to date with 'origin/main`
* **URL del repositorio público en GitHub:** `https://github.com/mdanesska/proyecto_hotel.git`

---

## 3. 🗺️ Arquitectura y Entorno (Puerta 4 - VS Code & Dependencies)
* **Versión de Python detectada:** `...`
* **Comando utilizado para instalar `requirements.txt`:** `...`
* **Diferencia entre Ruta Absoluta y Ruta Relativa (explicación breve):** 

---

## 4. ⚙️ Conciliación Financiera (Puerta 5 - Python CLI)
* **Facturación Bruta (Sin filtrar):** `... €`
* **Facturación Neta Real (Solo Completadas):** `... €`
* **Fuga Financiera (Canceladas + Devueltas):** `... €`
* **Conclusión de Negocio:** ¿Por qué no debemos tomar decisiones con la facturación bruta?

---

## 5. 🔮 Auditoría Final e IA Generativa (Puerta 6 - Jupyter & Prompting)
* **Número de duplicados exactos eliminados:** `...`
* **Respuesta de la LLM tras enviar el Prompt Estructurado:**
  > [Pegar aquí la síntesis generada por la IA]
* **Verificación de Factualidad y Sesgos (Guardrails):**
  - ¿La IA inventó algún dato que no estuviera en el contexto? (Sí/No y detalle):
  - ¿El lenguaje utilizado es neutro y libre de sesgos de culpabilidad?

---

## 🏁 Semáforo de Autoevaluación Individual
* **Piloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*
* **Copiloto:** 🟢 Verde / 🟡 Amarillo / 🔴 Rojo — *Comentario:*