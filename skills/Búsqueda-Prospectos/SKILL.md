---
name: sommos-busqueda-prospectos
description: 'Busca prospectos para Sommos según lo que se indique (segmento, país, tipo de entidad u otro criterio), identifica contactos clave, revisa si ya están en HubSpot y redacta el primer mensaje para cada uno. En Sommos "prospecto" y "lead" significan lo mismo. Úsalo SIEMPRE que pidan buscar, listar o investigar prospectos, leads, empresas o contactos para ofrecer soluciones de Sommos, aunque no mencionen HubSpot.'
---

# Búsqueda de prospectos (Sommos)

## 1. Objetivo
- Tener una lista de empresas y contactos clave para ofrecer soluciones de Sommos, sin repetir los que ya están en HubSpot, con el primer mensaje listo para enviar.

## 2. Cuándo se usa
- Cuando pidan buscar prospectos o leads. Por ejemplo: "busca prospectos de AFPs en Perú".

## 3. Datos de entrada
- Qué buscar: segmento, país, tipo de entidad u otro criterio.
- Opcional: producto de Sommos a ofrecer, cargos objetivo y cantidad de empresas.
- Si no se indica la cantidad: 10 empresas.
- Si el pedido es muy amplio (por ejemplo, "busca prospectos"), pregunta por el segmento o el país antes de empezar.

## 4. Proceso

### 4.1 Buscar empresas
- Busca primero en fuentes oficiales (regulador del país, gremios y listados oficiales) y después en rankings y prensa.
- Anota la fuente de cada empresa.

### 4.2 Revisar HubSpot
- Busca cada empresa en HubSpot por nombre y dominio.
- Si ya está: márcala como "Ya en HubSpot", con la etapa del deal y la fecha del último contacto, y no busques más contactos salvo que lo pidan.

### 4.3 Buscar contactos
- Para cada empresa nueva, busca de 1 a 3 contactos.
- Cargos a priorizar: gerencia general, gerencia comercial o de negocios, canales digitales, innovación y productos de ahorro.
- Fuentes: web de la empresa, notas de prensa y perfiles públicos de LinkedIn.
- Dato de contacto: solo correos publicados en una fuente pública o perfiles de LinkedIn. Nunca adivines ni armes correos.

### 4.4 Redactar el primer mensaje
- Usa el skill sommos-redactor-comercial (primer contacto en frío).
- Canal: correo si hay correo; LinkedIn si solo hay perfil.
- Elige el producto de Sommos que mejor encaje con la empresa y explica en una línea por qué.

## 5. Reglas
- No registres nada en HubSpot. Si Camila decide contactar a alguien, se registra con el skill sommos-contactos-hubspot.
- No envíes mensajes ni entres a LinkedIn con la sesión de nadie.
- Si un dato no se encuentra, deja el campo vacío y avísalo en el resumen. No lo completes con suposiciones.

## 6. Entrega

### 6.1 Dónde se entrega
- En el chat.

### 6.2 Tabla, con una fila por contacto
- Empresa, país y tipo de entidad.
- Dato relevante de la empresa (tamaño, número de clientes o foco).
- Contacto y cargo.
- Canal y dato de contacto (correo o link de LinkedIn).
- Fuente de la empresa y del contacto.
- Estado en HubSpot (nuevo o etapa del deal).
- Producto sugerido y mensaje propuesto.

### 6.3 Resumen final
- Número de empresas encontradas.
- Cuántas ya estaban en HubSpot, en caso de que haya alguna.
- Cuántos contactos tienen correo y cuántos solo LinkedIn.
