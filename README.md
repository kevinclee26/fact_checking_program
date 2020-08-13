# fact_checking_program

Ratings
* False - the primary claim(s) of the content are factually inaccurate. 
* Partly False - the claim(S) of the content are a mix of accurate and inaccurate, or the primary claim is misleading or incomplete. 
* False Headline - the primary claim(s) of the article body content are true, but the primary claim within the headline is factually inaccurate. 
* True - fact-checking partners also rate content to be True
9 ratings total

Action
* Reduced Distribution - show the content lower in News Feed
* Sharing Warning - show a pop-up false content notification so people can decide what to share
* Sharing Notification - show a notification if they had previously shared a story that is later rated false. 
* Misinformation Labels - apply a visual label
* Removing Incentives for Repeat Offenders - when pages or websites repeatedly share content that is rated false, their overall distribution and ability to monetize and advertise will be reduced

Fact-checking websites - impartially verifying rumors, news, and remarks made by politicians but have limited reach
* Snopes
* FactCheck.org
* PolitiFact

Stance detection - an important first step toward identifying disinformation
1. understand the requirements of verifying the veracity of a claim
2. retrieving documents that are relevant to the claim
3. detecting the stance or position of those documents with respect to the claim
4. calculating a reputation score for the document, based on its source and language quality
5. verify the claim based on the information obtained from the relevant documents
this is a different approach that outputs if a document "agrees", "disagrees", or "takes no stance" on a specific claim

ANN types: 
* Recurrent neural network (RNN)
* LSTM models
* multi-layer perceptions
* new approach uses transformers - GPT-2 and Meena. unsupervised learning so does not require the time and labor intensive data-labeling work
