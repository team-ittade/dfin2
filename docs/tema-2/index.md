# Tema 2 - La estructura de financiación I

## 1. La estructura financiera de la empresa

Es el conjunto de decisiones relativas a la obtención de recursos

Tipos:

- **Según la propiedad:** ^^propios^^ (*capital social, reservas, autofinanciación...*) o ^^ajenos^^ (*créditos, préstamos, proveedores, obligaciones, leasing...*)
- **Según el periodo:** ^^permanentes^^ o ^^corrientes^^
- **Según el origen:** ^^externos^^ (*capital social, obligaciones, préstamos...*) o ^^internos^^ (*beneficios retenidos, venta de activos, proveedores...*)

||Propios|Ajenos|Internos|Externos|Permanentes|Corrientes|
|--|:--:|:--:|:--:|:--:|:--:|:--:|
|Póliza de crédito||:octicons-x-16:||:octicons-x-16:|:octicons-x-16:|:octicons-x-16:|
|Beneficio retenido|:octicons-x-16:||:octicons-x-16:||:octicons-x-16:||
|Ampliación de capital|:octicons-x-16:|||:octicons-x-16:|:octicons-x-16:||
|Proveedores||:octicons-x-16:|:octicons-x-16:|||:octicons-x-16:|
|Leasing||:octicons-x-16:||:octicons-x-16:|:octicons-x-16:||
|Obligaciones convertidas en acciones||:octicons-x-16:||:octicons-x-16:|:octicons-x-16:||
|Venta de activos|:octicons-x-16:||:octicons-x-16:||:octicons-x-16:||

![img](../images/tema-2/fondo-de-rotacion.png)

- La estructura económica es todo lo relativo al activo.
- La **estructura financiera** es todo lo relativo a cuestiones del pasivo, de la financiación.

Fondo de rotación = Fondo de maniobra = PN - AC = AC - PC = PF - AF

**TODO: contrastar fórmula de arriba. Viene de Nadia.**
{.red}

![img](../images/tema-2/estructura-financiera.png)

- **V:** valor de la empresa
- **BAII/BAIT:** beneficio antes de intereses e impuestos. Beneficio bruto, generado por los proyectos de inversión.
- **BDII:** beneficio después de intereses e impuestos. Beneficio neto.
- **EBITDA:** Beneficio - ITDA = EBITDA
    - Intereses
    - Tax - Impuestos
    - Depreciaciones
    - Amortizaciones
- **r:** intereses

$V=S+D$

$BAII=BDII+r_d→BDII=BN=BAII-r_d$

## 2. Riesgo y apalancamiento

Apalancamiento financiero: todo lo referido a la utilización de deuda. Cuanta más deuda tenga la empresa, más apalancada estará.

![img](../images/tema-2/riesgo-y-apalancamiento.png)

- ROA: *Return on Assets*. Es la **rentabilidad económica** o **coste de capital (k~T~)**.
- BN: *Beneficio neto*. $BN=BAII-rD$

$k_s=k_T+\dfrac{D}{S}(k_T-r)$

$ROE=ROA+\dfrac{D}{S}(ROA-r)$

??? info "Demostración"
    ![img](../images/tema-2/demostracion-riesgo-apalancamiento.png)

Si no hay deuda:

- $k_S=k_T$
- $ROE=ROA$

Resumen:

- **ROA:** mide la ^^eficiencia de los activos totales de una empresa independientemente de las fuentes de financiación utilizadas y de la carga fiscal^^ (los impuestos se dan en el `tema 3`). ^^Mide la capacidad de los activos de una empresa para generar renta^^.
- *ROE:* mide el ^^rendimiento que obtienen los accionistas de los fondos invertidos en la empresa^^. Trata de captar la capacidad de la empresa para remunerar a sus accionistas. Se utiliza para comparar empresas del mismo sector. Se pueden comparar empresas de distinto sector, pero la fiabilidad es mucho menor que si las empresas son del mismo sector.

??? example "Ejemplo: nueva empresa que tiene que decidir si financiar proyecto de 100 um"
    - A) todo con fondos propios → ROE = ROA
    - B) 10% con fondos propios, 90% de préstamo

    ![img](../images/tema-2/ejemplo-roe-roa.png)

    En el caso `B` los accionistas reclaman más dinero porque la empresa tiene más apalancamiento (**más riesgo**). Recordar que los accionistas son los últimos en cobrar.

Recordar: `Coste capitales propios = Coste del capital + Prima por riesgo`

??? note "De qué depende la rentabilidad que reciben los accionistas?"
    - :fontawesome-solid-caret-up:{.green} Nivel de endeudamiento
    - :fontawesome-solid-caret-up:{.green} Rentabilidad de la empresa
    - :fontawesome-solid-caret-down:{.red} Tipo de interés

### Coste de Capital Medio Ponderado (ccmp)

$ccmp=k_T=\dfrac{S}{S+D}k_S+\dfrac{D}{S+D}k_D$

k~T~ es una media ponderada del coste de capital propio (k~S~) y el coste del capital ajeno (k~D~)

Ahora vemos el riesgo:

- $\sigma(k_S)=\sigma(k_T)+\dfrac{D}{S}\sigma(k_T)=\sigma(k_T)(1+\dfrac{D}{S})\geq \sigma(k_T)$
- Riesgo financiero = Riesgo económico + Riesgo financiero propiamente dicho
    - El `riesgo económico` no depende del endeudamiento
    - El `riesgo financiero` depende del endeudamiento

??? info "Demostraciones (no caen)"
    ccmp:
    ![img](../images/tema-2/demostracion-ccmp.png)

    riesgo:
    ![img](../images/tema-2/demostracion-riesgo.png)

## 3. La posición tradicional

## 4. Estructura de capital en mercados perfectos: las proposiciones de medigliani y miller
