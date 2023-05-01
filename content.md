### Vacancia de oxígeno como atractor no nuclear en CaTiO<sub>3</sub>
M. en C. Marcos Rivera-Almazo <a href="https://molecular-mar.github.io/"><img src="img/github.png" height=50px></a> <a href="https://www.researchgate.net/profile/Marcos-Rivera-Almazo"><img src="img/rglogo.png" height=50px></a><br>
Asesor: Prof. Jorge Garza Olguín

Contacto: mralm@xanum.uam.mx

||||
|--|--|--|
|![logo UAM-I](img/logoUAMIw.svg "logo UAM-I")|<img src="img/DES2023newT.png" height=140px)>|<img src="img/logoVGGbn2.png" height=140px)>|


### Versión interactiva

<img src="img/DES2023QR.png" height=200px><br>
https://molecular-mar.github.io/DES2023


## Contenido

* ### Fundamentos de QTAIM
* ### CaTiO<sub>3</sub> con V<sub>O</sub>
* ### Metodología
* ### Resultados
* ### Conclusiones

---

### Fundamentos de QTAIM

* Teoría Cuántica de Átomos en Moléculas: describir la estructura atómica de un sistema (finito o periódico). 
* Análisis topológico de la densidad electrónica `$\rho(r)$`
<span class="attribution">Bader, R. F. W. Atoms in Molecules: A Quantum Theory; Oxford University Press: Oxford, UK, 1990.</span>

<!-- <div class="container-fluid" style="margin-top:40px">                            -->
<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div class="column">                           
        <img src="img/lasawas.png">
</div>
<div class="column">                           
<iframe src="waterRho.html" height="300px"></iframe>                                                 
</div>
</div>


* Puntos críticos `$\rightarrow$` interpretación estructural
* Clasificación basada en la matriz Hessiana:

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div data-markdown class="column" style: "vertical-align: middle;">

|Firma|Objeto|
|--|--|
|(3,-3)|Atractor *nuclear/no nuclear* (NA/NNA)|
|(3,-1)|Enlace (BCP)|
|(3,+1)|Anillo|
|(3,+3)|Caja|

</div>
<div class="column">
 <img src="img/cubano.gif" height="330px">
</div>
</div>

* (# eigenvalores `$\neq$` 0, `$\sum sign$` eigenvalores) 


* Ruta de enlace (BP): Trayectoria `$\nabla \rho$` que une (3,-1) a dos (3,-3). 

* NA + BCP + BP = Grafo molecular

<img src="img/cubanoBp.png" height="330px">



### Ejemplo: interacción Benceno-MOF
<!-- |||
|--|--|
|<img src="img/aimSc.png" height=330px> |<model-viewer bounds="tight" enable-pan src="mfmIn_bpath_New.glb" ar ar-modes="webxr scene-viewer quick-look" camera-controls environment-image="neutral" camera-orbit="0deg 90deg 2m" poster="img/poster.png" shadow-intensity="0" auto-rotate interaction-prompt=none></model-viewer>| -->

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div data-markdown class="column" style: "vertical-align: middle;">
<img src="img/aimSc.png" height=330px>
</div>
<div style="margin: 3em auto; display: flex; flex-direction: column; max-width: 400px;max-height: 330px; border-radius: 6px; box-shadow: 0 3px 10px rgba(0, 0, 0, 0.25); overflow: hidden">
        <model-viewer bounds="tight" 
 	        enable-pan src="models3D/mfmIn_bpath_New.glb"
	        camera-controls environment-image="neutral" 
            camera-orbit="-4.9deg 86.11deg 6.512m" field-of-view="25.77deg"
        	poster="img/poster.png" 
        	shadow-intensity="0" auto-rotate
            interaction-prompt=none>
        </model-viewer>
    </div>
</div>

<span class="attribution">Rivera-Almazo, M. et al. Isostructural MFM-300(Sc) and MFM-300(In): Adsorption Behavior to Determine Their Differences. J. Phys. Chem. C 300, (2022).</span>

---

### CaTiO<sub>3</sub> con V<sub>O</sub>

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">

<div data-markdown class="column">

* Grupo espacial `$Pnma$`
* Estudio experimental, dopado con Yb`$^{+3}$`
* Excitación a 2.98 eV  <br>(`$E_g=3.85$`)
* Posible influencia de defectos  <br>(¿V`$_O$`?)

<span class="attribution"> I. Padilla-Rosales, I. et al. Near infrared photon-downshifting in Yb3+-doped titanates: The influence of intrinsic defects, Journal of Alloys and Compounds 834,
155081 (2020).</span>

</div>
<div class="column">
<img src="img/catio3Ori.gif" height=400px)> 
</div>
</div>

---

### Metodología

<div class="r-stack">
    <div data-markdown class="fragment fade-out">

* Cálculos *ab initio* usando ***CRYSTAL14***. 
* Optimización completa de geometría.
* Base POB-TZVP. Funcional XC híbrido PBE0-`$\alpha_{adj}$`
* Sistema prístino, celda unitaria típica.
    * PBE0(25) y PBE0-20 ajuste. `$\alpha_{adj}$=17.33`
    * Muestreo puntos k Monkhorst-Pack 12x12x12 
<br>
<span class="attribution">Dovesi, R. et al. CRYSTAL14 : A program for the ab initio investigation of crystalline solids. Int. J. Quantum Chem. 114, 1287–1317 (2014).</span> 

</div>
    <div data-markdown class="fragment fade-in-then-out">

* Sistema con V`$_O$`:
    * Supercelda 16 unidades formula`$\rightarrow$` CaTiO`$_{2.937}$`-vO`$_{0.063}$`
    * Dos átomos no equivalentes (**O`$_{ap}$`** y O`$_{eq}$`)
    * Muestreo puntos k Monkhorst-Pack 3x3x3
    * Estado triplete (`$n_\alpha-n\beta=2$`)

<span class="attribution">Maul, J. et al. A quantum-mechanical investigation of oxygen vacancies and copper doping in the orthorhombic CaSnO3 perovskite. Phys. Chem. Chem. Phys. 20, 20970–20980 (2018).</span>

</div>
    <div data-markdown class="fragment fade-in-then-out">

* Análisis de `$\rho(r)$`
    * TOPOND (CRYSTAL14)
    * Módulo Cube3D de GPUAM

<span class="attribution">Hernández-Esparza, R. et al. GPUs as Boosters to Analyze Scalar and Vector Fields in Quantum Chemistry. Int. J. Quantum Chem., 119,1−9 (2019).</span>

</div>
</div>
---

### Resultados

* Diferencia triplete-singulete: \[0.05-0.08\] eV (triplete más estable)
* Aumento en el volumen respecto a pristino: \[0.1-0.3\]\%
* Resultados para V`$_O^{ap}$` triplete.

<img src="img/catio3_tripO1.png" height=400px)> 



#### Bandas/DOS

* Aparición de estados `$\alpha$`.<br>
<img src="img/dossO1T.png" height=500px)> 


#### Valores de Gaps

|Modelo | `$E_g^{dir}$` | `$E_g^{ind}$` | `$E_g'$` |  `$E_g''$`|
|--|--|--|--|--|
| V`$_O^{ap}$` singulete | 0.57 | 0.49 | 3.37 | -|
| V`$_O^{ap}$` triplete | 0.67 | 0.53 | 2.82 | 0.46|
| V`$_O^{eq}$` singulete | 0.60 | 0.51 | 3.36 |-|
| V`$_O^{eq}$` triplete | 0.60 | 0.44 | 2.80 |0.50|

* `$E_g'$` es cercano al valor observado para la excitación de Yb`$^{+3}$` en CaTiO`$_3$`



#### Densidad electrónica

* Densidad electrónica en plano Ti-V`$_O$`-Ti
* Pristino (izq.) y V`$_O$` (der).

<img src="img/rhoOriYO1T.png" height=350px)> 

* Diferencia clara en la forma de los Ti.


<img src="img/rho_newT.png" height=350px)> 
<img src="img/rhoCaAr_newT.png" height=350px)>  
 
* Planos Ti-V`$_O$`-Ti (izq.)  y Ca-V`$_O$`-Ca (der.).
* Observamos una región *anillo*, seguida de la región del atractor.


<img src="img/rho_newV.png" height=250px)> 
<img src="img/rhoCaAr_newV.png" height=250px)> 

* Planos Ti-V`$_O$`-Ti (izq.)  y Ca-V`$_O$`-Ca (der.).
* Observamos una región *anillo*, seguida de la región del atractor.


<img src="img/lap_ori2.png" height=350px)> 
<img src="img/lap_newT.png" height=350px)> 

* `$\nabla^2 \rho$`. Pristino (izq.) y V`$_O$` en plano Ti-V`$_O$`-Ti (der.) 
* Aparición de una capa donde se concentra `$\rho$`.


<img src="img/lap_newT.png" height=350px)> 
<img src="img/lapCaAr_newT.png" height=350px)> 

* `$\nabla^2 \rho$`. Plano Ti-V`$_O$`-Ti (izq.) y Ca-V`$_O$`-Ca (der.)


|Modelo | `$\rho_{crit}$` | `$\nabla^2 \rho_{crit}$` | q (Mulliken)|
|--|--|--|--|
|V`$_O^{ap}$` singulete | 0.032 | -119.47 | 0.89 |
|V`$_O^{ap}$` triplete | 0.021 | -69.71 | 0.69 (0.54 `$\alpha$`) |
|V`$_O^{eq}$` singulete | 0.031 | -118.01 | 0.89 |
|V`$_O^{eq}$` triplete | 0.021 | -69.42 | 0.68 (0.54 `$\alpha$`)|


### Rutas de enlace

<img src="img/cavO1T_1.png" height=400px)> 

* Rutas de enlace Ti-Ti y Ti-Ca, influenciadas por V`$_O$`.


* Propiedades de los CP:

|BCP|`$\rho_{crit}$`|`$\nabla^2 \rho_{crit}$`| `$\epsilon$` |
|--|--|--|--|
|Ti-Ti| 0.0145| -0.0180| 4.0908|
|Ti-Ca| 0.0115| 0.0032| 1.7748|

* `$\epsilon = \lambda_1 / \lambda_2 - 1 $`. Desviación de la distribución circular de `$\rho$` en plano perpendicular al BP. 

---

<!-- <div class="r-stack">
    <div data-markdown class="fragment fade-out">

> Periodic *ab initio* calculations were performed, using the code ***Crystal***, looking up for differences between each system alone and with a Bz molecule. 

<img src="img/cry.png" height=140px)>
    </div>    
    <div data-markdown class="fragment fade-in-then-out">

|||
|--|--|
|MFM-300(Sc)|MFM-300(In)|

What we found:
    </div>    
    <div data-markdown class="fragment fade-in-then-out">

|||
|--|--|
|<img src="img/diffRhoScOMO.png" height=280px> |<img src="img/diffRhoInOMO.png" height=280px>|

* Electronic density differences between the bulk system and a reference isolated atoms model show differences in the distribution of the electronic density, primarily around the oxygen from μ<sub>2</sub>-OH

    </div>    
    <div data-markdown class="fragment fade-in-then-out">
    
    
|||
|--|--|
|<img src="img/nciSc32.png" height=330px> |<img src="img/nciIn32.png" height=330px>|
        
* NCI analysis shows different nature of non-covalent interactions around a M-O(H)-M-O-C-O ring, which could indicate a higher strain for the In system.
    </div>    
    <div data-markdown class="fragment fade-in-then-out">

|||
|--|--|
|<img src="img/aimSc.png" height=330px> |<img src="img/aimIn.png" height=330px>|

* AIM study with Bz shows that in the In system the Bz molecule has an additional interaction with a second μ<sub>2</sub>-OH
    </div>    
    <div data-markdown class="fragment fade-in">

|||
|--|--|
|<img src="img/voidSc1.png" height=300px> |<img src="img/voidIn1.png" height=300px>|

* Void analysis shows posible second Bz adsorption sites. μ<sub>2</sub>-OHs in the In system are less directed to the pore, therefore less available for new interactions.
    </div>
</div>

-->

---

### Conclusiones

* La inclusión de V`$_O$` conlleva la aparición de estados. El Gap Valencia-Estado V`$_O$` es cercano con el encontrado para CaTiO`$^3$` + Yb`$^{+3}$`.
* En el sitio de V`$_O$` aparece un NNA, afectando el comportamiento general de `$\rho(r)$` en dicha vecindad. Este cambio lo asociamos a la aparición de las bandas adicionales.
* El comportamiento de `$\rho$` alrededor de V`$_O$`, con un *anillo* de densidad alrededor del atractor, no parece estar previamente reportado.
* Obtenemos una interacción Ti-Ti, además de una interacción Ti-Ca. No encontramos interacciones con V`$_O$`.
<!-- Given a [proposed](https://pubs.acs.org/doi/10.1021/acs.chemmater.1c01918) reaction mechanism, this may explain the formation of larger polysulfides.  -->

---
<!-- ### Published [article](https://pubs.acs.org/doi/10.1021/acs.jpcc.2c00742):   -->
<!-- Rivera-Almazo, Marcos, *et al*, Isostructural MFM-300(Sc) and MFM-300(In):   -->
<!-- Adsorption Behavior to Determine Their Differences, The Journal of Physical   -->
<!-- Chemistry C **2022** 126 (14), 6465-6471 -->

<!-- <img src="img/rivera2022G.png" height=250px>  -->


## Gracias por su atención

QR a esta presentación:
<img src="img/DES2023QR.png" height=200px>
