Payload Design
========================

**Notes**

Obiettivo per il primo PM è ragionare sulla parte di scienza.
Cosa vogliamo fare ? Cosa vogliamo misurare ? Un suggerimento ce lo da il titolo  _"Dark Matter Through distant galaxies observation"_
Sappiamo che per rilevare la presenza della materia oscura dobbiamo osservare delle galassie lontane alla ricerca di due fenomeni:

* osservo Red Shift
* osservo variazioni di luce

Bisogna quindi capire come osservare questi fenomeni, forumulare dunque requisiti alto livello scientifici da cui partire:

* come misurare il Red Shift ?
* come misurare la dark energy ?

Da fare prima, poi posso pensare a quali sono le funzioni e derivare i requisiti per i vari pezzettini. La scelta dell'orbita viene però più in basso : dipende dagli strumenti, saranno loro a dettarci i requisiti orbitali.
Strumenti proposti dal prof sono : _Telescope for Optical + IR + Spectral_
Lo strumento scelto deve poter guardare dove vogliono gli scienziati, pero dal punto di vista dello strumento non è di rilevante importanza.
Come faccio a guardare dappertutto ? E' meglio far girare il satellite per guardare tutto l'universo => questi saranno requirements sullo spacecraft.
Cose su cui concentrarsi per il PM2 : Lunghezza focale, campo di vista, risoluzione, specchi.

Organization
----------------

**What kind of science we want to perform**

* How we can measure the red shift
* How we can observe light variation
* How we can measure gravitational waves
* How we can observe cosmic rays
* We need to observe how dark objects moves

**Phenomena to be observed**

* **[Redshift]** : Red Shift is an effect that is observable when you analyze the spectroscopic signature of an electromagnetic radiation source that is so far removed from us that the expansion of the universe (whose unit of measurement is called the Hubble Constant) is noticeable because of the  frequency drop, called Doppler effect.

* **[Deformation of light due to mass]**:

* **[Weak lensing]**:
* **[Galaxy Clustering]**:

**What we will use to do science**

* Spectro{scope,grapher,meter} Red Shift, doppler galassie, velocita all'interno galassie, immagine galassie stiamo studiando
* Optics for visible
* Optics for infrared
* Particle reveler (WIMPs)
* Dragonfly Telephoto Array

**Top-Level Requirements and Expectations**

* Capabilities

	* Take pictures

		* Voglio osservare ogetti scuri
		* Vedere il gravity lensing (devo essere fermo per poterlo vedere ?)

	* View spectrum

		* Vedere Infrared : alcuni tipi di ogett + gas i presenti nell'universo possono essere visti solo nella banda infrarosso.  => Si usa il telescopio
		* Vedere Visible : serve per valutare la deformazione della luce

* Costraints : 

	* Peso 3Tons
	* Qualità immagine => gravity lensing
	* HEO
	* Operating temperature of the sensors

**Instruments to be used**

> __TELESCOPE__  : The heart of the instrument payload is the telescope, designed to offer diffraction limited performance over a fieldview of 0.5 square degrees.
Serve dunque un gruppo ottico che ci consenta di raccogliere la luce.
Usiamo lenti o specchi ?

* TRADE OFF

	_Lenti_ : alterazione cromatica,
	_Specchi_ :  COMA

> __SPECTROMETER__


**Justifications**

* We want to use the infrared vogliovedere ossigeno, piu facile vedere rispetto a visibile, voglio vedere redshift, è quello classicamente usato di più, nubi assorbono luce. [4]
* Telescopio : voglio osservare gravity lenses

**Who is doing what**


SIMILAR MISSIONS
-------------------------------

__EUCLID__ :  https://www.euclid.caltech.edu/page/about

SHALL STATEMENTS
-------------------------------


CONCEPT DESCRIPTION
-------------------------------------


**[REFERENCES]**

[1]  EUCLID_RB_Issue_1-1_2011-09-29HighQ.pdf

[2]  http://www.media.inaf.it/2016/08/25/dragonfly-44-dark-matter/amp/

[3]  http://www.astro.caltech.edu/~ycao/B&ETalks/vandokkum_bne.pdf

[3]  http://jila.colorado.edu/~pja/astr3830/lecture17.pdf
