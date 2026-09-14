---
type: experience
title: "Diseño del Atlas doméstico de cocina"
created: "2026-09-14"
work_id: "2026-09-14-cocina-atlas-schema"
status: in-discussion
kva: forming
reality: current
description: "Hub para diseñar un modelo de recetas, ingredientes, utensilios, compras, despensa y planificación de comidas."
origin: user
sensitivity: internal
relates_to:
  - path: autogenesis/work/2026-09-14-cocina-atlas-schema.md
    kind: implements
---

## Subject

Cómo estructurar un Atlas doméstico que conecte recetas, ingredientes,
utensilios, compras y existencias de la despensa para ayudar a elegir comidas.

## Objective

Llegar a una estructura de dominio útil para registrar recetas y utensilios,
controlar compras y despensa, y proponer comidas según los productos
disponibles, sin confundir conocimiento estable con inventario cambiante.

## Current distinction

La conversación parte de dos capas relacionadas:

1. **Conocimiento culinario:** recetas, ingredientes, cantidades, pasos,
   variantes, utensilios y restricciones.
2. **Estado doméstico:** compras, existencias, cantidades disponibles,
   ubicaciones, caducidades y prioridades de consumo.

La planificación de comidas será una capacidad derivada de ambas capas, no
necesariamente una entidad primaria desde el primer día.

## Batch still on the hub

1. ¿El dominio debe cubrir solo recetas familiares y productos reales de la
   despensa, o también un catálogo general de alimentos y sustituciones?
2. ¿Necesitamos cantidades precisas y unidades convertibles, o basta inicialmente
   con disponibilidad cualitativa y tamaños de envase?
3. ¿La despensa debe representar el estado actual o también un historial de
   compras, consumos y caducidades?
4. ¿La ayuda debe priorizar "qué puedo cocinar ahora", "qué debo comprar" o
   "cómo planificar varios días"?

## Current branch

The first decision is recorded in domain-boundary.md. The remaining open
questions are forming protostars linked from this hub.
