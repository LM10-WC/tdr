# Institut Universitaire des Sciences (IUS)
## Faculté des Sciences et des Technologies (FST)

### Présentation du Lab 3

**Cours** : Réseaux  
**Sujet** : Configuration de NAT et d'un réseau IoT (Internet des Objets) sur Cisco Packet Tracer

**Étudiant** : Wendy Colas  
**Niveau** : L3  

**Année** : 2025  

# Introduction
Dans le cadre de ce projet, une configuration réseau a été réalisée en utilisant GNS3 et VMware Workstation afin de simuler un environnement de travail fonctionnel et sécurisé. Les services essentiels tels que Telnet, SSH, DNS et DHCP ont été configurés avec précision pour garantir la connectivité et la gestion efficaces des appareils réseau. Ce rapport vise à détailler les étapes clés de la configuration, tout en mettant en lumière les défis rencontrés et les solutions apportées. 
Ce projet a permis d'explorer et de configurer plusieurs services réseau clés, notamment Telnet, SSH, DNS et DHCP, dans un environnement simulé à l'aide de GNS3 et VMware Workstation. Deux topologies distinctes, intégrant des VPCs et des conteneurs Ubuntu Docker, ont été testées, offrant des résultats intéressants. Ce travail met en évidence l'importance d'une configuration méthodique et d'un choix soigné des composants pour assurer la connectivité et la gestion réseau.

---

# Reproduction de la topologie en configurant le protocole Telnet

## Étapes de configuration

### 1. Définition de l'interface réseau
La première étape consiste à activer et configurer l'interface réseau de base.

![Configuration de l'interface](C:/Td-2025/Td/image/image%20(50).png)

### 2. Attribution des adresses IP
La deuxième étape est l'attribution des adresses IP à l'interface.

![Attribution des adresses IP](C:/Td-2025/Td/image/image%20(51).png)

### 3. Activation de Telnet
Configuration des lignes VTY pour permettre l'accès via Telnet.

![Activation de Telnet](C:/Td-2025/Td/image/image%20(52).png)

### 4. Vérification de la connectivité
Tests de connectivité entre les appareils configurés pour Telnet.

![Tests de connectivité](C:/Td-2025/Td/image/image%20(53).png)

### 5. Sauvegarde des configurations
Confirmation et sauvegarde des configurations.

![Sauvegarde des configurations](C:/Td-2025/Td/image/image%20(54).png)

### 6. Résolution des erreurs
Gestion des erreurs lors de la configuration.

![Gestion des erreurs](C:/Td-2025/Td/image/image%20(55).png)

### 7. Résultat final
Topologie fonctionnelle avec le protocole Telnet entièrement opérationnel.

![Topologie finale](C:/Td-2025/Td/image/image%20(56).png)

---

# Reproduction de la topologie en configurant le protocole Telnet en utilisant un Ubuntu Docker guest

## Étapes de la configuration

### 1. Connexion initiale via Telnet
![Connexion initiale](C:/Td-2025/Td/image/image%20(57).png)

### 2. Interface réseau après configuration
![Interface réseau](C:/Td-2025/Td/image/image%20(58).png)

### 3. Vérification de l'état des interfaces
![Vérification interfaces](C:/Td-2025/Td/image/image%20(59).png)

### 4. Modification du fichier de configuration réseau
![Configuration réseau](C:/Td-2025/Td/image/image%20(60).png)

### 5. Résultats après redémarrage des services
![Résultats après redémarrage](C:/Td-2025/Td/image/image%20(61).png)

### 6. Test de connectivité réseau
![Test connectivité](C:/Td-2025/Td/image/image%20(62).png)

### 7. Utilisation du protocole Telnet pour l'accès distant
![Telnet accès distant](C:/Td-2025/Td/image/image%20(63).png)

### 8. Résultats finaux de la configuration
![Résultats finaux](C:/Td-2025/Td/image/image%20(64).png)

---

# Reproduction de la topologie en configurant le protocole SSH

### Image 1 : Vue globale de la topologie
![Image 65](C:/Td-2025/Td/image/image%20(65).png)

### Image 2 : Configuration de l'interface FastEthernet
![Image 66](C:/Td-2025/Td/image/image%20(66).png)

### Image 3 : Configuration du PC1
![Image 67](C:/Td-2025/Td/image/image%20(67).png)

### Image 4 : Configuration du PC2
![Image 68](C:/Td-2025/Td/image/image%20(68).png)

### Image 5 : Configuration de SSH sur le routeur
![Image 69](C:/Td-2025/Td/image/image%20(69).png)

### Image 6 : Vérification des connexions réseau
![Image 70](C:/Td-2025/Td/image/image%20(70).png)

---

# Reproduction de la topologie du réseau en configurant SSH avec un Ubuntu Docker guest

### Étapes principales :

### 1. Configuration initiale avec Solar-PuTTY
![Image 71](C:/Td-2025/Td/image/image%20(71).png)

### 2. Configuration d'un PC virtuel (VPCS)
![Image 72](C:/Td-2025/Td/image/image%20(72).png)

### 3. SSH et génération de clés RSA
![Image 73](C:/Td-2025/Td/image/image%20(73).png)

### 4. Résultat de la commande `ifconfig`
![Image 74](C:/Td-2025/Td/image/image%20(74).png)

### 5. Fichier réseau statique modifié
![Image 75](C:/Td-2025/Td/image/image%20(75).png)

### 6. Configuration réseau dans Ubuntu Docker
![Image 76](C:/Td-2025/Td/image/image%20(76).png)

### 7. Configuration du client SSH
![Image 77](C:/Td-2025/Td/image/image%20(77).png)

### 8. Session SSH réussie
![Image 78](C:/Td-2025/Td/image/image%20(78).png)

---

# Reproduction de la topologie du réseau en configurant le serveur DNS

### Étapes principales :
1. Activation du DNS sur le routeur.  
2. Configuration des interfaces et attribution des adresses IP.  
3. Paramétrage des passerelles par défaut et des adresses IP des PC.  
4. Test de résolution DNS avec `ping` et `nslookup`.

### Images supplémentaires :
![Image 81](C:/Td-2025/Td/image/image%20(81).png)  
![Résolution DNS réussie](C:/Td-2025/Td/image/image%20(85).png)  

---

# Reproduction de la topologie du réseau en configurant DHCP

## Étapes principales :
### 1. Configuration initiale
![Image 91](C:/Td-2025/Td/image/image%20(91).png)

### 2. Vérification des paramètres de DHCP
![Image 92](C:/Td-2025/Td/image/image%20(92).png)

### 3. Simulation de la connectivité des PC
![Image 93](C:/Td-2025/Td/image/image%20(93).png)

### 4. Résultats du ping test
![Image 94](C:/Td-2025/Td/image/image%20(94).png)

### 5. Finalisation et sauvegarde de la configuration
![Image 95](C:/Td-2025/Td/image/image%20(95).png)

---




