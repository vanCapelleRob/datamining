# Datamining
## Info
Enkel de file __herexamen_vanCapelleRob.ipynb__ is voor het herexamen. De andere zijn van in december en nu niet meer van toepassing.

De twee datasets gaan over het COVID-19 vaccin, en vooral op de invloed (de symptomen) van het vaccin.

Na de initiële setup van spark en dergelijke laadde ik eerst de grootte dataset in. 
Mijn eerste grafiek toont de verdeling in procenten aan van welke vaccins er gebruikt zijn in deze metingen. 

Dan wou ik weten welke de meest voorkomende symptomen zijn die men krijgt na de toediening van het vaccin van Moderna en Pfizer.
Ik koos ervoor enkel deze twee te vergelijken omdat de bijdrage van andere frabrikanten zo klein was dat het te verwaarlozen valt.

Ook wou ik weten of het geslacht een invloed had op de symptomen die men kreeg. Dus vergelijk ik de vrouwlijke en mannelijke symptomen met elkaar.
De 'U' van de dataset vij 'SEX' staat volgens mij voor unknown, dus heb ik deze niet mee vergeleken.

Nu is het dan tijd voor de tweede dataset. Deze is van 2020 maar aanzienlijk kleiner en dus ook minder accuraat. Toch wou ik deze vergelijken met die van 2021.
Ik vergelijk het aantal doden dat iedere fabrikant met zich meebrengt. Dit voor beide datasets. Er moet natuurlijk wel rekening gehouden worden met het feit dat
die van 2020 een pak kleiner is. Die toont namelijk enkel gevallen van de maand december 2020. Daarom is de grafiek van 2021 ook enkel van januari 2021. 
Om het zo eerlijk mogelijk te houden. Nog steeds is het verschil zeer groot, maar onthoud dat de eerste dataset veel groter is en het resultaat misschien niet 100% correct is. 

## Link datasets
Big 100MB+ dataset: 
> https://www.kaggle.com/landfallmotto/covid19-vaccine-adverse-reactions-vaers-dataset?select=vaers_jan_aug_2021.csv

Smaller second dataset: 
> https://www.kaggle.com/elenaeb/2020-covid19-vaers-data-set
