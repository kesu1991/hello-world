# Coca-Cola's Brands Analysis Project - Ke Su

## Contents
<ol>
  <li>General Introduction</li>
  <li>Enviorment and Software Set Up</li>
  <li>Listed Source File</li>
  <li>Products Interaction</li>
</ol>


### General Introduction

"Exploration of the switching behaviour in different drinking products under Coca-Cola company. Process are seperated into two parts, 'General Tree' to have a first look of the Coca-Cola's beverage market and 'Heatmap' will show the beverage interaction with switching behaviour explaned. Additional work but not mainly focus in these project is to analaysis the market and choose the useful features such as price, unit size, units per package. To increase the profit by adjusting these features could be helpful in the future. Several process to increase the model accurate, random forrest was used at the end to produce the probability."

### Enviorment and software set up

- Anaconda Jupyter Notebook
- Microsoft Excel (Tree)
- ProcessOn (Tree)

### Listed source file

- Coca-Cola-Products-Interaction.ipynb
    - Products interaction analysis
    - Python code run in Jupyter Notebook
    
- Coca-Cola-Market-Strategy
    - Market strategy analysis
    - Python code run in Jupyter Notebook
    
- used_data.csv  
    - csv file stores the whole dataset with some not useful columns deleted

- cokes17to18.csv
    - csv file stores promotion column from 2017 to 2018
   
### Products Interaction

"Coca-Cola runs several brands in the Philippine's market including 'Coke', 'Sprite', 'Royal', 'Sparkle' and 'Wilkins'. These brands can be grouped into three typical categories, 'Coke', 'Not Coke' and 'Water' OR 'Soft Drink', 'Not Soft Drink'. The main purpose of this project is to see the switching trend between different brands. Two sections will be generated to produce the result. First section, 'General Tree' illustrate the basic description of the market and second section 'Metrics' store the switching probability in each criteria." Key features are selected by random forrest model.

- Sections
    - General Tree
        - General description of the data
        - Features selected by 'Random Forrest' Model and with customer behavier explanation
        - 'Pack Type' and 'Unit Size' are selected

    - Heatmap Matrices
        - Product interaction on different brands under selected features
        - General interaction
        - Two pack type 'Glass Bottle' and 'Plastic Bottle'
        - Four unit size '750ML', '1000ML', '1500ML', '1750ML'
        
- Process
    - Data feature engineering
        - Add promotion information
        - Select year from 2017 to 2018
    - Data formatting
        - Label Encoding
    - Model selection
        - Random forrest, Decesion tree, Gradient boosting
    - Extract important features
        - Pack type(Glass, Plastic) and Unit size(750ML, 1000ML, 1500ML, 1750ML)
    - Generate metrices
        - Matrices within pack type and unit size 
- Results
    - General tree 
    <img src="tree.PNG" style="width:900px;height:600px;">
    
    - Product Interaction – All Combination!
    <img src="all.PNG" style="width:600px;height:500px;">
    
    - Product Interaction – Package(Glass,Plastic)
    <img src="glass.png" style="width:600px;height:500px;">
    <img src="plastic.PNG" style="width:600px;height:500px;">
    
    - Product Interaction – Unit Size (750ml, 1000ml, 1500ml, 1750ml)
    <img src="75.PNG" style="width:600px;height:500px;">
    <img src="1.PNG" style="width:600px;height:500px;">
    <img src="1.5.PNG" style="width:600px;height:500px;">
    <img src="1750.PNG" style="width:600px;height:500px;">




