# Enhanced-LM-Mixer
This is a modified language model weight-sum merge script based off of LostRuin's work. Enhancements include migrating copies of necessary files to run the model to the new model folder as well as enhanced console output. A GUI environment is required as tkinter will popup dialogue boxes prompting for the first model, the second model, and the desired folder for the new model. Additional parameters can be modified directly in the python script as it has friendly comments to guide any desired difference in mixing parameters. Defaults are 50/50 merge, operation in fp32 and model output in fp16.

Credit to LostRuin's for their initial weight-sum merge script:
https://github.com/LostRuins
