The Integration-Code Repository holds files for creating a wrapper URL code (Integration Code) for their webchat AI bot application.
The reason I created this was so that I could give my clients an Integration Code branded with my business.

I had too many CNAME records in my angelcitybusiness.com DNS registrar, so I changed the domain to angelcitymarketing, which I don't use anymore.

Example of Integration Code:
<script src="https://www.angelcitymarketing.com/Integration-Code/bot-10830.js"></script>

Which was changed from Aminos.ai's code of:
<script src="https://app.aminos.ai/js/chat_plugin_ghl.js" data-bot-id="10830"></script>

Lastly, I used a tool called Obfuscator.io to make my code illegible if someone tried to go to the URL in the Integration Code I give them and reverse engineer it. Here is the original code:

/*

// bot-10830.js

(function() {

    // Load the chat plugin
    
    var script = document.createElement('script');
    script.src = 'https://app.aminos.ai/js/chat_plugin_ghl.js'; // Original script source
    script.setAttribute('data-bot-id', '10830'); // Setting the bot ID
    document.head.appendChild(script);

    // Add custom CSS styling
    var css = `div.talktext p {
        color: black !important;
        font-family: sans-serif !important;
    }`;
    var style = document.createElement('style');
    if (style.styleSheet) {
        style.styleSheet.cssText = css;
    } else {
        style.appendChild(document.createTextNode(css));
    }
    document.head.appendChild(style);

    //PUT NEW INTEGRATION CODE IN COMMENT BELOW!!!

    //************************************************
    //NEW INTEGRATION CODE: <script src="https://www.angelcitymarketing.com/bot-10830.js"></script>
    //************************************************

    // Optionally, add any additional JavaScript code here
})();

*/
