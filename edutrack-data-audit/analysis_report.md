# EduTrack — Informe de análisis

## 1. Inscripciones en 'Intro to Python'

Resultado: 5

| student_name | student_email | completion_percentage |
| ------------ | --------------------------------- | --------------------- |
| Emily Watson | emily.watson@student.edutrack.com | 85 |
| Klaus Weber | klaus.weber@student.edutrack.com | 92 |
| Marco Rossi | marco.rossi@student.edutrack.com | 88 |
| James Miller | james.miller@test.com | 30 |
| Priya Sharma | priya.sharma@student.edutrack.com | 55 |

---

## 2. Posibles abandonos

Resultado: 4

| id | student_id | student_name | student_email | course_id | course_title | category | enrollment_date | completion_percentage | passed | monthly_fee_paid | instructor |
| -- | ---------- | --------------- | ------------------------------------ | --------- | --------------------- | --------- | --------------- | --------------------- | ------ | ---------------- | ------------ |
| 5 | 3 | Lucia Fernandes | lucia.fernandes@student.edutrack.com | 2 | Web Design Basics | Design | 2024-06-20 | 5 | false | 39.99 | Carlos Vega |
| 6 | 3 | Lucia Fernandes | lucia.fernandes@student.edutrack.com | 4 | Digital Marketing 101 | Marketing | 2024-07-01 | 3 | false | 29.99 | Lucia Prades |
| 10 | 5 | Yuki Nakamura | yuki.nakamura@student.edutrack.com | 6 | UI/UX Fundamentals | Design | 2024-10-11 | 0 | false | 44.99 | null |
| 11 | 6 | Pierre Dubois | pierre.dubois@student.edutrack.com | 6 | UI/UX Fundamentals | Design | 2024-11-05 | 0 | false | 44.99 | null |

---

## 3. Inscripciones sin instructor

Resultado: 2

| id | student_id | student_name | student_email | course_id | course_title | category | enrollment_date | completion_percentage | passed | monthly_fee_paid | instructor |
| -- | ---------- | ------------- | ---------------------------------- | --------- | ------------------ | -------- | --------------- | --------------------- | ------ | ---------------- | ---------- |
| 10 | 5 | Yuki Nakamura | yuki.nakamura@student.edutrack.com | 6 | UI/UX Fundamentals | Design | 2024-10-11 | 0 | false | 44.99 | null |
| 11 | 6 | Pierre Dubois | pierre.dubois@student.edutrack.com | 6 | UI/UX Fundamentals | Design | 2024-11-05 | 0 | false | 44.99 | null |

---

## 4. Top 5 no aprobados con mayor progreso

Resultado: 5

| student_name | course_title | completion_percentage | passed |
| ------------- | ---------------------- | --------------------- | ------ |
| Emily Watson | Web Design Basics | 60 | false |
| Priya Sharma | Intro to Python | 55 | false |
| Yuki Nakamura | Data Analysis with SQL | 45 | false |
| Emily Watson | Advanced Python | 40 | false |
| James Miller | Intro to Python | 30 | false |

---

## 5. Inscripciones del último año

Resultado: 0

---

## 6. Agregar inscripción faltante

Resultado: 1

| id | student_id | student_name | student_email | course_id | course_title | category | enrollment_date | completion_percentage | passed | monthly_fee_paid | instructor |
| -- | ---------- | --------------- | ------------------------------------ | --------- | --------------- | ----------- | --------------- | --------------------- | ------ | ---------------- | ----------- |
| 18 | 3 | Lucia Fernandes | lucia.fernandes@student.edutrack.com | 5 | Advanced Python | Programming | 2025-04-01 | 0 | false | 69.99 | Carlos Vega |

---

## 7. Corregir instructores NULL

Resultado: 2 registros actualizados a 'Pending assignment'

*(Verificación previa: se encontraron los registros ID 10 e ID 11 con instructor en NULL antes de la actualización)*

---

## 8. Eliminar cuentas de prueba

Resultado: 2 registros eliminados (@test.com)

*(Verificación previa: se identificaron los registros de James Miller y Alex Chen antes del DELETE)*

---

## 9. Inscripciones por categoría

Resultado:

| category | total_enrollments |
| ----------- | ----------------- |
| Marketing | 2 |
| Programming | 7 |
| Design | 4 |
| Data | 3 |

---

## 10. Promedio de completado por curso

Resultado:

| course_title | average_completion |
| ---------------------- | ---------------------- |
| UI/UX Fundamentals | 0.00000000000000000000 |
| Web Design Basics | 32.5000000000000000 |
| Digital Marketing 101 | 36.5000000000000000 |
| Advanced Python | 45.0000000000000000 |
| Data Analysis with SQL | 47.6666666666666667 |
| Intro to Python | 80.0000000000000000 |

---

## 11. Cursos con más de 3 inscripciones

Resultado:

| course_title | total_enrollments |
| --------------- | ----------------- |
| Intro to Python | 4 |

---

## 12. Ingresos totales por categoría

Resultado:

| category | total_revenue |
| ----------- | ------------- |
| Programming | 409.93 |
| Data | 179.97 |
| Design | 169.96 |
| Marketing | 59.98 |