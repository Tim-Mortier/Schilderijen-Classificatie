# Schilderijen-Classificatie

Dit is een project om schilderijen van Mondriaan, Picasso, Rembrandt en Rubens te classificeren met behulp van een neuraal netwerk. De structuur van de repository is als volgt.

## 1_Data_Acquisition.ipynb

Deze notebook bevat code om rembrandt afbeeldingen te scrapen van ...

## 2_Data_Preprocessing.ipynb

Hier worden de schilderijen van de 4 schilders onderzocht op corrupte afbeeldingen en als ze in het correcte formaat staan. De 3 verschillende samplingdatasets worden hier ook aangemaakt.

## 3_EDA.ipynb

Hierin worden de statistieken rond de hoogtes en breedtes van de afbeeldingen onderzocht.

## 4_Data_augmentation.ipynb

Hierin wordt de beste data augmentation strategie onderzocht.

## 5_Data_Sampling_Reshaping.ipynb

Hierin wordt de beste sampling strategie samen met de optimale hoogtes en breedtes onderzocht.

## 6_Model_Training.ipynb

Hierin wordt het optimale model gezocht. Er wordt gestart vanuit simpele neurale netwerken om te eindigen bij pretrained convnets.

## 7_Demo.ipynb

Dit is een demo waarin het gevonden model wordt gedemonstreerd. Dit model schilderijen van de 4 schilders classificeren.