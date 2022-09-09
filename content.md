### Exploring the differences between isostructural MOFs MFM-300(Sc) and MFM-300(In) using computational methods

Marcos Rivera-Almazo

Supervisor: Jorge Garza Olguín

|||
|--|--|
|![logo UAM-I](img/logoUAMIw.svg "logo UAM-I")|<img src="img/logoMSSC.png" height=140px)>|


### Why this pair of MOFs?

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
    <div class="r-stack">
        <div data-markdown class="fragment fade-out" data-fragment-index="0">

* MOFs and MFM-300 family components
        
    * Metal center (Sc, In, Cr, Al,...) 
    * Organic ligand (biphenyl-3,3′, 5,5′-tetracarboxylate)     
    * μ<sub>2</sub>-OH bridge 
        </div>    
        <div data-markdown class="fragment current-visible" data-fragment-index="0">

* Experimental studies for the In and Sc variants
    * Larger Benzene (Bz) adsorption
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
            camera-orbit="0deg 75deg 2m"
        	poster="img/poster.png" 
        	shadow-intensity="0">
            <button class="Hotspot" slot="hotspot-2" data-position="-0.016136788012466652m 1.8188077688410695m -1.1092772696304694m" data-normal="0.3877984063151501m 0.6208699364220553m 0.6812730129006306m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Organic ligand
        </div>
    </button><button class="Hotspot" slot="hotspot-5" data-position="1.7840894715853053m 1.7677043049728423m 0.6518118625453408m" data-normal="0.48160193641876264m 0.27766315751633935m 0.8312416891589081m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">OH bridge</div>
    </button><button class="Hotspot" slot="hotspot-7" data-position="-1.374190778253282m 1.964442284089202m 1.3709640283087712m" data-normal="0.00479209835895687m 0.5999895154339765m 0.7999935107003183m" data-visibility-attribute="visible">
        <div class="HotspotAnnotation">Metal</div>
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

Published article [link](https://pubs.acs.org/doi/10.1021/acs.jpcc.2c00742):
<img src="img/rivera2022G.png" height=150px>


## Thank you for you attention!

QR for this presentation:
<img src="img/qrGit.png" height=200px>


