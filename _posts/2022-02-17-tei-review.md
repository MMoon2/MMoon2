# TEI Project Review

### By Meghan Moon

#### Project Overview

For my class's TEI project, we were instructed to translate a piece from a novel into [XML](https://en.wikipedia.org/wiki/XML), extensible markup language. To begin, we were each assigned a separate section from [_Dracula’s Guest_](http://www.bramstoker.org/stories/03guest.html), a short story by Bram Stoker. The piece was published within _Dracula’s Guest and Other Weird Stories_ and is believed to have been a discarded draft of the first chapter to the novel, _Dracula_.  

The piece is about an unnamed man who wanders off on [Walpurgis Night](https://en.wikipedia.org/wiki/Walpurgis_Night). He gets caught in a storm and finds himself in a cemetery before being frightened by the sight of a wolf. He is soon saved and brought back home where he finds a note from Count Dracula claiming to have saved him.  

#### Annotating our Text

Our first task for the TEI project was to highlight any features within the text that require special coding. To do this, I used Google Docs to denote any page breaks, separate paragraphs, insert quotation marks, highlight em-dashes, add notes, and more. I created comments within the document by highlighting each variable adding a comment to record the type of special coding it would require.   

![paragraph](https://MMoon2.github.io/MMoon2/images/paragraph.png)

#### Coding with Oxygen

Once I annotated my assigned text, I began the coding process within [Oxygen](https://www.oxygenxml.com/xml_editor.html?gclid=Cj0KCQiApL2QBhC8ARIsAGMm-KGftV20DSqpM8yHQLmO210tk_7Aq8NcsEQuJmP-3wdXvz8bwPtGDsEaAjF-EALw_wcB), the software we used to convert our passages into XML. I began by adding the title, author, and editor to my code between opening and closing tags of the same name. These tags were included under the title tags within the TEI header tag. These tags cause this information to display at the top of my page upon entering.  

Next, I added a paragraph tag under the publication tag with the words, “Publication Information,” and then added an additional paragraph tag under the source tag which contained a link to the 1914 edition of the novel.  

![paragraph](https://MMoon2.github.io/MMoon2/images/paragraph.png)

Finally, I created two sets of opening and closing paragraph tags within the body and pasted the two paragraphs of text I had been assigned within each. Once my text was in place, I referred back to my Google Doc and began entering the code for each special character I flagged in my annotation.  

![code](https://MMoon2.github.io/MMoon2/images/code.png)

Because my text included several em-dashes, I tackled those first. I deleted the formal em-dashes from the text and replaced them with the special character code. The code for an em-dash is as follows.  

![emdash](https://MMoon2.github.io/MMoon2/images/emdash.png)

Next, I added in the note tags. The purpose of these tags is to add a definition to words that may require one. This is done by placing <note> and </note> tags after the word that contains the definition. I made sure to leave a space after the word but not after the closing tag so that there would not be additional space on the page itself.  

![note](https://MMoon2.github.io/MMoon2/images/note.png)

The last element I needed to add to my code was a page break which occurred in the middle of my second paragraph. To do this, I deleted “[Page 11]” from the text and replaced it with the following code.  

![pagebreak](https://MMoon2.github.io/MMoon2/images/pagebreak.png)

#### Project Summary

The most difficult part of this project for me was placing the code correctly in the text to ensure I didn’t have any extra spaces or place my closing tag in the wrong place. Overall, I really enjoyed this project as it introduced me to XML and expanded my knowledge in programming. In addition, I was able to learn more about Dracula’s Guest, a novel I found very interesting. I look forward to using XML with future projects and putting this new skill to use.  

![tweet](https://MMoon2.github.io/MMoon2/images/tweet.png)
