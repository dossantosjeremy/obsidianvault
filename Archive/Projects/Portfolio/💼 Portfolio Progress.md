
[[2024-11-25]]
> [!NOTE] Process to create case studies
> Automation is accessible [here](https://eu2.make.com/671501/scenarios/2648385/edit)
> 
> What was the goal of this automation? 
> * To learn the range of possibilities
> * To have my case studies in a controllable format (markdown)
> * Also have my case studies in a variety of formats (PDF, MD, Google, Notion...)
> * Being able to share my case studies to people with various needs
>  
> How does it work
> 1. It takes files from my google drive: https://drive.google.com/drive/folders/16jc4v6ZNP1Cxx4yIJwc8h8dV86H2Qwvn
> 2. It will use a Chat GPT Assistant to create a case study out of it
> 3. The case study is then converted to different formats
> 	1. Google Docs
> 		1. A comprehensive format on Google Docs
> 		2. A synthetised format on google docs
> 		3. A pdf format on Google Docs
> 	2. MarkDown Format
> 		1. A comprehensive version
> 		2. A synthesized version
> 		3. A PDF Version
> 	3. Notion format
> Now, I ran into some troubles for notion. Notion works with API Calls and a json format. The problem is, the json output might now always be predictable. 
> And sometimes, the json format might be rejected from Notion. And when that happens, even if I have like 30 case studies to process, it will be interrupted. 
> 
> Solutions I had in mind: 
> * Instructing the assistant to output the json correctly. 
> * Connecting to another assistant that will output the json correctly
> * In any case, I think as it is a bit unpredictable that it is safer to run all the jsons in a google sheets to be able to process them later. 
> * On top of that, I would have control over them way more easily. 
> * We should still look into error handling as this might happen for a lot of other reasons. 
> 



