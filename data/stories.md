
#################      TRIBUNAL       #################
## demande_tribunal
* greet
  - utter_greet
* tribunal
  - utter_tribunal
* affirm
  - utter_aurevoir

## demande_tribunal
* tribunal
  - utter_tribunal
  

## demande tribunal agir avec un avocat a la cour
* greet
  - utter_greet
* avec_ou_sans_avocat_a_la_cour{"avocat": "avec"}
  - utter_avec_un_avocat_a_la_cour
* affirm
  - utter_aurevoir

## demande tribunal agir sans un avocat a la cour
* greet
  - utter_greet
* avec_ou_sans_avocat_a_la_cour{"avocat": "sans"}
  - utter_sans_un_avocat_a_la_cour
* affirm
  - utter_aurevoir

## demande tribunal procedures judiciaires conjoitns
* greet
  - utter_greet
* procedures_judiciaires{"relation": "conjoints"}
  - utter_procedures_judiciaires_conjoints
* affirm
  - utter_aurevoir

## demande tribunal procedures judiciaires maries
* greet
  - utter_greet
* procedures_judiciaires{"relation": "maries"}
  - utter_procedures_judiciaires_maries
* affirm
  - utter_aurevoir
##########################################################

#################      MEDIATION       #################
## demande mediation
* greet
  - utter_greet
* mediation
  - utter_mediation
* affirm
  - utter_aurevoir

##demande mediation
* mediation
  - utter_mediation

#################      DIVORCE       #################

## demande_divorce
* greet
  - utter_greet
* divorce
  - utter_divorce
* affirm
  - utter_aurevoir

## demande divorce
* divorce
  - utter_divorce

#################      DOMICILE, BIENS ET ARGENT       #################

  ## ask_domicile_biens_argent
* greet
  - utter_greet
* domicile_biens_argent
  - utter_domicile_biens_argent
* affirm
  - utter_aurevoir

## demande domicile
* domicile
  - utter_domicile

## demande biens et argent
* greet
  - utter_greet
* biens_et_argent
  - utter_biens_et_argent
* affirm
  - utter_aurevoir

## demande de maitien du niveau de vie
* greet
  - utter_greet
* maintien_du_niveau_de_vie
  - utter_maintien_du_niveau_de_vie
* affirm
  - utter_aurevoir

#################      ENFANTS      #################

## demande_enfants
* greet
  - utter_greet
* enfants
  - utter_enfants
* affirm
  - utter_aurevoir

## demande garde
* garde
  - utter_garde

## demande sante education religion et voyage
* greet
  - utter_greet
* sante_education_religion_voyage
  - utter_sante_education_religion_voyage
* affirm
  - utter_aurevoir

## demande sante education religion voyage
* sante_education_religion_voyage
  - utter_sante_education_religion_voyage

## demande de pension alimentaire
* greet
  - utter_greet
* pension_alimentaire
  - utter_pension_alimentaire
* affirm
  - utter_aurevoir

## demande pension alimentaire
* pension_alimentaire
  - utter_pension_alimentaire

#################      AUTRES      #################

## demande_meteo
* greet
  - utter_greet
* meteo
  - utter_meteo
* affirm
  - utter_aurevoir
   
## je suis un robot
* jesuisunrobot
  - utter_jesuisunrobot

## au revoir
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

## ask_homepage
* greet
  - utter_greet
* homepage
  - utter_homepage
* affirm
  - utter_aurevoir