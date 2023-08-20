# CustomTemplateUiPath

How to make custom template into uipath

## Step by Step
![Empty xaml](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/principalXaml.PNG)

Add 4 sequences
- init
- global variables
- body
- final

![scheme](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/globalXaml.PNG)

Init sequences

Add Get current Job Info -> Get current xaml name
Add Log -> show start current xaml name

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/initSequence.PNG)

Global variables 

Add all variables do you use in your xaml

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/globalVariables.PNG)

Body sequence

Empty because this sequences you add activities

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/bodySequence.PNG)

Final sequence

Log end of current xaml execution

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/finalSequence.PNG)

## Final result
