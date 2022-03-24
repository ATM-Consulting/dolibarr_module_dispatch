# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]

## Version 3.7 - 2022-03-24
- NEW : ajout conf "Réalimenter équipement à la suppression de l'expédition" pour la dissocier de "Retirer l'entrepot de l'équipement à la validation de l'expédition" - 3.7.0 - *21/03/2022*

## Version 3.6 - 2021-12-03
- FIX : il n'était pas possible d'ajouter un équipement avec numéro de série sans numéro de lot dans le détail d'une expédition - 3.6.3 - *27/01/2022*
- FIX : les équipements n'apparaissaient pas dans le select des exped - 3.6.2 - *20/12/2021*
- FIX : detail.php, la quantité ne s'affichait plus automatiquement, erreur de js (ligne commentée) - 3.6.1 - *07/12/2021*

- NEW : Conf permettant d'ignorer la localisation ainsi que d'ajouter un num serie dans une meme exped - 3.6.0 - *03/12/2021*

## Version 3.5 - 2021-07-06

- FIX: on shipment validate use newref instead of ref - 3.5.10 - *26/11/2021*
- FIX : Js Ajax and form for dispatching new element - 3.5.9 - *17/11/2021*
- FIX : order reception - if DISPATCH_CREATE_NUMSERIE_ON_RECEPTION_IF_LOT activated wwe must give serialnumber to data or it will overide with empty serial number - 3.5.8 - *03/11/2021*
- FIX : expedition detaim - display asset with enough qty - 3.5.7 - *25/10/2021*
- FIX : expedition detaim - hide lot without units - 3.5.6 - *5/10/2021*
- FIX : v14 compatibility - NOSCRFCHECK and selectMeasuringUnits - 3.5.5 - *15/09/2021*
- FIX : v14 compatibility - setDateLivraison -> setDeliveryDate - 3.5.4 - *27/07/2021*
- FIX : display quantity of shipped products on PDF *12/07/2021* - 3.5.3
- FIX : auto-fill of expedition's tab is made with ordered qty and not with the whole lot *29/06/2021* - 3.5.2
- FIX : Add error message if no more available assets for this expedition *31/05/2021* - 3.5.1
- NEW : automatically add all the assets contained in OF with the Add automatically select option *20/05/2021* - 3.5.0

## Version 3.4 - 2020-12-10

### Added

- FIX: v13 + v14 compatibility *29/06/2021* - 3.4.3
- FIX: missing en_US translations *22/04/2021* - 3.4.1
- NEW T2966 Affiche une seule ligne par lot au lieu de plusieurs - *24/05/2021* - 3.4.2
- NEW T2476 Ventilation produits/équipement multicompany OFSOM

### Changed

- FIX : Préparations entité A disponibles sur CF entité B doit uniquement afficher celles au statut clôturée
- FIX : Équipement : ajouter code inventaire, VPN, n° logiciel, Notes
- FIX : Manque filtre sur entrepots (getentities) sur écran réception standard
- FIX : Manque filtre entité sur liste des équipements

## Version 3.3 - 2020-10-21

### Added

### Changed

- FIX error on table naming : the right table name is entity_thirdparty *29/06/2021* - 3.3.1
