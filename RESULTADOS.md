# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 19 correctas de 22 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.55 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
🚨 `JOIN` sin índice. Revisar claves foráneas e índices.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,5 +1,4 @@
 nombre
-Informática
 Matemáticas
 Economía y Empresa
 Educación
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_profesor, PRIMARY,id_departamento, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
+grado | total
 Grado en Ingeniería Informática (Plan 2015) | 51.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_grado

---

## ❌ Query 22: Error
- **Descripción**: 'NoneType' object is not iterable

