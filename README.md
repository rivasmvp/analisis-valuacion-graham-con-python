Análisis fundamental de empresas con Python📊

Propósito: Indica si la empresa cotiza debajo de su precio justo (fórmula Graham con lógica conservadora) de forma automatizada. 
Si cotiza por encima de su fair value + margen de seguridad se infiere un precio de burbuja especulativa.
Implementa una lógica de "freno de mano" al 15% de tasa de crecimiento para que no arroje un crecimiento explosivo sin coherencia. El fallback asigna valores conservadores de seguridad.

Fallo: Empresas con perdidas históricas, EPS erráticos o alta volatilidad.
