# Note2.0xsite

## Motivation

I am ICT student. I was creating notes since age of 7. First in a classic way with notebooks in school. Later on Uni I switched to [Markdown](https://en.wikipedia.org/wiki/Markdown) markup language to create notes on PC. Now I am thriving for more, for a way to create more readable, structurized notes.

I don't have to explain why markdown is a better version of classic notebook. The ease of editing, portability, paperless concept. What markdown lacks in my opinion?

- First Markdown "compiles" to HTML, but with pure markdown you cannot use the **full functionality of HTML&CSS** like:
  - Text alignment (Center, Right)
  - Text colors (you can only do that by HTML injection)
  - Background colors 

- **Auto numbering** of chapters
  - When you create a new chapter with heading syntax, you need to define numbering yourself
- **Multiple pages** on single topic / in single document
  - With markdown you can create multiple `.md` files and link them inside the documents. But markdown doesn't support static elements like side menu (on the left for example) unless you use software like [Typora](https://typora.io/)
- **Interactive notes**. For example you would like to hover some text fragment and then small box appears with some text e.g. term definition or personal comment (JavaScript scripts)
- Defining **objects**. 
  - Usually when you learn you introduce some new concepts, terms in your notes. It would be nice to have an opportunity to define them and automatically have some features, like bold text each time term appears, a shorthand to term definition etc.
  - Each note fragment (definition, example, comment etc.) could be recognized with special text formatting, so the user already know "ah, so this is a definition, this one is a comment". It helps build you more readable and clean notes.
- **Expanded text areas**. When you are viewing notes it is not the best idea to show everything at once. People get overwhelmed with large amount of text. It would be cool to hide some elements, and when user decided he is familiar with already depicted concepts, he can expand some element to discover more details about something
- Automatically generated **"course dictionary"**. A separate page when all the terms with their definitions go automatically.
- And even more...

Of course it is "doable" with markdown. You just need to add some HTML&CSS to your resulting `.html/.md` file. Unfortunate process of creating notes that way would be really long and onerous to repeat each time. It can be automated and simplified. Also this kind of note taking may require some knowledge of HTML&CSS etc. and I want to have a tool that goes beyond the technical/IT environment.