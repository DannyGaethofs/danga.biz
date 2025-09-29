# Utilities Layer

Deze layer bevat CSS- en JavaScript-bestanden die engine-compatibele hulpfuncties en utility-klassen definiëren. 
De inhoud is modulair, rollbackbaar en DevTools-verifieerbaar. 

## Inhoud

- `utilities.css`  
- `utilities.js`  

## Scope

- Alleen bedoeld voor gebruik binnen deze layer zelf  
- Geen cross-layer afhankelijkheden  
- Volledig DevTools-verifieerbaar

## Enginegedrag

- CSS-klassen zijn getest op acceptatie door Blogger’s parser  
- JS-functies zijn conditioneel inzetbaar op basis van inputtype en device-capabilities  
- Geen globale namespace-vervuiling

## Rollbackstrategie

- Layer is volledig verwijderbaar zonder impact op andere delen van de repository  
- Subtree-pad: `layers/utilities-layer`  
- Rollback via `git rm -r layers/utilities-layer` + changelog-update

## Changelog

Zie `CHANGELOG-utilities-layer.md` voor versiehistorie, audit-layer tagging en DevTools-verificatie.
