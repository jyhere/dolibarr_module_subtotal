# Change Log
All notable changes to this project will be documented in this file.

# [Unreleased]

- NEW : Sum qty in each subtotal line  *10/12/2021* - 3.9.0 [PR #222 OpenDsi](https://github.com/ATM-Consulting/dolibarr_module_subtotal/pull/222)  
  
  Apport de possibilité du choix du modèle de docuement dans la configuration du module.
  Les options sur les sous-totaux ont été mises sur les lignes de sous-totaux pour simplification du code et éviter de parcourir toutes les lignes afin de retrouver le titre parent.
- NEW : Can select sub-total lines in supplier order and invoice  *10/12/2021* - 3.8.0 [PR #226 OpenDsi](https://github.com/ATM-Consulting/dolibarr_module_subtotal/pull/226)

## Version 3.7
- FIX : Compatibility with version 15 *14/12/2021* - 3.7.1
- NEW : add api subtotal to module. add entryPoint getTotalLine  *17/11/2021* - 3.7.0
    

## Version 3.6
- FIX : Title lines broken on PDF for documents whose lines use the `desc` field instead of the `label` field (such as
        supplier orders and invoices) *22/11/2021* - 3.6.9
- FIX : checkbox to add a subtotal title block per order on invoices using the "Bill orders" feature was broken by
        core changes in Dolibarr *12/11/2021* - 3.6.8
- FIX : addition of a conf allowing to add the subtotal line or not when creating an expedition from an order *12/07/2021* - 3.6.7 
- FIX : Clone icon compatibility *08/06/2021* - 3.6.6
- FIX : Uniformize module descriptor's editor, editor_url and family fields *2021-06-08* - 3.6.5
- FIX : Ajout include de la classe dans actions_subtotal pour éviter des erreurs *21/05/2021* - 3.6.4
- FIX : Fix document line colspan fail if Margin module don't enabled but some conf of this module still actived *21/04/2021* - 3.6.3
- FIX : Dolibarr v13.0 compatibility (token renewal exclusion) *13/04/2021* - 3.6.2
- FIX : Exclude subtotals from the total calculation *07/04/2021* - 3.5.6
- NEW : Ajouter les lignes 'Titre' , 'Total' , 'Libre' aux generations d'expeditions de commandes expédiables (il faudra
  supprimer les lignes de sous-total à la main si le besoin s'en fait sentir) *03/04/2021* - 3.5.5


## Version 3.5

- FIX : Text or title line break PDF *15/04/2021* - 3.5.7
- NEW Ajouter les lignes 'Titre' , 'Total' , 'Libre' aux generations d'expeditions de commandes expédiables (il faudra
  supprimer les lignes de sous-total à la main si le besoin s'en fait sentir) *2021-02-03* - 3.5.5
- NEW : Add more compatibility for new PDF models using new cols system. 
  Ceci est un fix avec un fort impact potentiel sur les instances courantes. Il est donc préférable de le placer
  sur une nouvelle release - 3.5

## Version 3.5
- FIX: invoice creation: title/subtotal/free text lines coming from shipments or deliveries not imported with special code (MDLL) - *17/11/2021* - 3.5.8
- FIX : Text or title line break PDF *15/04/2021* - 3.5.7
- NEW Ajouter les lignes 'Titre' , 'total' , 'libre' aux generation d'expedition de commandes expédiables (il faudra supprimer les lignes de sous-total à la main si le besoin s'en fait sentir ) [2021-02-03]

