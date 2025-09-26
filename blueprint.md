
# Blueprint: Faysuris.com

## Propósito y Capacidades

Faysuris.com es un sitio web de Astro.js diseñado para una empresa con un triple rol:

1.  **Nail Spa:** Ofrece servicios de belleza y cuidado de uñas de alta calidad en Curazao.
2.  **Marca Propia:** Desarrolla y comercializa **Fays**, su propia línea de esmaltes para uñas.
3.  **Distribuidor Oficial:** Vende y distribuye productos de belleza de las marcas **Staleks** y **Arobell**, siendo los distribuidores exclusivos para toda la región del Caribe.

El objetivo del sitio es atraer clientes locales para el spa, construir la marca Fays y consolidarse como el punto de venta de referencia en el Caribe para profesionales que buscan Staleks y Arobell.

## Outline del Proyecto

*   **Framework:** Astro.js
*   **Estilos:** Tailwind CSS.
*   **Funcionalidades:** Página de inicio con presentación de las marcas principales (Fays, Staleks, Arobell).
*   **Diseño:** Diseño moderno y responsive con un fondo desenfocado y logos de marcas interactivos.

## Plan Actual: Refactorización a Tailwind CSS

*   **Objetivo:** Refactorizar el componente `Welcome.astro` para utilizar exclusivamente clases de utilidad de Tailwind CSS, eliminando todo el CSS en línea del bloque `<style>`.
*   **Pasos:**
    1.  **Analizar Estilos Existentes:** Revisar el bloque `<style>` en `Welcome.astro` para entender los estilos actuales.
    2.  **Mapear a Clases de Tailwind:** Convertir todas las reglas de CSS a sus clases de utilidad de Tailwind CSS correspondientes, siguiendo un enfoque *mobile-first*.
    3.  **Aplicar Clases:** Reemplazar los `id` y `class` existentes en el HTML del componente con las nuevas clases de Tailwind.
    4.  **Eliminar Bloque de Estilo:** Borrar completamente el bloque `<style>` del archivo `Welcome.astro` para finalizar la refactorización.
