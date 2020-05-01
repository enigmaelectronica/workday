# workday
translation for spanish
the file path for the Script is located in:
\\application\resources\lang

Cambiar formato de fecha ingles a español:
carpeta:
\application\resources\views
Linea 80 archivo clock.blade.php
cambiar esto:
elDate.innerHTML = time.format('MMMM D, YYYY');
por esto:
elDate.innerHTML = time.format('D MMMM, YYYY');
