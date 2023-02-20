---
marp: false
theme: default
title: Mon installation panneau solaire
html: true
---

# localisation

    Installation dans la région Valentinnoise (Drôme) dans un endroit exposé au vent (mistral)
    Maison 90m² rénovée avec isolation refaite.
    Tout électrique + insert dernière génération (bois séché 3ans dans le jardin)
    DP mairie, CACCSI enedis, assurance OK. Pas de consuel (non demandé par enedis)

# Panneau solaire

    installation des panneaux sur toit plat (abri pour le bois) par mes soins avec l'aide des copains pour monter les panneaux.
    installation à plat car zone très exposée au vent. pas d'ajout d'equerre pour une inclinaison à 30° par exemple.
    Pas d'installation sur le toit de la maison car toit refait (donc sous décennale) et ombrage par des grands arbres.
    1 kit oscaro fin 2019 de 4 panneaux 275W + 2 YC600
    ajout 2 panneaux en 2021 de 2 panneaux 300Wc + 1 YC600 (osacro) , plus de place sur le toit de l'abri.
    ajout 2 panneaux en 2022 sur pergola (toit plat) + 1 DS3 (oscaro) partiellement ombragé le matin.
    production sur ligne dédiée différentiel + disjoncteur via prise 230V Véhicule électrique renforcée.
    parafoudre sur tableau général.
    suivi des micro_injecteurs par ECU-ESP32
        https://github.com/patience4711/read-APSystems-YC600-QS1-DS3
        https://github.com/patience4711/read-APSystems-YC600-QS1-DS3/wiki
        https://www.youtube.com/watch?v=7ZOAcrYXxbM


# routeur

    1 routeur conception perso sur la base de celui de PTWATT https://jjdegaine.github.io/Wifi-Solar-panel-optimizer-/
    en hiver surplus vers radiateur électrique
    en été asservissement en température de la PAC piscine (projet été 2023: jeedom?, domoticz?)

# contrat énergie (contrat via appel d'offre famille de France)

tarif HP/ HC (limite rentable), tempo à l'étude (semble rentable)

# production

    2020: 1290kWh => 230€ 
    2021: 1670kWh => 300€
    2022: 2650kWh (installtion 2 derniers panneaux mi mai 2022) ==> 480€ 
    objectif 2023 : 2800kWh ==> 600€ 

    suivi de production par compteur énergie avec tore. 

# consommation

    en hiver (novembre à mars) : ECS, LL, LV la nuit (HC)
    hors hiver piscine 0.9kW. ECS entre 13h et 16h (arrêt piscine entre 13h et 14h), LV, LL après 14h.
    ECS avec régulation électrique neuf (sous garantie donc pas de routage)

    ~ 10000kWh avant installation
    ~ 7500kWh après installation PV
    objectif 2023 7000kWh

# amortissement

    prix de l'installation: 2700€ (non optimisé car 3 frais de livraison)
    2019-2022: 1010€ puis 600€/an au tarif 1° février 2023 
    (2700-1010)/600 => 3 ans
    ROI 6 ans

# coupure secteur

    gestion des coupures secteur (1h à 12h de temps en temps). chauffage par cheminée, pack batterie pour les portables, camping gaz pour les reaps, ebook pour la soirée devant la cheminée. Anticipation des coupures lors des épisodes neige /vent.

# projet futur

    Plus de place sur le toit de l'abri bois ou de la pergola!
    par principe pas de batterie (amortissement, entretien).
    étude de rentabilité à faire pour installation de panneaux verticaux. production horaire inversée par rapport aux panneaux à plat. contrainte: vent!!!!

# erreur pendant la réalisation

    câblage en 4² donc reprise pour la terre en 6² aprés (nouvelle tranché!!!)




