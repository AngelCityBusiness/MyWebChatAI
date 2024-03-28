The MyWebChatAI Repository holds files for creating a wrapper URL code (Integration Code) for their webchat AI bot application.
It also houses the custom domain www.mywebchatai.com, where I use as a proxy website to show businesses what the webchat bot could look like for their business.

The reason I created this was so that I could give my clients an Integration Code branded with my business in addition to showing them what a webchat ai bot would look like on their website.

Example of Integration Code:
<script src="https://www.mywebchatai.com/bot-17772.js"></script>

Which was changed from Aminos.ai's code of:
<script src="https://app.aminos.ai/js/chat_plugin.js" data-bot-id="10830"></script>



Instructions to Create Custom AI Chatbot quickly:
1. After reaching out to a business and getting confirmation they want to trial the chatbot, Go to browse.ai.
2. Sign in and go to "Robots". Find the "Extract DuckDuckGo Search Results" Robot.
3. Click Run Task.
4. For the search bar, put in "site:[root domain of business]" then select how ever many results you want (10-15 should be sufficient).
5. Go to https://docs.google.com/spreadsheets/d/1x_BWpouZlIjM1njJRRMuHQJdxqMI1KG3Tswgm4-QTx0/edit#gid=0 and find the latest URL results—hightlight and copy them.
6. Go to ChatGPT and find the Business Context for AI Chatbot (BCAC) GPT I created and paste all the URLs into the chat box and press Enter.
7. Copy the business context produced.
8. Go to Aminos and find the mywebchatai.com bot.
9. Go to Flow Builer and input new business name and context into "Switching to AI" block.
10. Save and go to AI Mode in the left-hand column and paste the business context and enter the business name. DO NOT ENABLE AI MODE. Nothing else should have to be changed.
11. Now come here, to GitHub, to this MyWebChatAI repository.
12. Go to the index.html and simply change the iframe website to the website of the business.
13. Wait a minute and test it at www.mywebchatai.com.
