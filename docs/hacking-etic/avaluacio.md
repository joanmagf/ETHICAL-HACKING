### Taula de Resultats d'aprenentatge - Criteris d'avaluació - Percentatges

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

<h3>🔍 Màquina: Injection (Nivell bàsic - Injecció SQL)</h3>
<table>
  <thead>
    <tr>
      <th>Criteri</th>
      <th>Inicial (1-4)</th>
      <th>En procés (4-5)</th>
      <th>Assolit (6-8)</th>
      <th>Excel·lent (9-10)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RA5.a Autenticació web</td>
      <td>No identifica cap mètode</td>
      <td>Identifica mètodes bàsics</td>
      <td>Analitza seguretat i vulnerabilitats</td>
      <td>Compara sistemes i proposa millores</td>
    </tr>
    <tr>
      <td>RA5.b Inventari serveis</td>
      <td>No escaneja serveis</td>
      <td>Detecta alguns serveis</td>
      <td>Realitza inventari complet amb Nmap</td>
      <td>Documenta serveis i riscos associats</td>
    </tr>
    <tr>
      <td>RA5.c Flux HTTP</td>
      <td>No entén les peticions</td>
      <td>Analitza peticions simples</td>
      <td>Utilitza Burp o similar correctament</td>
      <td>Documenta fluxos amb captures i explicacions</td>
    </tr>
    <tr>
      <td>RA5.d Vulnerabilitats manuals</td>
      <td>No troba vulnerabilitats</td>
      <td>Identifica errors menors</td>
      <td>Explotació manual d’injecció SQL</td>
      <td>Troba vectors alternatius i suggereix defenses</td>
    </tr>
    <tr>
      <td>RA5.e Eines d’explotació</td>
      <td>No sap usar-les</td>
      <td>Execució bàsica</td>
      <td>SQLmap i Burp utilitzats adequadament</td>
      <td>Integra diverses eines i opcions avançades</td>
    </tr>
    <tr>
      <td>RA5.f Explotació per programari</td>
      <td>No accedeix a dades</td>
      <td>Accedeix parcialment</td>
      <td>Exfiltra credencials/dades sensibles</td>
      <td>Documenta explotació i proposta de correcció</td>
    </tr>
  </tbody>
</table>

<h3>📤 Màquina: Upload (Nivell mitjà - Upload vulnerabilitat)</h3>
<table>
  <thead>
    <tr>
      <th>Criteri</th>
      <th>Inicial (1-4)</th>
      <th>En procés (4-5)</th>
      <th>Assolit (6-8)</th>
      <th>Excel·lent (9-10)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RA5.a Autenticació web</td>
      <td>No analitza restriccions d'accés</td>
      <td>Reconeix mecanismes bàsics</td>
      <td>Analitza validació i control d’accés</td>
      <td>Detecta bypass i planteja defenses</td>
    </tr>
    <tr>
      <td>RA5.b Inventari serveis</td>
      <td>Cap reconeixement d'entorn</td>
      <td>Identificació parcial d’elements</td>
      <td>Inventari detallat amb eines</td>
      <td>Informe complet amb mapes de xarxa</td>
    </tr>
    <tr>
      <td>RA5.c Flux HTTP</td>
      <td>No segueix el procés d’upload</td>
      <td>Entén parcialment les capçaleres</td>
      <td>Intercepta i modifica peticions</td>
      <td>Detecta validacions mal implementades</td>
    </tr>
    <tr>
      <td>RA5.d Vulnerabilitats manuals</td>
      <td>No intenta uploads maliciosos</td>
      <td>Prova extensions comunes</td>
      <td>Desplega shells PHP funcionals</td>
      <td>Troba varies formes d’evasió</td>
    </tr>
    <tr>
      <td>RA5.e Eines d’explotació</td>
      <td>Cap eina usada</td>
      <td>Fa servir alguna amb errors</td>
      <td>Aplica correctament gobuster o Burp</td>
      <td>Combina escaneig + explotació</td>
    </tr>
    <tr>
      <td>RA5.f Explotació per programari</td>
      <td>No s’executa codi</td>
      <td>S’executa parcialment</td>
      <td>Shell funcional</td>
      <td>Escalada de privilegis documentada</td>
    </tr>
  </tbody>
</table>

<h3>🧠 Màquina: Hackzones (Nivell avançat - Escalada de privilegis)</h3>
<table>
  <thead>
    <tr>
      <th>Criteri</th>
      <th>Inicial (1-4)</th>
      <th>En procés (4-5)</th>
      <th>Assolit (6-8)</th>
      <th>Excel·lent (9-10)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RA5.a Autenticació web</td>
      <td>No detecta mecanismes</td>
      <td>Detecta mètodes en client</td>
      <td>Analitza sessions i cookies</td>
      <td>Demostra tècniques de manipulació</td>
    </tr>
    <tr>
      <td>RA5.b Inventari serveis</td>
      <td>No detecta serveis actius</td>
      <td>Escaneig parcial</td>
      <td>Identificació avançada amb scripts</td>
      <td>Recull informació d'usuari i OS</td>
    </tr>
    <tr>
      <td>RA5.c Flux HTTP</td>
      <td>Flux confús</td>
      <td>Algunes rutes identificades</td>
      <td>Mapeig funcional de l'aplicació</td>
      <td>Detall complet d’interaccions + anàlisi</td>
    </tr>
    <tr>
      <td>RA5.d Vulnerabilitats manuals</td>
      <td>No detecta vectors</td>
      <td>Prova sense èxit vulnerabilitats conegudes</td>
      <td>Explota XSS o escales bàsiques</td>
      <td>Identifica cadenes de vulnerabilitats</td>
    </tr>
    <tr>
      <td>RA5.e Eines d’explotació</td>
      <td>Cap eina utilitzada</td>
      <td>Us parcial de LinPEAS o BeEF</td>
      <td>LinPEAS, BloodHound o ZAP utilitzats</td>
      <td>Workflow complet amb documentació</td>
    </tr>
    <tr>
      <td>RA5.f Explotació per programari</td>
      <td>No accedeix a cap nivell superior</td>
      <td>Accés parcial (user)</td>
      <td>Escalada a root o admin</td>
      <td>Explotació + root + mitigació proposada</td>
    </tr>
  </tbody>
</table>

<h3>🔧 Màquina: DebugMe (Nivell expert - Entorns de desenvolupament)</h3>
<table>
  <thead>
    <tr>
      <th>Criteri</th>
      <th>Inicial (1-4)</th>
      <th>En procés (4-5)</th>
      <th>Assolit (6-8)</th>
      <th>Excel·lent (9-10)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>RA5.a Autenticació web</td>
      <td>No analitza entorns dev</td>
      <td>Detecta entorns de prova</td>
      <td>Analitza diferències dev/prod</td>
      <td>Troba claus, API keys o fallades greus</td>
    </tr>
    <tr>
      <td>RA5.b Inventari serveis</td>
      <td>Escaneig incomplet</td>
      <td>Detecta serveis visibles</td>
      <td>Mapeig del backend i API</td>
      <td>Identificació de serveis exposats innecessàriament</td>
    </tr>
    <tr>
      <td>RA5.c Flux HTTP</td>
      <td>No comprén l’arquitectura</td>
      <td>Flux dev parcial</td>
      <td>Comprensió completa amb eines</td>
      <td>Explicació amb diagrames i capturas</td>
    </tr>
    <tr>
      <td>RA5.d Vulnerabilitats manuals</td>
      <td>Cap intent de test</td>
      <td>Errors simples detectats</td>
      <td>Accés a variables de debugging o entorns</td>
      <td>Obtenció de credencials + anàlisi completa</td>
    </tr>
    <tr>
      <td>RA5.e Eines d’explotació</td>
      <td>Cap eina utilitzada</td>
      <td>Us de ZAP o curl sense resultats</td>
      <td>Explotació de rutes dev o debug</td>
      <td>Escenari complet amb Dradis o Faraday</td>
    </tr>
    <tr>
      <td>RA5.f Explotació per programari</td>
      <td>No accedeix a dades</td>
      <td>Accedeix parcialment</td>
      <td>Exfiltra dades o secrets d’entorn</td>
      <td>Accés, escalada i proposta de seguretat</td>
    </tr>
  </tbody>
</table>
# Taula d'Avaluació del Report de Pentesting

## Criteris Generals

| Criteri | Excel·lent (9-10) | Notable (7-8) | Aprovat (5-6) | Insuficient (0-4) |
|---------|-------------------|---------------|---------------|-------------------|
| **Estructura i Organització** | Report ben estructurat amb totes les seccions necessàries. Format professional i fàcil de seguir. | Report ben organitzat amb la majoria de seccions. Format clar. | Estructura bàsica present però amb algunes seccions incompletes. | Estructura confusa o incompleta. |
| **Documentació Tècnica** | Documentació detallada i precisa de tot el procés. Captures de pantalla clares i ben explicades. | Documentació adequada amb la majoria dels passos explicats. | Documentació bàsica amb algunes parts poc clares. | Documentació incompleta o confusa. |
| **Anàlisi de Vulnerabilitats** | Anàlisi exhaustiu i detallat de totes les vulnerabilitats trobades. Explicació clara del risc i impacte. | Anàlisi adequat de les vulnerabilitats principals. | Anàlisi bàsic de les vulnerabilitats més evidents. | Anàlisi incomplet o incorrecte. |
| **Explotació** | Explotació exitosa de totes les vulnerabilitats amb proves detallades. | Explotació de la majoria de vulnerabilitats amb proves adequades. | Explotació bàsica de les vulnerabilitats principals. | Explotació incompleta o incorrecta. |
| **Mitigació i Recomanacions** | Recomanacions detallades i pràctiques per a cada vulnerabilitat. | Recomanacions adequades per a la majoria de vulnerabilitats. | Recomanacions bàsiques per a les vulnerabilitats principals. | Recomanacions incompletes o inadequades. |

## Criteris Específics

| Criteri | Excel·lent (9-10) | Notable (7-8) | Aprovat (5-6) | Insuficient (0-4) |
|---------|-------------------|---------------|---------------|-------------------|
| **Reconeixement** | Anàlisi complet de ports, serveis i versions. Documentació detallada del procés. | Anàlisi adequat dels ports i serveis principals. | Anàlisi bàsic dels ports oberts. | Anàlisi incomplet o incorrecte. |
| **Escaneig de Vulnerabilitats** | Ús efectiu de múltiples eines. Resultats ben analitzats i documentats. | Ús adequat d'eines principals. Resultats documentats. | Ús bàsic d'eines. Resultats parcialment documentats. | Ús inadequat d'eines o resultats poc documentats. |
| **Explotació d'Vulnerabilitats** | Explotació exitosa amb proves detallades i captures. | Explotació adequada amb proves bàsiques. | Explotació parcial amb algunes proves. | Explotació incompleta o sense proves. |
| **Post-Explotació** | Anàlisi complet de l'accés obtingut i possibles vectors d'atac addicionals. | Anàlisi adequat de l'accés i vectors principals. | Anàlisi bàsic de l'accés obtingut. | Anàlisi incomplet o incorrecte. |
| **Presentació** | Format professional, llenguatge tècnic precís, figures i taules ben integrades. | Format clar, llenguatge tècnic adequat, figures presents. | Format bàsic, llenguatge tècnic parcialment correcte. | Format inadequat, llenguatge tècnic incorrecte. |

## Notes Addicionals

- **Puntuació Mínima per Aprovat**: 5/10 en cada criteri
- **Puntuació Final**: Mitjana ponderada de tots els criteris
- **Extra Points**: Es poden atorgar fins a 2 punts extra per:
  - Descobriment de vulnerabilitats no documentades
  - Solucions creatives o innovadores
  - Documentació excepcionalment detallada

## Observacions Generals

- Es valorarà especialment la claredat en l'explicació dels passos seguits
- Les captures de pantalla han de ser clares i estar ben etiquetades
- Es valorarà la capacitat d'anàlisi i síntesi
- Es tindrà en compte l'ús adequat de la terminologia tècnica