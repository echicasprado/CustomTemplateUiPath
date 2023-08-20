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
---

Add Get current Job Info for get current xaml name

Add Log show start current xaml name

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/initSequence.PNG)

Global variables 
---

Add all variables do you use in your xaml

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/globalVariables.PNG)

Body sequence
---

Empty because this sequences you add activities

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/bodySequence.PNG)

Final sequence
---

Log end of current xaml execution

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/finalSequence.PNG)

## Xaml to template

Click right on xaml to make template

Then click on Extract as Template 

![Extract as template](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/makeTemplate.jpeg)

Add name and location for template

![Location for template](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/newTemplate.PNG)

Look new template in Templates folder 

![Look template](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/showTemplate.PNG)

## Create xaml by template

Click new Workflow

- Add name 
- Add location
- Template select your template
- Click Create

![New xaml](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/newXamlFromTemplate.PNG)

Your new xaml content template scheme

After that add activities into body

![Init sequence](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/contentNewXamlFromTemplate.PNG)

## Final result

invoke new xaml

![Invoke xaml](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/invokeNewXaml.PNG)

show result

![Logs](https://github.com/echicasprado/CustomTemplateUiPath/blob/main/img/resultNewXaml.PNG)
