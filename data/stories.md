## greet + tribunal + aurevoir
* greet
  - utter_greet
* tribunal
  - utter_tribunal
* affirm
  - utter_aurevoir

## tribunal
* tribunal
  - utter_tribunal
  

## greet + tribunal agir avec un avocat a la cour + aurevoir
* greet
  - utter_greet
* avec_ou_sans_avocat_a_la_cour{"avocat": "avec"}
  - utter_avec_un_avocat_a_la_cour
* affirm
  - utter_aurevoir

## greet + tribunal agir sans un avocat a la cour + aurevoir
* greet
  - utter_greet
* avec_ou_sans_avocat_a_la_cour{"avocat": "sans"}
  - utter_sans_un_avocat_a_la_cour
* affirm
  - utter_aurevoir

## greet + tribunal procedures judiciaires conjoitns + aurevoir
* greet
  - utter_greet
* procedures_judiciaires{"relation": "conjoints"}
  - utter_procedures_judiciaires_conjoints
* affirm
  - utter_aurevoir

## greet + tribunal procedures judiciaires maries + aurevoir
* greet
  - utter_greet
* procedures_judiciaires{"relation": "maries"}
  - utter_procedures_judiciaires_maries
* affirm
  - utter_aurevoir

## greet + mediation
* greet
  - utter_greet
* mediation
  - utter_mediation
* affirm
  - utter_aurevoir

## mediation
* mediation
  - utter_mediation



## greet + divorce + aurevoir
* greet
  - utter_greet
* divorce
  - utter_divorce
* affirm
  - utter_aurevoir

## divorce
* divorce
  - utter_divorce


  ## greet + domicile, biens et argent + aurevoir
* greet
  - utter_greet
* domicile_biens_argent
  - utter_domicile_biens_argent
* affirm
  - utter_aurevoir

## domicile
* domicile
  - utter_domicile

## greet + biens et argent
* greet
  - utter_greet
* biens_et_argent
  - utter_biens_et_argent
* affirm
  - utter_aurevoir

## greet + maitien du niveau de vie + aurevoir
* greet
  - utter_greet
* maintien_du_niveau_de_vie
  - utter_maintien_du_niveau_de_vie
* affirm
  - utter_aurevoir



## greet + enfants + aurevoir
* greet
  - utter_greet
* enfants
  - utter_enfants
* affirm
  - utter_aurevoir

## greet + garde + aurevoir
* garde
  - utter_garde

## greet + ante education religion et voyage + aurevoir
* greet
  - utter_greet
* sante_education_religion_voyage
  - utter_sante_education_religion_voyage
* affirm
  - utter_aurevoir

## sante education religion voyage
* sante_education_religion_voyage
  - utter_sante_education_religion_voyage

## greet + de pension alimentaire + aurevoir
* greet
  - utter_greet
* pension_alimentaire
  - utter_pension_alimentaire
* affirm
  - utter_aurevoir

## pension alimentaire
* pension_alimentaire
  - utter_pension_alimentaire


## greet + meteo + aurevoir
* greet
  - utter_greet
* meteo
  - utter_meteo
* affirm
  - utter_aurevoir
   
## je suis un robot
* jesuisunrobot
  - utter_jesuisunrobot

## aurevoir
* aurevoir
  - utter_aurevoir
  
## meteo
* meteo
  - utter_meteo
  
## blague
* blague
  - utter_blague
  
## homepage
* homepage
  - utter_homepage

## greet + homepage
* greet
  - utter_greet
* homepage
  - utter_homepage
* affirm
  - utter_aurevoir
  
## out of scope
* out_of_scope
  - utter_out_of_scope

## greet + soquij
* greet
  - utter_greet
* soquij
  - utter_soquij
  
## soquij
* soquij
  - utter_soquij