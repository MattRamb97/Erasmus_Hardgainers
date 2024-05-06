<h1 align="center">Erasmus Hardgainers</h1>

Welcome to Erasmus_Hardgainers project, your go-to destination for delectable natural language processing (NLP) recipes! Just like crafting a gourmet dish requires the perfect blend of ingredients and precise instructions, mastering NLP involves combining algorithms, datasets, and code in a harmonious symphony. Whether you're a seasoned NLP chef or a novice eager to sharpen your skills, our GitHub repository is here to guide you through a flavorful journey of linguistic exploration.

Using only the dataset **recipes_raw_nosource_ar.json**

NVIDIA RTX 4090 (24GiB) 1 GPUs x 16 CPUs | 62GiB
1. **Recipes_model.ipynb**:
   - without concanate together all the ingredients
   - without cleaning the quantities of the ingredients
   - train of the model on prompt: title -> get ingredients and instructions (200 raws)
   - evaluate the model on prompt: ingredients -> get title and instructions
2. **Recipes_model_v2.ipynb**:
   - concanating together all the ingredients
   - without cleaning the quantities of the ingredients
   - train of the model on prompt: ingredients -> get title and instructions (1000 raws)
   - evaluate the model on prompt: ingredients -> get title and instructions
3. **Recipes_model_v3.ipynb**:
   - concanating together all the ingredients
   - cleaning the quantities of the ingredients
   - train of the model on prompt: ingredients -> get title and instructions (5000 raws)
   - evaluate the model on prompt: ingredients -> get title and instructions

NVIDIA H100 (80GiB) 1 GPUs x 31 CPUs | 177GiB
1. **Recipes_model_v4.ipynb**:
   - concanating together all the ingredients
   - cleaning the quantities of the ingredients
   - train of the model on prompt: ingredients -> get title and instructions (19761 raws)
   - evaluate the model on prompt: ingredients -> get title and instructions
2. **Recipes_model_v5.ipynb**:
   - concanating together all the ingredients
   - cleaning the quantities of the ingredients
   - train of the model on prompt: ingredients -> get title and instructions (5000 raws)
   - evaluate the model on prompt: ingredients -> get title and instructions
