### Vacancia de oxígeno como atractor no nuclear en CaTiO<sub>3</sub>
M. en C. Marcos Rivera-Almazo <a href="https://molecular-mar.github.io/"><img src="img/github.png" height=50px></a> <a href="https://www.researchgate.net/profile/Marcos-Rivera-Almazo"><img src="img/rglogo.png" height=50px></a>

Contacto: mralm@xanum.uam.mx

|||
|--|--|
|![logo UAM-I](img/logoUAMIw.svg "logo UAM-I")|<img src="img/logoMSSC.png" height=140px)>|


### Contenido

* Fundamentos de QTAIM
    * Algunos ejemplos
* CaTiO<sub>3</sub> con V<sub>O</sub>
* V<sub>O</sub> como NNA

### Fundamentos de QTAIM

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
    <div class="r-stack">
        <div data-markdown class="fragment fade-out" data-fragment-index="0">

* MFM-300(Sc) and MFM-300(In) components
        
    * Metal center (Sc, In) 
    * Organic ligand (biphenyl-3,3′, 5,5′-tetracarboxylate)     
    * μ<sub>2</sub>-OH bridge

* Isostructural materials 
        </div>    
        <div data-markdown class="fragment current-visible" data-fragment-index="0">

* Experimental studies for the In and Sc variants

    * Larger Benzene (Bz) adsorption in MFM-300(Sc)
    * Formation of polysulfides in presence of H<sub>2</sub>S, with larger chains for In
        </div>

        <div data-markdown class="fragment fade-in">
            <span class="fragment highlight-red">
* No clear reason for this difference in reactivity
            </span>
        </div>

    </div>

    <div style="margin: 3em auto; display: flex; flex-direction: column; max-width: 400px;max-height: 500px; border-radius: 6px; box-shadow: 0 3px 10px rgba(0, 0, 0, 0.25); overflow: hidden">
        <model-viewer bounds="tight" 
 	        enable-pan src="models3D/mfmIn_clear.glb" 
	        camera-controls environment-image="neutral" 
            camera-orbit="0deg 90deg 2m"
        	poster="img/poster.png" 
        	shadow-intensity="0"
		auto-rotate
            interaction-prompt=none>
            <button class="Hotspot" slot="hotspot-3" data-position="-1.8812155300539697m 1.763153750904624m -0.35147077915528335m" data-normal="-0.24508880025691712m 0.26956470714956804m 0.9312713614451982m" data-visibility-attribute="visible">
        <div class="HotspotAnnotationl">OH bridge</div>
    </button><button class="Hotspot" slot="hotspot-5" data-position="-1.3449316072047406m 1.8874519669395287m 1.4285309580878136m" data-normal="0.00479209835895687m 0.5999895154339765m 0.7999935107003183m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Metal</div>
    </button><button class="Hotspot" slot="hotspot-7" data-position="-2.168626637990537m 2.3799385322279996m -2.2336290327512383m" data-normal="-0.5333272400624021m 0.05224716296927647m -0.8442939588609425m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Metal</div>
    </button><button class="Hotspot" slot="hotspot-8" data-position="1.7376060017548984m 1.7298722086145164m -3.6132504585087126m" data-normal="-0.13498223760778588m -0.08320034631379696m -0.9873487215283462m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">OH bridge</div>
    </button><button class="Hotspot" slot="hotspot-9" data-position="2.587617916028829m 1.89976071439453m -0.8030771211442933m" data-normal="0.7815222232380535m 0.6222877345641713m -0.044508313785649636m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Metal</div>
    </button><button class="Hotspot" slot="hotspot-10" data-position="-1.940658580440196m -0.1056368413596831m -1.6605607461386063m" data-normal="-0.8245146437912436m -0.2996659546597841m 0.47997491371074696m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Organic ligand</div>
    </button><button class="Hotspot" slot="hotspot-11" data-position="1.8570928346928899m -0.08434399133416909m -0.26363810285161593m" data-normal="0.8297405486551619m -0.27057997718439103m -0.48817732215284826m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Organic ligand</div>
    </button>
        </model-viewer>
    </div>
</div>
---

### Searching for differences

<div class="r-stack">
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

---

### Conclusions

* MFM-300(Sc) has a tighter structure, given the non-covalent interactions predicted. More ordered material. 
* MFM-300(In) OH groups tend to modify its direction on the influence of an adsorbed Bz. 
* Because of that it has a lower adsorption capacity. 
* Given a [proposed](https://pubs.acs.org/doi/10.1021/acs.chemmater.1c01918) reaction mechanism, this may explain the formation of larger polysulfides. 

---
### Published [article](https://pubs.acs.org/doi/10.1021/acs.jpcc.2c00742):  
Rivera-Almazo, Marcos, *et al*, Isostructural MFM-300(Sc) and MFM-300(In):  
Adsorption Behavior to Determine Their Differences, The Journal of Physical  
Chemistry C **2022** 126 (14), 6465-6471

<img src="img/rivera2022G.png" height=250px>


## Thank you for you attention!

QR for this presentation:
<img src="img/qrGit.png" height=200px>
