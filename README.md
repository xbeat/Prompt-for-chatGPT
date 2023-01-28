# chatGPT prompt!

Testo introduttivo per i prompt di **chatGPT**.


# Check copy


**PROMPT**: Check my website copy [insert copy here] and Identify 5 ways to improve it to convert more customers.

**PROMPT**: I have this issue vith a customer [insert issue] provide 10 so .ions to resolve this problem. 

**PROMPT**: Here is my email/ website/marketing copy / [insert copy here] provide 10 different versions that will maximise conversions.

**PROMPT**: Here are my notes from a meeting [insert notes here] please sort these notes into topics and themes.

**PROMPT**: Write me standard operation procedure fpr keyword research.

**PROMPT**: Can you provide me with a long and well-thought-out comprehensive yet simplified guide of [SUBJECT], that only includes offline information that you are certain is true and excludes any speculation or uncertainty? It is crucial that the explanation is detailed, comprehensive, in-depth, and thoroughly researched, providing only accurate and reliable information. Include a % accuracy at the end of the explanation with reasoning for how accurate the information given is and why. Give 2 web sources with general urls (accurate as of 2021, ends in .com, .gov, or .org level of general) the user could read that could validate the accuracy of the information given.

It argues when you ask it to do complex stuff but then maybe just emphasize you want the simplified version of a guide. Really useful prompt for studying stuff for school and still get links to sites with the info given. You can even insert general word problems in there and it could solve them.

**PROMPT**: “Where there any parts of my previous prompt that were not useful to you?”
Honestly this was a game changer and helped me get rid of chaff in my prompts. More often than not it will tell you specifically what was ignored and why but you might need to pry a bit more with something like:
“Explain why that/those part(s) of the prompt were ignored.”
If you are feeling particularly lazy you can even just write:
“Suggest a rewrite of my previous prompt and exclude any parameters, details, or text that was not interpreted by you and was not useful to the results.”

**PROMPT**: If you are posting something to the OpenAI API and you are getting nonsense/dumb responses on the JSON, try adding this before the desired request:
prompt:"The following is a conversation with an AI assistant that is an expert on [TOPIC]. The assistant is helpful, creative, clever, and very friendly.\n\nHuman: Hello, who are you?\nAI: I am an AI created by OpenAI. How can I help you today?\nHuman: " + [REQUEST],
It may look dumb, at the beginning I thought the API was nerfed, but I realize that I was just making request without giving GPT a "purpose", by using this I'm getting more consistent answers from the API.

**PROMPT**: Generate digital startup ideas based on the current needs of the people which ChatGPT can fulfill. Use the entire database and knowledge of ChatGPT to generate a business plan for the digital startup complete with idea name, a short one liner, target user persona, user's pain points to solve, main value propositions, sales & marketing channels, revenue stream sources, cost structures, key activities, key resources, key partners, idea validation steps, estimated 1st year cost of operation, and potential business challenges to look for. Write the result in a markdown table.
Generate 2 or more than 2 startup ideas using the information above and give relevant details about each of them.

