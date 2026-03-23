# Desarrollo web con HTML y CSS

Proyecto integrador orientado a practica de maquetado y organizacion de estilos.

## Objetivo
Construir una landing page para una agencia de marketing digital con:

- Presentacion del servicio
- Seccion de servicios
- Formulario de contacto
- Enlaces a redes sociales

## Estructura actual del proyecto

```text
public/
	index.html          -> estructura semantica del sitio

src/
	assets/             -> imagenes e iconos
	css/
		generic.css       -> variables, reset, tipografias, utilidades base
		styles.css        -> layout, componentes, responsive

modules/
	*.pdf               -> material de estudio por etapas
```

## Criterios del refactor aplicado

- HTML con semantica clara: header, nav, main, section, article y footer.
- Clases descriptivas y consistentes.
- CSS separado por responsabilidad:
	- generic.css para base global
	- styles.css para componentes y secciones
- Mejora de accesibilidad:
	- labels correctos en formulario
	- atributos aria en navegacion y redes
	- focus visible en controles
- Correccion de errores de marcado y enlaces.
- Diseno responsive para desktop, tablet y mobile.

## Como estudiar este proyecto

1. Empeza por public/index.html para entender la estructura general.
2. Segui con src/css/generic.css para ver tokens y reglas base.
3. Termina con src/css/styles.css para comprender como se construyen los componentes.
4. Proba cambios pequenos de colores, espaciados y tipografia para practicar.

## Referencia de diseno original

Figma:
https://www.figma.com/file/6BvM0dWolsIQl1ZEtT7YUl/Proyecto-HTML?node-id=0%3A1