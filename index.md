<style type="text/css">
img[alt="minipic"] { 
  max-width:  120px; 
  float: left;
  padding-right: 15px;
}
img[alt="centrar"] { 
  align: center;
}
</style>

# Principis d'arquitectura d'entorn de treball

<img src="https://cburgales.github.io/CTTI/ET.JPG" alt="centrar" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="23,300,185,330" alt="Sun" href="#ArquitecturaTELCO">
  <area shape="rect" coords="190,300,371,330" alt="Sun" href="#ArquitecturaTELCO">
  <area shape="rect" coords="375,300,575,330" alt="Sun" href="#arqtelco">
</map>

<details>
 <summary>Index dels Principis</summary>

+ **[Solucions LldT](#arqtelco)**
    + nested list 1
    + nested list 2
    
+ **[Arquitectura LldT](#arqtelco)**

+ **[Arquitectura Telco](#arqtelco)**
    + [Principis de disseny](#Principisdissenytelco)
    + [Principis tecnologics](#Principistecnotelco)
    + [Principis de cost i manteniment](#Principiscosttelco)

</details>


---
![minipic](https://cburgales.github.io/CTTI/Conect_2.jpg)

### <a id="arqtelco"> Arquitectura TELCO </a>
*Els principis d’arquitectura CTTI són les normes i directrius generals destinades a ser perdurables i rarament modificables i tenen com a objectiu informar i recolzar la forma en què CTTI vol que s’implementin les xarxes de telecomunicacions.*

---

#### <a id="Principisdissenytelco"> Principis de disseny </a>

* **Adaptabilitat**. Capacitat per acollir noves funcionalitats i/o tecnologies minimitzant els canvis estructurals i els costos d'implementació.

* **Escalabilitat**. Totes les solucions de xarxes de telecomunicacions han de suportar sense dificultats el creixement, moltes vegades continu, i sense que es tingui que redissenyar novament la solució. 

* **Disponibilitat**. S’ha d’establir el grau de disponibilitat per tota solució de xarxa de telecomunicacions. Aquest valor es mesurarà com el percentatge de temps de disponibilitat de la xarxa durant un temps indicat, o també es podrà valorar com el temps màxim permès que pugui estar caiguda la xarxa sense afectar als serveis principals de l’empresa. 

* **Rendiment**. Per tota solució de xarxes de telecomunicacions cal determinar les càrregues de treball màximes, per tal de poder-les absorbir. Els paràmetres fonamentals a tenir en compte pel correcte funcionament dels serveis dintre de la xarxa (Telefonia IP, Videoconferència, Correu Electrònic, Etc...) són l’amplada de banda (Bandwidth), la pèrdua de paquets (Packet loss), el retard (Latency) i la variació de retard (Jitter). 

* **Administració**. Tota xarxa de telecomunicacions haurà de permetre de forma senzilla la seva administració, monitorització, control d'esdeveniment i incidències, amb enfocament cap una gestió automatitzada. 

* **Automatització**. Tant la provisió com el manteniment de la xarxa de telecomunicacions haurà d’orientar-se cap a la màxima automatització dels seus processos.

* **Seguretat**. Tota xarxa de telecomunicacions haurà d’establir un nivell de seguretat mínim que permeti aplicar els següents punts:

  * **Traçabilitat**. Capacitat per identificar l’origen i les diferents etapes d’una connexió de xarxa.
  * **Control d’accés**. Capacitat per limitar l’accés a la xarxa.
  * **Auditoria**. Capacitat per enregistrar tots els accessos realitzats.

* **Simplicitat**. Tot disseny està orientat a la senzillesa, evitant sempre desenvolupar solucions complicades, que acabin sent posteriorment ingovernables. 

* **Provat**. Totes les noves solucions han de ser provades en un laboratori, per tal de revisar-les més enllà de la simulació i poder fer els ajustos necessaris. Obtenint així evidències de les proves efectuades, i conseqüentment del funcionament de la solució.


#### <a id="Principistecnotelco"> Principis tecnologics </a>

* **Estabilitat**. Les solucions a aplicar en les xarxes de telecomunicacions haurien de ser solucions amb un cert recorregut, no es recomanable utilitzar solucions poc madures a nivell de producció. Encara que, en certes situacions s’avaluara implementar solucions emergents.

* **Evolució**. Monitoritzar la xarxa i els seus components per a identificar les necessitats de creixement o de canvi dels equipaments de xarxa, per tal de acollir les previsions e creixement, noves necessitats i/o la obsolescència tecnològica.

* **Minimitzar la dependència sobre els fabricants**. Cal evitar sempre que sigui possible les solucions propietàries, i maximitzar la compatibilitat amb la resta dels components i sistemes. Però, allunyant-nos de solucions massa heterogènies que puguin generar problemes de governança. 


####  <a id="Principiscosttelco"> Principis de cost i manteniment </a>

* **Arquitectura mínima**. Cal tenir sempre en compte l’escalabilitat de la xarxa, i caldrà minimitzar al màxim el marge de creixement del disseny. Basat en el principi de la automatització s’aconsegueix una reducció dels costos i temps dels processos d’instal·lació i manteniment, i una arquitectura sostenible en el temps, que doni una bona rendibilitat. 
 
* **Benefici màxim al menor cost i risc possible**. La solució de xarxa de telecomunicacions no només haurà d’aconseguir recollir unes especificacions tècniques, també haurà de valorar la rendibilitat tant del disseny com de la seva implementació, evitant sempre duplicitats en els serveis de xarxa. D’aquesta manera, haurà de prendre un enfoc per tal d’abaratir els costos, mentre es garanteixen els requeriments de la solució.

* **Impacte d’actualització**. Cal pensar en l’impacte que pugui generar una actualització a nivell de software, o equipament hardware de la xarxa de telecomunicacions. Cal sempre valorar quins seran els possibles canvis dintre de la xarxa, quins riscos i millores aportarà.

</br></br>

