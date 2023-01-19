# Natural Selection Simulator with Genetic Algorithms

## Biome generation

### Natural habitat generation

-	Procedurally generated biomes and characters controlled by neural networks for sensor/action decision making.
-	Genetic algorithm for gene reproduction and optimization 
- This project takes an alternative path to optimization. GA's do not use traditional backpropagation to ajust network weights but rather "breed" them to obtain the mean value between 2 seperate good solutions. 


 medium nature density     |          low nature density  |     high nature density                  
:-------------------------:|:----------------------------:|:-------------------------:
![Screenshot 2023-01-16 154057](https://user-images.githubusercontent.com/65002959/212764644-402da6e2-a8bd-4b05-8286-8141488d8536.png) |  ![Screenshot 2023-01-16 154248](https://user-images.githubusercontent.com/65002959/212764676-71fdee57-4dad-4e42-b91d-144e48b784ec.png) | ![Screenshot 2023-01-16 154337](https://user-images.githubusercontent.com/65002959/212764755-b8768792-2efd-48c9-b279-3666f32e8097.png)

### Creature generation

 - Eventually, more complex character will be generated. For now, random sized and colored cubic animals with randomly generated latin names.

 Sulyha Sotaenis           |          Maejubis Gijolis    |     Qeshusis Raso & Pebyshaho Haeqisheqa               
:-------------------------:|:----------------------------:|:-------------------------:
![Capture](https://user-images.githubusercontent.com/65002959/212765592-271b6f71-ed96-4a74-8e43-2dab3cc0e4f5.PNG) | ![Screenshot 2023-01-16 154742](https://user-images.githubusercontent.com/65002959/212765602-ef46d13a-01dc-477f-92ae-920f123e5835.png) |![Screenshot 2023-01-16 155040](https://user-images.githubusercontent.com/65002959/212765606-4bde5723-cbfa-4f33-adf2-59cce2cc1f70.png)


## Genetic Algorithm Design

![GA](https://user-images.githubusercontent.com/65002959/213335497-5d64a079-3540-4692-8a88-ba18220bb3bb.png)
![GA1](https://user-images.githubusercontent.com/65002959/213335502-b2e4254e-0f0b-43d6-a0ae-43d763b4bfa6.png)

# Neural Network

 - ## Functionality
      -Characters will always be in movement unless they are eating, drinking or breeding. Depending on their Network, creatures will be responding to situations solely  by changing directions
 - ## Current Sensor and Actor Neurons
![Neurons](https://user-images.githubusercontent.com/65002959/213335512-dfb6ca9f-9f5f-475a-b31f-0c51b91d9945.png)
