# AI Prompt Generator


## The repository stores the HTML code to provide an AI prompt generator feature. The origin code was generated with use of the Claude AI (https://claude.ai/).


### The code in this form can be used as a standalone html file, with no need to publish on the web, and providing the full scope of the features.


#### General description


The html document stands for the AI prompts generator, which operates under the RICECO framework, to provide better and more accurate prompt output. The generated prompt can be copied as a plain text and JSON structure as well. What is also important, none of the elements are the mandatory ones and can be omitted, still delivering consistent and functional, usable prompt content.

#### RICECO framework description


* **R** stands for **Role** in which AI should incarnate in (all phrases like 'act as top tier specialist …' perfectly fits here)
* **I** stands for **Instruction** - describe what AI is supposed to do on behalf of you (e.g. write me a summary of the today news - your favourite news service here - with highlight the most remarkable financial news).
* **C** stands for **Context** - deliver background information to set up the specific boundaries and express your needs / use case.
* **E** stands for **Expectations** - provide expectations of the desired output -  should it be brief or deep dive, provide some sample of the output you are willing to get in return.
* **C** stands for **Constraints** - this is a perfect space for any limits or rules which apply to your case (e.g. 1000 words length, post which wasn’t published in any corner of the internet, etc.)
* **O** stands for **Outcome** - describe what is the desired AI answer you are supposed to see at the end of the model' reasoning process (e.g. presentation deck content, social media post, etc)

#### AI Prompt Generator fields description


The general idea is very simple and most of the fields corresponds to the **RICECO** framework (**Role**, **Instruction**, **Context**, **Expectations**, **Constraints** and **Outcome**).

##### The additional feature here are:

* the **Output Style** dropdown field - here the User can choose the style which influences the general output tone. There are several options like **Professional**, **Technical**, **Creative** and so on. However, if the User is not satisfied with the provided options, via choosing **Custom Output Style**, is enabled to provide its own **Output Style** definition. The additional field  - the**Custom Output Style** - appears below the dropdown field to provide this feature.
* Checkbox **Generate as JSON** serves to switch between a plain text and JSON structure formatted prompt. Here, all the provided parameters are connected into key-value pairs with the respective field' names.
* **GENERATE PROMPT** button - this one makes things happen and turns all provided parameters into a prompt text. Important note here is that, if the checkbox **Generate as JSON** is checked, the JSON prompt appears automatically.
* **COPY TO CLIPBOARD** button - this one copies the generated prompt simply and enables the user to paste it directly into the chat window (or anywhere else :).

**Happy prompting!**
