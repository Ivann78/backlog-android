# Story 5 : Analyse de strings.xml

**Analyse du fichier strings.xml**

L’analyse du fichier strings.xml extrait de l’application a permis d’identifier plusieurs informations sensibles liées aux services backend et à la configuration de l’application.

![1](.img/1.png)

**Endpoints API exposés**

- "https://api.nickel.eu/customer-banking-api"  
    → **Risque :** exposition des endpoints bancaires pouvant faciliter des attaques de reconnaissance ou de ciblage d’API.
- "https://api.nickel.eu/customer-authentication-api"  
    → **Risque :** endpoint d’authentification exposé, pouvant être ciblé pour des attaques de brute force ou d’interception.
- "https://api.nickel.eu/personal-space-api"  
    → **Risque :** accès potentiel à des données utilisateurs personnels via analyse des requêtes API.

**Service cloud Firebase exposé**

- "https://application-client-nickel.firebaseio.com"  
    → **Risque :** exposition d’un backend Firebase pouvant contenir des données sensibles ou mal configurées.

**Clé API Google exposée**

- "google_api_key"  
    Valeur : AIzaSyBTgztvImsUfMWDa41PCrDWAj7dmyIDhUg

→ **Risque :** clé API exposée pouvant être réutilisée pour accéder à des services Google associés (abus potentiel, coût, ou extraction de données).

**Clé API de crash reporting**

- "google_crash_reporting_api_key"  
    Valeur identique à la clé Google API

→ **Risque :** possibilité d’exploitation des services de crash reporting ou d’abus de quotas.
