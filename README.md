<p align="center">
  <img src="banner.svg" width="100%" alt="Paolo Jove. Macroeconomía, finanzas y análisis de datos. Lima, Perú. El gráfico muestra la inflación del Perú a 12 meses y la tasa de referencia del BCRP desde 2004.">
</p>

Estudiante de 8.º semestre (por iniciar el 9.º) en la **Pontificia Universidad Católica del Perú**. Cursé **FM350 Advanced Corporate Finance** de forma presencial en la **London School of Economics (LSE)**, en Londres. Aquí publico proyectos de macroeconomía, finanzas y análisis de datos aplicados al Perú.

**Busco prácticas pre-profesionales en Lima** en finanzas corporativas y banca de inversión, estudios económicos, gestión de riesgos, análisis de datos y auditoría interna.

[LinkedIn](https://www.linkedin.com/in/paolo-jove-085647127)

## Proyectos

<table>
  <tr>
    <td width="44%"><a href="https://github.com/paolojoveal/portafolio-finanzas"><img src="img/portafolio-finanzas.png" alt="Respuesta de la tasa, la inflación, las expectativas y la brecha del producto a un alza de 25 puntos básicos en la tasa de referencia"></a></td>
    <td>
      <h3><a href="https://github.com/paolojoveal/portafolio-finanzas">portafolio-finanzas</a></h3>
      Siete proyectos con datos del BCRP y de mercado: valorización DCF con su modelo en Excel, optimización de portafolio, VaR con backtesting, política monetaria, scorecard de crédito, tablero macro y finanzas corporativas (LBO, M&amp;A, venture capital).<br><br>
      <b>Un resultado:</b> el BCRP responde a las expectativas de inflación (coeficiente de 3.0), no a la inflación del mes (1.0).<br><br>
      <code>Python</code> <code>statsmodels</code> <code>scikit-learn</code> <code>Streamlit</code>
    </td>
  </tr>
  <tr>
    <td><a href="https://github.com/paolojoveal/auditoria-analitica-ventas"><img src="img/auditoria-analitica-ventas.png" alt="Número de excepciones e importe expuesto en cada una de las diez pruebas de auditoría"></a></td>
    <td>
      <h3><a href="https://github.com/paolojoveal/auditoria-analitica-ventas">auditoria-analitica-ventas</a></h3>
      Diez pruebas de auditoría interna en SQL sobre el 100% de las ventas de una distribuidora ficticia, con informe, papeles de trabajo en Excel y un análisis de qué usuarios concentran las excepciones.<br><br>
      <b>Un resultado:</b> detectar es la parte fácil. La prueba de fraccionamiento marca 47 casos y 17 son operaciones legítimas.<br><br>
      <code>SQL</code> <code>SQLite</code> <code>Python</code> <code>Excel</code>
    </td>
  </tr>
  <tr>
    <td><a href="https://github.com/paolojoveal/muestreo-auditoria"><img src="img/muestreo-auditoria.png" alt="Probabilidad de aceptar un saldo según su error real, para tres planes de muestreo"></a></td>
    <td>
      <h3><a href="https://github.com/paolojoveal/muestreo-auditoria">muestreo-auditoria</a></h3>
      Muestreo estadístico para auditar lo que no se puede revisar completo: atributos para probar controles y unidad monetaria con cota de Stringer para probar saldos, con un caso de principio a fin.<br><br>
      <b>Un resultado:</b> una muestra de 154 partidas sin un solo error no prueba que el saldo esté limpio. Solo permite afirmar que el error no supera S/ 221 105.<br><br>
      <code>Python</code> <code>estadística</code> <code>auditoría</code> <code>Monte Carlo</code>
    </td>
  </tr>
  <tr>
    <td><a href="https://github.com/paolojoveal/proyecciones-locales"><img src="img/proyecciones-locales.png" alt="Cobertura efectiva de los intervalos de confianza de 90% por horizonte, para tres métodos de inferencia y dos niveles de persistencia"></a></td>
    <td>
      <h3><a href="https://github.com/paolojoveal/proyecciones-locales">proyecciones-locales</a></h3>
      El estimador de proyecciones locales escrito desde cero, una simulación de Monte Carlo sobre sus intervalos de confianza, el bootstrap que los corrige y una aplicación al efecto del precio del cobre en la economía peruana.<br><br>
      <b>Un resultado:</b> con series persistentes, un intervalo tradicional «de 90%» contiene el valor verdadero 62% de las veces. Con bootstrap, 88%.<br><br>
      <code>Python</code> <code>NumPy</code> <code>econometría</code> <code>Monte Carlo</code>
    </td>
  </tr>
</table>

## Cómo trabajo

- **Los datos se verifican antes de usarse.** Cada serie del BCRP se comprueba contra su nombre oficial al descargarla, y una descarga incompleta no se guarda.
- **Cada cálculo tiene una prueba con respuesta conocida.** Los cuatro repositorios corren sus pruebas en GitHub Actions: comparaciones con `statsmodels`, fórmulas cerradas y datos simulados con parámetros conocidos.
- **Los límites van escritos.** Cada README dice qué supuestos sostienen el resultado y qué no se puede concluir de él.

## Herramientas

Python (pandas, NumPy, statsmodels, scikit-learn, matplotlib, Plotly, Streamlit) · SQL · Git y GitHub Actions · Excel
