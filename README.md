<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FitShift</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #007BFF;
      --secondary-color: #00BFFF;
      --accent-color: #E0F7FF;
      --bg-color: #F0F8FF;
      --white: #ffffff;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: var(--bg-color);
      color: #333;
    }

    header {
      background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
      color: var(--white);
      padding: 1rem 2rem;
      text-align: center;
    }

    .container {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 1rem;
      background: var(--white);
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: var(--primary-color);
      margin-bottom: 1rem;
    }

    section {
      margin-bottom: 2rem;
    }

    .form-group {
      margin-bottom: 1rem;
    }

    input, select, button {
      padding: 0.5rem;
      width: 100%;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      background-color: var(--primary-color);
      color: var(--white);
      border: none;
      cursor: pointer;
      margin-top: 1rem;
    }

    .routine img {
      width: 100px;
      border-radius: 10px;
      margin-right: 1rem;
    }

    .progress, .tips, .calorie-counter, .integration, .community, .achievements, .nutrition {
      background-color: var(--accent-color);
      padding: 1rem;
      border-radius: 8px;
      margin-bottom: 1rem;
    }

    .flex {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }

  </style>
</head>
<body>
  <header>
    <h1>FitShift</h1>
    <p>Tu transformación comienza aquí</p>
  </header>

  <div class="container">
    
    <section id="auth">
      <h2>Inicia sesión o regístrate</h2>
      <div class="form-group">
        <input type="email" placeholder="Correo electrónico">
      </div>
      <div class="form-group">
        <input type="password" placeholder="Contraseña">
      </div>
      <button>Entrar</button>
    </section>

    <section id="survey">
      <h2>Datos personales y nivel de actividad</h2>
      <div class="form-group">
        <label>Edad</label>
        <input type="number" placeholder="Edad">
      </div>
      <div class="form-group">
        <label>Estatura (cm)</label>
        <input type="number" placeholder="Ej. 170">
      </div>
      <div class="form-group">
        <label>Peso actual (kg)</label>
        <input type="number" placeholder="Ej. 70">
      </div>
      <div class="form-group">
        <label>Actividad física</label>
        <select>
          <option>Sedentario</option>
          <option>Ligero</option>
          <option>Moderado</option>
          <option>Activo</option>
          <option>Muy activo</option>
        </select>
      </div>
      <div class="form-group">
        <label>Objetivo</label>
        <select>
          <option>Bajar de peso</option>
          <option>Tonificar</option>
          <option>Ganar masa muscular</option>
        </select>
      </div>
      <button>Calcular rutina personalizada</button>
    </section>

    <section id="routine">
      <h2>Rutina semanal recomendada</h2>
      <div class="flex routine">
        <img src="https://via.placeholder.com/100" alt="Ejercicio 1">
        <img src="https://via.placeholder.com/100" alt="Ejercicio 2">
        <img src="https://via.placeholder.com/100" alt="Ejercicio 3">
      </div>
    </section>

    <section class="nutrition">
      <h2>Plan nutricional sugerido</h2>
      <p>Tu objetivo calórico diario es: <strong>2200 kcal</strong> (ajustable según progreso).</p>
      <ul>
        <li>Proteínas: 40%</li>
        <li>Carbohidratos: 30%</li>
        <li>Grasas: 30%</li>
      </ul>
    </section>

    <section class="progress">
      <h2>Progreso personal</h2>
      <p>Ingresa tus mediciones y guarda tu evolución.</p>
      <div class="form-group">
        <label>Peso actual (kg)</label>
        <input type="number" placeholder="Ej. 68">
      </div>
      <div class="form-group">
        <label>Cintura (cm)</label>
        <input type="number" placeholder="Ej. 80">
      </div>
      <div class="form-group">
        <label>Pecho (cm)</label>
        <input type="number" placeholder="Ej. 95">
      </div>
      <button>Guardar progreso</button>
    </section>

    <section class="achievements">
      <h2>Logros</h2>
      <ul>
        <li>✅ 1 semana completando la rutina</li>
        <li>✅ Peso bajado 1 kg</li>
        <li>🏆 Registro diario de 7 días consecutivos</li>
      </ul>
    </section>

    <section class="community">
      <h2>Comunidad FitShift</h2>
      <p>Comparte tus avances y motivación con otros usuarios.</p>
      <button>Ir al foro</button>
    </section>

    <section class="integration">
      <h2>Integración con apps</h2>
      <p>Conecta FitShift con:</p>
      <ul>
        <li>📱 Google Fit</li>
        <li>🍏 Apple Health</li>
        <li>⌚ Fitbit</li>
      </ul>
    </section>
  </div>
</body>
</html><!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FitShift</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #007BFF;
      --secondary-color: #00BFFF;
      --accent-color: #E0F7FF;
      --bg-color: #F0F8FF;
      --white: #ffffff;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background-color: var(--bg-color);
      color: #333;
    }

    header {
      background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
      color: var(--white);
      padding: 1rem 2rem;
      text-align: center;
    }

    .container {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 1rem;
      background: var(--white);
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: var(--primary-color);
      margin-bottom: 1rem;
    }

    section {
      margin-bottom: 2rem;
    }

    .form-group {
      margin-bottom: 1rem;
    }

    input, select, button {
      padding: 0.5rem;
      width: 100%;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      background-color: var(--primary-color);
      color: var(--white);
      border: none;
      cursor: pointer;
      margin-top: 1rem;
    }

    .routine img {
      width: 100px;
      border-radius: 10px;
      margin-right: 1rem;
    }

    .progress, .tips, .calorie-counter, .integration, .community, .achievements, .nutrition {
      background-color: var(--accent-color);
      padding: 1rem;
      border-radius: 8px;
      margin-bottom: 1rem;
    }

    .flex {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }

  </style>
</head>
<body>
  <header>
    <h1>FitShift</h1>
    <p>Tu transformación comienza aquí</p>
  </header>

  <div class="container">
    
    <section id="auth">
      <h2>Inicia sesión o regístrate</h2>
      <div class="form-group">
        <input type="email" placeholder="Correo electrónico">
      </div>
      <div class="form-group">
        <input type="password" placeholder="Contraseña">
      </div>
      <button>Entrar</button>
    </section>

    <section id="survey">
      <h2>Datos personales y nivel de actividad</h2>
      <div class="form-group">
        <label>Edad</label>
        <input type="number" placeholder="Edad">
      </div>
      <div class="form-group">
        <label>Estatura (cm)</label>
        <input type="number" placeholder="Ej. 170">
      </div>
      <div class="form-group">
        <label>Peso actual (kg)</label>
        <input type="number" placeholder="Ej. 70">
      </div>
      <div class="form-group">
        <label>Actividad física</label>
        <select>
          <option>Sedentario</option>
          <option>Ligero</option>
          <option>Moderado</option>
          <option>Activo</option>
          <option>Muy activo</option>
        </select>
      </div>
      <div class="form-group">
        <label>Objetivo</label>
        <select>
          <option>Bajar de peso</option>
          <option>Tonificar</option>
          <option>Ganar masa muscular</option>
        </select>
      </div>
      <button>Calcular rutina personalizada</button>
    </section>

    <section id="routine">
      <h2>Rutina semanal recomendada</h2>
      <div class="flex routine">
        <img src="https://via.placeholder.com/100" alt="Ejercicio 1">
        <img src="https://via.placeholder.com/100" alt="Ejercicio 2">
        <img src="https://via.placeholder.com/100" alt="Ejercicio 3">
      </div>
    </section>

    <section class="nutrition">
      <h2>Plan nutricional sugerido</h2>
      <p>Tu objetivo calórico diario es: <strong>2200 kcal</strong> (ajustable según progreso).</p>
      <ul>
        <li>Proteínas: 40%</li>
        <li>Carbohidratos: 30%</li>
        <li>Grasas: 30%</li>
      </ul>
    </section>

    <section class="progress">
      <h2>Progreso personal</h2>
      <p>Ingresa tus mediciones y guarda tu evolución.</p>
      <div class="form-group">
        <label>Peso actual (kg)</label>
        <input type="number" placeholder="Ej. 68">
      </div>
      <div class="form-group">
        <label>Cintura (cm)</label>
        <input type="number" placeholder="Ej. 80">
      </div>
      <div class="form-group">
        <label>Pecho (cm)</label>
        <input type="number" placeholder="Ej. 95">
      </div>
      <button>Guardar progreso</button>
    </section>

    <section class="achievements">
      <h2>Logros</h2>
      <ul>
        <li>✅ 1 semana completando la rutina</li>
        <li>✅ Peso bajado 1 kg</li>
        <li>🏆 Registro diario de 7 días consecutivos</li>
      </ul>
    </section>

    <section class="community">
      <h2>Comunidad FitShift</h2>
      <p>Comparte tus avances y motivación con otros usuarios.</p>
      <button>Ir al foro</button>
    </section>

    <section class="integration">
      <h2>Integración con apps</h2>
      <p>Conecta FitShift con:</p>
      <ul>
        <li>📱 Google Fit</li>
        <li>🍏 Apple Health</li>
        <li>⌚ Fitbit</li>
      </ul>
    </section>
  </div>
</body>
</html>
