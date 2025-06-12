# Unitat de Treball: Explotació de Vulnerabilitats Web amb DockerLabs

## Introducció

Aquest projecte pràctic està dissenyat per a desenvolupar les competències en l'àrea de seguretat web, específicament en la identificació i explotació de vulnerabilitats comunes en aplicacions web. Utilitzarem màquines de DockerLabs ja que es configuren de manera molt fàcil i podem escollir-en de diferents nivells.

- [Enllaç al vídeo de presentació](https://mega.nz/file/rZlAERjY#152uP-zS7pTC0hbPaZB7aO6_puij633u4pW-jpMuctk)

## 1. Contextualització i Elements curriculars

### 1.1 Ubicació en el Pla d'Estudis

Aquesta Unitat de Treball s'emmarca dins del mòdul de **Hàcking Ètic** en el curs d'especialització de **Ciberseguretat en Entorn de les Tecnologies de la Informació**, relacionat amb **l'explotació de vulnerabilitats**. Es vincula amb el **Resultat d'Aprenentatge 5**.

### 1.2 Competències

  - Anàlisi de vulnerabilitats
  - Explotació controlada
  - Documentació tècnica

### 1.3 Continguts

**Determinació de ferramentes de monitoratge i proves d’intrusió:**

- Hacking ètic i fases
- Caixa negra vs caixa blanca
- Documentació de vulnerabilitats
- ClearNet, Deep Web, Dark Web

**Atac i defensa a aplicacions web:**

- Negació de credencials
- Proxies d’intercepció
- Selenium, Burp, ZAP
- Explotació de vulnerabilitats

### 1.4 - Taula de Resultats d'aprenentatge - Criteris d'avaluació - Percentatges

<table style="width:100%; border-collapse: collapse; text-align:center ">
  <thead>
    <tr style="background-color:#111; color:#fff; ">
      <th style="padding:10px; border:1px solid #ccc; vertical-align: middle; text-align:center">Resultat d'aprenentatge</th>
      <th style="padding:10px; border:1px solid #ccc; vertical-align: middle; text-align:center">Criteri d'avaluació</th>
    <th style="padding:10px; border:1px solid #ccc; vertical-align: middle; text-align:center">Percentatges</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center" rowspan="6">RA5: Ataca i defensa en entorns de prova, aplicacions web aconseguint accés a dades o funcionalitats no autoritzades.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center">a) S'han identificat els distints sistemes d'autenticació web, destacant les seues debilitats i fortaleses.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center"> 16.66 %</td>

    </tr>
    <tr>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center">b) S’ha realitzat un inventari d’equips, protocols, serveis i sistemes operatius que proporcionen el servei d’una aplicació web.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center"> 16.66 %</td>

    </tr>
    <tr>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center">c) S’ha analitzat el flux de les interaccions realitzades entre el navegador i l’aplicació web durant el seu ús normal.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center"> 16.66 %</td>
    </tr>

    <tr>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center">d) S’han examinat manualment aplicacions web a la recerca de les vulnerabilitats més habituals.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center"> 16.66 %</td>
    </tr>
        <tr>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center">e) S’han utilitzat ferramentes de cerca i explotació de vulnerabilitats web.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center"> 16.66 %</td>
    </tr>
    <tr>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center">f) S’ha realitzat la cerca i explotació de vulnerabilitats web mitjançant ferramentes de programari.</td>
        <td style="padding:8px; border:1px solid #ccc; vertical-align: middle; text-align:center"> 16.66 %</td>
    </tr>

  </tbody>
</table>

---

## 2. Objectius i Motivació

### 2.1 Objectius Generals

- Desenvolupar competències pràctiques en seguretat web
- Comprendre el cicle d’una prova de penetració
- Aplicar coneixements teòrics en un entorn controlat

### 2.2 Motivació

- Aproximació a problemes reals
- Entorn segur per a practicar
- Competències demandades al mercat

---


## 3. Planificació temporal

Cada sessió tindrà una duració de 2 hores.

### 3.1 Fases

1. **Preparació (3 sessions)** – Configuració, entorn i eines
2. **Desenvolupament (6 sessions)** – Reconeixement, anàlisi, explotació
3. **Presentació (1 sessió)** – Presentació

### 3.2 Desenvolupament de les sessions

- **Sessió 1 - Preparació:** En esta primera sessió es farà la introducció a Docker i la instal·lació. No s'entrarà en molt de detall sobre Docker avançat. L'alumnat que haja cursat cicles superiors com DAW o DAM haurien de tindre coneixements més tirant cap a avançats que a bàsics i l'alumnat que vinga d'altres estudis és possible que no tinga tants coneixements. Per a esta Unitat de Treball no es requereix tindre coneixements avançats. 

- **Sessió 2 - Preparació:** En esta segona sessió es farà la introducció al pentesting d'aplicacions web i a les tecnologies més famoses (Nmap, Burp Suite, etc). També es voran les vulnerabilitats més famoses i es mostraran exemples.

- **Sessió 3 - Preparació:** En esta tercera sessió es seguirà amb les classes teòriques del pentesting en aplicacions web i les tecnologies i eines més utiltizades i imprescindibles.

- **Sessions 4, 5, 6, 7, 8 i 9 - Desenvolupament:** Estes sessions seran al 100% pràctiques i l'alumnat haurà d'intentar vulnerar les 4 màquines i redactar i reportar tot el que vagen fent.

- **Sessió 10 - Presentació:** En esta sessió l'alumnat haurà de mostrar a la resta de la classe, fent una xicoteta presentació, tot el que han fet en les sessions de desenvolupament. Es presentarà el report que han fet.

---

## 4. Eines i Tecnologies

### Eines recomanades i alternatives

<table style="width:100%; border-collapse: collapse; text-align:left;">
  <thead>
    <tr style="background-color:#444; color:#fff;">
      <th style="padding:10px; border:1px solid #ccc;">Eina</th>
      <th style="padding:10px; border:1px solid #ccc;">Funció</th>
      <th style="padding:10px; border:1px solid #ccc;">Categoria</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.kernel.org/doc/html/latest/" target="_blank">Linux</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Sistema operatiu base</td>
      <td style="padding:8px; border:1px solid #ccc;">Infraestructura</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://docs.docker.com/" target="_blank">Docker</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Contenidors per a laboratoris</td>
      <td style="padding:8px; border:1px solid #ccc;">Infraestructura</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://dockerlabs.es/" target="_blank">DockerLabs</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Laboratoris vulnerables</td>
      <td style="padding:8px; border:1px solid #ccc;">Entorn</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://nmap.org/book/man.html" target="_blank">Nmap</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Escaneig de ports i serveis</td>
      <td style="padding:8px; border:1px solid #ccc;">Reconeixement</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://github.com/laramies/theHarvester" target="_blank">theHarvester</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Recollida d'informació pública</td>
      <td style="padding:8px; border:1px solid #ccc;">OSINT</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://github.com/owasp-amass/amass" target="_blank">Amass</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Enumeració DNS i subdominis</td>
      <td style="padding:8px; border:1px solid #ccc;">OSINT</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://docs.tenable.com/nessus/" target="_blank">Nessus</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Escaneig de vulnerabilitats</td>
      <td style="padding:8px; border:1px solid #ccc;">Anàlisi</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.openvas.org/" target="_blank">OpenVAS</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Escaneig de vulnerabilitats</td>
      <td style="padding:8px; border:1px solid #ccc;">Anàlisi</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://cirt.net/Nikto2" target="_blank">Nikto</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Escaneig de servidors web</td>
      <td style="padding:8px; border:1px solid #ccc;">Web</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.zaproxy.org/docs/" target="_blank">OWASP ZAP</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Test d'aplicacions web</td>
      <td style="padding:8px; border:1px solid #ccc;">Web</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.metasploit.com/" target="_blank">Metasploit Framework</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Explotació i post-explotació</td>
      <td style="padding:8px; border:1px solid #ccc;">Explotació</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://sqlmap.org/" target="_blank">SQLMap</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Detecció d'injecció SQL</td>
      <td style="padding:8px; border:1px solid #ccc;">Explotació</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.openwall.com/john/" target="_blank">John the Ripper</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Crackejat de contrasenyes</td>
      <td style="padding:8px; border:1px solid #ccc;">Post-explotació</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://beefproject.com/" target="_blank">BeEF</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Explotació de navegadors</td>
      <td style="padding:8px; border:1px solid #ccc;">Client-side</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.exploit-db.com/" target="_blank">ExploitDB</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Base de dades d'exploits</td>
      <td style="padding:8px; border:1px solid #ccc;">Recerca</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS" target="_blank">LinPEAS</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Enumeració de privilegis Linux</td>
      <td style="padding:8px; border:1px solid #ccc;">Post-explotació</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://bloodhound.readthedocs.io/" target="_blank">BloodHound</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Anàlisi d'Active Directory</td>
      <td style="padding:8px; border:1px solid #ccc;">Post-explotació</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://dradisframework.com/" target="_blank">Dradis</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Gestió de resultats</td>
      <td style="padding:8px; border:1px solid #ccc;">Reportatge</td>
    </tr>
    <tr>
      <td style="padding:8px; border:1px solid #ccc;"><a href="https://www.faradaysec.com/" target="_blank">Faraday</a></td>
      <td style="padding:8px; border:1px solid #ccc;">Plataforma de pentesting</td>
      <td style="padding:8px; border:1px solid #ccc;">Reportatge</td>
    </tr>
  </tbody>
</table>

---

## 5. Indicacions Específiques

### Per a l’alumnat

- Documentar tot el procés
- Seguir la metodologia
- Participació activa

### Per al professorat

- Supervisió constant
- Adaptació del ritme
- Feedback continuat

---

## 6. Avaluació

El pes de l'avaluació d'esta Unitat de Treball es dividirà en un 25% per a cada màquina. Dins de cada màquina es puntuarà un 60% el document (report) i un 40% la vulneració a la màquina. En l'apartat d'avaluació hi ha més informació amb rúbriques.
<table>
    <tr>
        <th>Màquina</th>
        <th>Ponderació Total</th>
        <th>Report (60%)</th>
        <th>Vulneració (40%)</th>
    </tr>
    <tr>
        <td>Màquina Injection</td>
        <td>25%</td>
        <td>15%</td>
        <td>10%</td>
    </tr>
    <tr>
        <td>Màquina Upload</td>
        <td>25%</td>
        <td>15%</td>
        <td>10%</td>
    </tr>
    <tr>
        <td>Màquina Hackzones</td>
        <td>25%</td>
        <td>15%</td>
        <td>10%</td>
    </tr>
    <tr>
        <td>Màquina DebugMe</td>
        <td>25%</td>
        <td>15%</td>
        <td>10%</td>
    </tr>
    <tr>
        <td><strong>Total</strong></td>
        <td><strong>100%</strong></td>
        <td><strong>60%</strong></td>
        <td><strong>40%</strong></td>
    </tr>
</table>
---

## 7. Entregables

- Informe tècnic
- Presentació oral
- Scripts i captures

---
