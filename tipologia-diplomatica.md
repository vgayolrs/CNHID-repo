---
title: Tipología diplomática CNHID
author: Víctor Gayol
date: 2021 05 24
---

## Introducción

Uno de los puntos más importantes de la propuesta de marcado `TEI` es la posibilidad de establecer una taxonomía diplomática de los textos normativos editados; por una parte reales cédulas y, por la otra, las reales provisiones como ordenanzas, bandos, títulos, despachos o cualquiera que sea su naturaleza. Para elaborar la taxonomía se toma como base la tipología propuesta por José J. Real Díaz,[^1] con las adiciones que se consideren pertinentes.

El espacio para el marcado de la tipología dentro del `<teiHeader>` se haría con el elemento `<classDecl>`

```xml
<classDecl>
  <taxonomy xml:id="T-CNHDI">
    <bibl>Tipología diplomática CNHID, 2021</bibl>
    <!-- Definir el marcado en función del listado, por ejemplo, un auto acordado de la Audiencia de México -->
      <category = xml:id="auDel-RlProv">
        <category = xml:id="AudMx-AutAcord">
          <catDesc>Auto Acordado de la Audiencia de México</catDesc>
        </category>
      </category>
  </taxonomy>  
</classDecl>
```

## Tipología general

### Emanados de autoridad soberana

* Real provisión
* Real cédula

### Emanados de autoridades delegadas

* Real provisión
  * Real orden
  * Mandamiento
  * Ordenanza
  * Bando
  * Carta acordada (auto acordado)
  * Sentencias
  * Carta  

## Tipología de reales provisiones

* Ordenanzas.
* Títulos para cargos:
  - eclesiásticos: Ejecutoriales de arzobispos y de obispos, dignidades y canonjías.
  - seculares: títulos de virreyes, de gobernador, capitanes o comandantes generales; teniente de rey, sargentos mayores, alcaides, escribanos mayores de gobernación presidentes, de Audiencia, oidores, fiscales, alcaldes de corte, alguacil mayor, escribanos de cámara, receptores de cámara y gastos de justicia, regente, contadores, oficial real (contador tesorero, factor), escribano mayor de minas y registros, del tribunal de cuentas, regidor, alférez mayor, alcalde de hermandad, alguacil mayor, depositario general, corregidor y alcalde mayor, escribano de número y concejo, escribano de provincia, notaría y notario mayor, de corregimientos, superintendente, tesorero y contador, ensayador, fundidor de la casa de la moneda; generales de armada; general de flota; almirante de la flota, capitanes veedores de plazas honorarias y jubilaciones, de pacificador y poblador, de oficios perpetuos.
* Títulos de ciudades.
* Títulos de muy noble, leal, etc. a ciudad o uso de otro renombre.
* Concesión de blasón de_ armas para ciudad o particular.
* Asientos de alcabalas y otras rentas.
* Mercedes a villas y ciudades.
* Cartas de naturaleza.
* Ejecutorias de naturaleza.
* Despachos de merced perpetua.
* Confirmaciones de encomiendas.
* Prorrogación de rentas.
* Facultad vitalicia para nombrar teniente.
* Facultad para fundar mayoraZgo.
* Perdones o indultos.
* Futuras sucesiones.
* Confirmaciones de ventas y composiciones de tierras.
* Facultad a los provistos de gobernadores, corregimientos y alcaldías para que sirvan estos empleos nuevos nominados
* Facultad de poder nombrar a un teniente poseedor perpetuo.
* Legitimación de hijos espurios para heredar.
* Legitimación de hijos bastardos.
* Legitimación de hijos naturales.
* Facultad para hacer probanzas
* Emplazamientos.
* Comisión en grado de segunda súplica.
* Ejecutorías en forma de pleito fenecido.


[^1]: Real Díaz, José Joaquín autor. Estudio diplomático del documento indiano José Joaquín Real Díaz, 1970.
