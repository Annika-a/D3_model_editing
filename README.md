# How to use Jupyter notebook
The notebook: rome_edit.ipynb is for project where GPT-Neo-125M model is edited with data from CounterFacts dataset and then evaluated.

## 0. Install Dependencies
For installing missing dependencies

## 1. Load pretrained model
Loads GPT-Neo-125M from Hugging Face

## 2. Load CounterFact dataset
Loads CounterFact dataset from Hugging face. Only needed to do once.

## 3. Evaluate model performance
Evaluates the model performance with question "What is the capital of France”. This is used as baseline. 
Example values returned:
  Efficacy: -25.5820
  Paragraph: 1.0000
  Neighborhood: -25.5615

## 4.1 Select facts to edit
num_facts -value can be edited to change the amount of facts edited. 
Suggestion is to stay under 100 so evaluation will not take too long time.
4.2.Apply knowledge editing

## 5. Evaluate edited facts 
Evaluates the model by evaluating the changed facts.

## 6. Apply ROME properly
-Not applicable yet

## 6. Validate the Edit
This part can be used to validate the default question "What is the capital of France”.
