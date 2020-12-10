# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]

## Version 3.4.0

 - [x] Préparations entité A disponibles sur CF entité B doit uniquement affiche celles au statut clôturée

 - [x] Équipement : ajout code inventaire, VPN, n° logiciel, Notes

 - [x] filtre sur entrepots (getentities) sur écran réception standard

 - [x] filtre entité sur liste des équipements

 - [x] Produit composition => création ok sauf titre / sous-total. Un ancien dev d'ATM permet de convertir un produit composé COMP 24) en plusieurs lignes. Il manque les titres / sous-totaux lorsque la ligne a été ajoutée par OFSOM (cliama conf définie dans Shanghai entié)

        dans le module cliama , lorsque que l'on est sous l'entité ama-shanghai , on doit activer la conf  
        Convertir les produits composés en bloc titre/sous-total 

 - [x] Case doit se cocher pour éviter la double réception
        
        
    
 - [x] expédition traitée réception affichage détail


## 2020-04-21

### Added

- NEW Instance monitoring

### Changed

- FIX webmodule element definition to be compatible Dolibarr call
- FIX webpassword element definition to be compatible Dolibarr call
- FIX webinstance element definition to be compatible Dolibarr call
