<!DOCTYPE html>

<html>

<head>

    <title>Comment Paster</title>

    <link rel="stylesheet" type="text/css" href="~/Style/invinostyle.css">

   

 

    <style>

        input {

            text-wrap: normal;

            width: 75%;

        }

        .leftside{

            position:absolute;

            left:0%;

            width:10%;

 

 

        }

        .rightside{

            position:absolute;

            left:11%;

            width: 89%;

            height:100%;

            top:0%;

        }

        .tooltip {

            position: relative;

           

        }

 

 

            .tooltip .tooltiptext {

                visibility: hidden;

                width: 250px;

                height: 250px;

                background-color: black;

                color: #fff;

                text-align: center;

                padding: 5px 0;

                border-radius: 6px;

                /* Position the tooltip text - see examples below! */

                position: absolute;

                z-index: 1;

            }

 

            .tooltip:hover .tooltiptext {

                visibility: visible;

            }

            textarea{

                width:90%;

                height:90%;

                position:absolute;

                top:5%;

                left:5%;

                font-family:"Times New Roman"

            }

 

           .hide{

               height:50px;

           }

    </style>

</head>

<body>

 

    <div id="leftside">

    <button id="introbutton" class="hide" onclick="hide('intro')">Introduction and Thesis</button>

 

    <div id="intro">

 

        <span class="tooltip">

            <button onclick="copy('Broad Opener')">Overly Broad Opening Sentence</button> <span class="tooltiptext">

                <textarea id="Broad Opener"> Avoid starting your paper with overly broad generalizations like this. It is just filler.  You want to hook your audience by immediately introducing them to the specific problem or question that your essay will investigate.</textarea>

            </span>

        </span>

        <br />

 

        <span class="tooltip">

           <button onclick="copy('Introduce Argument')">Introduce Argument</button>

            <span class="tooltiptext">

                <textarea id="Introduce Argument">You should typically avoid starting your argument by jumping right into your thesis statement. Start your introduction with a sentence or two to grab the reader's attention.  Then, make sure that you orient the reader by introducing the central problem or question that will be driving your essay and by introducing the key texts that you will be using to help answer that question. Otherwise, your audience will be disoriented.

            </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Title')">More Descriptive Title Needed</button>

            <span class="tooltiptext">

                <textarea id="Title"> You need a more descriptive title.  A good title both catches the reader's attention and helps them figure out whether the content of your essay is something they are interested in reading.  Otherwise, how will your intended audience know whether they want to read your essay or not?

            </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('No Thesis')">No Thesis</button> <span class="tooltiptext">

                <textarea id="No Thesis"> Your paper must articulate a central argument (thesis) that controls the rest of the paper, focuses your essay, and begins to specify your reasoning.  It is not clear what your thesis is. </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Vague Thesis)">Vague Thesis</button> <span class="tooltiptext">

                <textarea id="Vague Thesis"> Your thesis is too vague.  A good thesis statement should summarize your reasoning for why you are holding to the position you have chosen.  One useful way to generate a thesis statement is by using the Topics of Invention.  For more information on the Topics of Invention, see the following website

                http://rhetoric.byu.edu/Canons/Invention/topics_of_invention/topics.htm

            </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Synthesize Thesis')">Synthesize Your Thesis</button> <span class="tooltiptext">

                <textarea id="Synthezise Thesis"> Your thesis statement is a list of the things you are going to argue for in the body.  This is okay, but not ideal.  Can you find the common elements of your subarguments and synthesize them to come up with a more focused overall argument?</textarea>

            </span>

        </span>

 

    </div>

 

    <button id="supportbutton" class="hide" onclick="hide('support')">Support and Analysis</button>

    <div id="support">

 

        <span class="tooltip">

            <button onclick="copy('Dropped Quote')">Dropped Quote</button> <span class="tooltiptext">

                <textarea id="Dropped Quote"> This is what is known as a "dropped quotation".  In short, this is a quotation that is not well integrated into your essay because you have failed to give the reader adequate information about its original context.  This is important not only because proper contextualization helps orient the reader to the importance of your evidence, but because the original context can affect the very meaning of the evidence you are choosing to deploy.  All evidence should be prefaced by as much context as is necessary for the reader to understand the evidence cited (at the very least, this should always include who the speaker is)

            </textarea>

            </span>

        </span>

 

        <br />

        <span class="tooltip">

            <button onclick="copy('No Evidence')">Support For Claim Needed</button> <span class="tooltiptext">

                <textarea id="No Evidence">This is an interesting claim, but you can't assume that your reader will simply agree with all your claims.  To be persuasive, claims need to be supported with evidence.  Do you have any specific evidence (from the text or elsewhere) that would help prove that your claim is true?

                </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Cite Evidence')">Uncited Supporting Evidence</button> <span class="tooltiptext">

                <textarea id="Cite Evidence"> You must use parenthetical references to cite the source of any evidence, even if the evidence is a paraphrase and not a direct quotation. For info on how see https://owl.english.purdue.edu/owl/resource/747/02/ If you do not cite your sources, your audience will not be able to find and check the evidence that you used for themselves, and will thus be less likely to accept it.</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('More Analysis')">Not Enough Analysis</button> <span class="tooltiptext">

                <textarea id="More Analysis"> This part of the paragraph needs more analysis. Don't move on to the next point until you've adequately explained the evidence you introduce.  What does it mean in the context of your argument?  Why is it important?  How does it relate to other important concepts?

            </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Misused Evidence')">Doesn't follow</button> <span class="tooltiptext">

                <textarea id="Misused Evidence"> It is not clear how the claims that you have made follow from the evidence that you've presented here.</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Warrant')">Warrant</button> <span class="tooltiptext">

                <textarea id="Warrant"> Each evidentiary paragraph (every paragraph that is serving to build your own argument), should have a warrant, which is a sentence that demonstrates how the evidence cited supports your thesis. The following website has some good examples of how to write a warrant.  https://owl.purdue.edu/owl/general_writing/academic_writing/establishing_arguments/organizing_your_argument.html </textarea>

            </span>

        </span>

        <br />

 

    </div>

 

 

    <button id="organizationbutton" class="hide" onclick="hide('Organization')">Organization</button>

    <div id="Organization">

        <span class="tooltip">

            <button onclick="copy('No Topic Sentence')">No Topic Sentence</button> <span class="tooltiptext">

                <textarea id="No Topic Sentence"> In a persuasive essay, there are different types of paragraphs that do different things. This one looks like an evidentiary paragraph, a paragraph that is supporting your thesis by making a subargument and using evidence to support it. Evidentiary paragraphs should articulate the subargument as a topic sentence, which should function as a sort of mini-thesis for just the paragraph. What is the topic sentence here?</textarea>

            </span>

        </span>

        <br />

 

        <span class="tooltip">

            <button onclick="copy('Break Paragraph')">Break Paragraph</button> <span class="tooltiptext">

                <textarea id="Break Paragraph"> This looks like the start of a new subargument.

               When you change topics like this, you should break paragraph and start a new one.  In general, paragraphs are used to help your reader keep track of your arguments.  One good rule of thumb is: one paragraph for each distinct idea or subargument.</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Flow')">Flow</button> <span class="tooltiptext">

                <textarea id="Flow"> This is an abrupt topic change. Make sure that all the ideas in your paper flow together logically. Otherwise, make sure to signal topic changes with clear indicating words. (However, On the other hand, etc)</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Incomplete Paragraph')">Incomplete Paragraph</button> <span class="tooltiptext">

                <textarea id="Incomplete Paragraph"> This is not a complete paragraph. Complete paragraphs in a persuasive essay have a topic sentence, context, evidence (normally with quotations), analysis, and a warrant (sentence that links the evidence given to the thesis of the essay).</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('No Paragraphs')">No paragraphs</button> <span class="tooltiptext">

                <textarea id="No Paragraphs"> You need to structure your paper with paragraphs. For help on how and why to use paragraphs, see https://owl.purdue.edu/owl/general_writing/academic_writing/paragraphs_and_paragraphing/index.html</textarea>

            </span>

        </span>

    </div>

 

 

 

 

    <button id="claritybutton" class="hide" onclick="hide('clarity')">Clarity</button>

 

    <div id="clarity">

        <span class="tooltip">

            <button onclick="copy('Dangling Modifier')">Dangling Modifier</button> <span class="tooltiptext">

                <textarea id="Dangling Modifier"> This is a dangling modifier. A modifier is a word or phrase that describes, clarifies, or gives more detail about a concept. When it refers to a word that is not included in the sentence, your audience doesn't know what it is describing. In this case, '' modifies '' , which is not in the sentence.</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Read Aloud')">Read Aloud</button> <span class="tooltiptext">

                <textarea id="Read Aloud"> At some stage of proofreading, you should read your paper aloud to yourself. This will help you catch unclear sentence structure and phrasing.</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Sentence Fragment')">Sentence Fragment</button> <span class="tooltiptext">

                <textarea id="Sentence Fragment"> This is not a complete sentence.  To be a complete sentence, you need a subject and a predicate. You need to make sure that your sentence is not just a dependent clause. </textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Usage')">Usage</button> <span class="tooltiptext">

                <textarea id="Usage"> It appears that you may have used this word incorrectly.  What do you mean by " " here?</textarea>

            </span>

        </span>

 

        <br />

        <span class="tooltip">

            <button onclick="copy('Active Voice')">Active Voice</button> <span class="tooltiptext">

                <textarea id="Active Voice"> This is a good example of a place in which you'd want to use active voice.

                Identify the real "doer" in the sentence and make that the subject. Then identify what the doer is really doing and make that the verb.  That way your reader will know who exactly is doing what in the sentence and what exactly is being done</textarea>

            </span>

        </span>

    </div>

 

    <button id="mechanicsbutton" class="hide" onclick="hide('mechanics')">Mechanics</button>

 

    <div id="mechanics">

 

 

 

 

        <span class="tooltip">

            <button onclick="copy('Comma Intro')">Long Introductory Phrase</button> <span class="tooltiptext">

                <textarea id="Comma Intro"> Use a comma to set off a long introductory phrase or if/then statement.  Normally if the phrase is five or more words, you use a comma to set it off.</textarea>

            </span>

        </span>

 

        <br />

        <span class="tooltip">

            <button onclick="copy('Periods after parenthesis')">Period after parenthesis</button><span class="tooltiptext">

                <textarea id="Periods after parenthesis">Put the period after the comma when you make a parenthetical citation"</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Restrictive Clause')">Restrictive Clause</button> <span class="tooltiptext">

                <textarea id="Restrictive Clause"> No commas because this is a restrictive clause (“ ” restricts the possible meaning of “”)</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Non-Restrictive Clause)">Non-Restrictive Clause</button> <span class="tooltiptext">

                <textarea id="Non-Restrictive Clause"> Comma because it is a non-restrictive clause (“ ” doesn’t restrict the possible meaning of ” ”)</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Comsma Independent')">Comma to link Indep. Clause</button> <span class="tooltiptext">

                <textarea id="Comma Independent"> Use a comma to separate independent clauses (clauses that form a complete sentence) linked by a conjunction (and, or, but).</textarea>

            </span>

        </span>

        <br />

        <span class="tooltip">

            <button onclick="copy('Semi-Colon')">Semi-Colon</button> <span class="tooltiptext">

                <textarea id="Semi-Colon"> Use a semicolon to separate independent clauses (clauses that form a complete sentence) that are not linked by a conjunction (and, or, but)</textarea>

            </span>

        </span>

 

    </div>

 

 

    <button id="wcbutton" class="hide" onclick="hide('wc')">Works Cited</button>

  

    <div id="wc">

    <span class="tooltip">

        <button onclick="copy('Workscited')">Works Cited Page Missing</button> <span class="tooltiptext">

            <textarea id="Workscited"> You must include a Works Cited Page. For examples on how to do this, please see https://owl.purdue.edu/owl/research_and_citation/resources.html </textarea>

        </span>

    </span>

        <br />

    <span class="tooltip">

        <button onclick="copy('WFA')">Use Work from an anthology format.</button> <span class="tooltiptext">

            <textarea id="WFA">Use Works from an Anthology for this type of entry</textarea>

        </span>

    </span>

        <br />

    <span class="tooltip">

        <button onclick="copy('HI')">Hanging Indent.</button> <span class="tooltiptext">

                                                                  <textarea id="HI">Use hanging indents for your works cited page. The first line in each entry is flush to the left. Subsequent lines are tabbed. This is so that your reader can easily scan down the list and match parenthetical references to their corresponding entry in the Works Cited page.</textarea>

 

        </span>

        </span>

 

        </div>

        </div>

   

 

 

            <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

            <script>

                function copy(x) {

                    console.log(x);

                    var copyText = document.getElementById(x);

                    console.log(copyText);

                    copyText.select();

                    document.execCommand('copy');

 

 

 

                }

                function hide(x) {

                    if ($('#' + x + ":visible").length == 0) {

                        $('#' + x).show();

                    }

                    else {

                        $('#' + x).hide();

                    }

 

 

                }

 

            </script>

 

</body>

 

 

 

</html>
