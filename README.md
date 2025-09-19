# PartiPay – App de Compartir Gastos

PartiPay es una aplicación web hecha en **React + TypeScript** que permite crear eventos, añadir participantes y registrar gastos compartidos de forma sencilla. Los balances y liquidaciones se calculan automáticamente, evitando cuentas manuales y discusiones.

## ✨ Características

* Crear un **evento** con nombre y moneda.
* Añadir **participantes** (nombres personalizados).
* Registrar **gastos** con:

  * Importe base
  * Propina (puede pagarla otra persona)
  * Opción de **un solo pagador** o **varios (repartido)**
  * Selección de qué participantes disfrutaron el gasto
* Ver **balances individuales** (positivo = te deben, negativo = debes).
* Generar **liquidaciones sugeridas** con el mínimo número de pagos.
* **Exportar** a CSV/JSON e **importar** después.
* Datos guardados en **localStorage**.

## 🚀 Cómo usar

1. Clona el repo:

   ```bash
   git clone https://github.com/tuusuario/partipay.git
   cd partipay
   ```
2. Instala dependencias:

   ```bash
   npm install
   ```
3. Inicia en modo desarrollo:

   ```bash
   npm run dev
   ```
4. Abre en el navegador la URL indicada (normalmente `http://localhost:5173`).

## 📦 Build para producción

```bash
npm run build
npm run preview
```

## 📝 Ejemplo de uso

* Evento: *Fin de semana en Trives* (EUR)
* Participantes: Manolo, Ana, Kai 🐾
* Gastos:

  * Cena: 60€ pagados por Ana
  * Propina: 5€ puesta por Manolo
  * Café: 9€ pagado por Manolo, disfrutado solo por él y Ana

El sistema calculará automáticamente quién debe a quién y cuánto.

## 🤝 Contribuciones

¡Bienvenidas! Puedes abrir un **issue** o un **pull request**.

## 📄 Licencia

MIT
