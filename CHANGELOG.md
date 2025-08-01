 # ![ThunderAI icon](images/icon-32px.png "ThunderAI") ThunderAI Release Notes




<h2>Version 3.6.0 - 30/07/2025</h2>
      <ul>
        <li>Now it's possibile to define custom data placeholders to be used in custom prompts [<a href="https://github.com/micz/ThunderAI/issues/156">#156</a>].</li>
        <li>Improved the handling of HTML and line breaks between the email text and the AI Chat.</li>
        <li>When replying, it's now possibile to choose a different reply type (between "all" or "sender only") directly in the AI chat window [<a href="https://github.com/micz/ThunderAI/issues/372">#372</a>].</li>
        <li>Added a new default prompt for replying to emails, which asks for a custom command each time it's used [<a href="https://github.com/micz/ThunderAI/issues/444">#444</a>].</li>
        <li><i>[All APIs]</i> Added an option to choose to exclude a tag only with an exact match in the excluded words list [<a href="https://github.com/micz/ThunderAI/issues/395">#395</a>].</li>
        <li><i>[OpenAI API]</i> Added an option to enable the OpenAI storage for API requests [<a href="https://github.com/micz/ThunderAI/issues/406">#406</a>].</li>
        <li><i>[OpenAI API]</i> In the AI chat page, the initial configuration now also displays the storage setting and the "Developer Messages" [<a href="https://github.com/micz/ThunderAI/issues/430">#430</a>].</li>
        <li><i>[Ollama API]</i> Added an option to enable the thinking feature [<a href="https://github.com/micz/ThunderAI/issues/398">#398</a>].</li>
        <li><i>[Google Gemini API]</i> In the AI chat page, the initial configuration now also displays the "System Instructions". [<a href="https://github.com/micz/ThunderAI/issues/429">#429</a>].</li>
        <li><i>[OpenAI Comp API]</i> Handling responses without choices when using RAG [<a href="https://github.com/micz/ThunderAI/issues/416">#416</a>].</li>
        <li><i>[OpenAI Comp API]</i> Added Perplexity configuration [<a href="https://github.com/micz/ThunderAI/issues/405">#405</a>].</li>
        <li><i>[OpenAI Comp API]</i> Added OpenRouter configuration [<a href="https://github.com/micz/ThunderAI/issues/401">#401</a>].</li>
        <li>Traditional Chinese (zh_Hant) translation added, thanks to <a href="https://github.com/evez">evez</a>.</li>
        <li>Russian (ru) translation added, thanks to <a href="https://hosted.weblate.org/user/law820314/">Maksim</a>.</li>
        <li>Some English typing errors have been fixed [<a href="https://github.com/micz/ThunderAI/issues/422">#422</a>].</li>
      </ul>
<h2>Version 3.5.5 - 21/07/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Fix: Autotag and Antispam filter working again [<a href="https://github.com/micz/ThunderAI/issues/449">#449</a>].</li>
      </ul>
<h2>Version 3.5.4 - 13/06/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Fix: Changed again how to detect when the response is completed.</li>
        <li><i>[ChatGPT Web]</i> Fix: Auto scroll to bottom works again.</li>
      </ul>
<h2>Version 3.5.3 - 10/06/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Fix: Correctly detecting when the response is completed.</li>
      </ul>
<h2>Version 3.5.2 - 05/06/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Fix: Correctly hiding the model warning message when forcing to send the prompt [<a href="https://github.com/micz/ThunderAI/issues/410">#410</a>].</li>
        <li><i>[ChatGPT Web]</i> Fix: ThunderAI is now working also with a free account [<a href="https://github.com/micz/ThunderAI/issues/408">#408</a>].</li>
        <li><i>[ChatGPT Web]</i> Fix: Correctly showing a warning message to a not logged in user [<a href="https://github.com/micz/ThunderAI/issues/411">#411</a>].</li>
        <li><i>[ChatGPT Web]</i> Improved the model not found message [<a href="https://github.com/micz/ThunderAI/issues/413">#413</a>].</li>
        <li><i>[All APIs]</i> Fix: The selection info message in the API WebChat is shown only when needed [<a href="https://github.com/micz/ThunderAI/issues/412">#412</a>].</li>
        <li>Czech (cs) translation updated, thanks to <a href="https://hosted.weblate.org/user/jaroush/">Jaroslav Staněk</a>.</li>
      </ul>
<h2>Version 3.5.1 - 31/05/2025</h2>
      <ul>
        <li>Fix: correctly saving text options [<a href="https://github.com/micz/ThunderAI/issues/400">#400</a>].</li>
      </ul>
<h2>Version 3.5.0 - 30/05/2025</h2>
      <ul>
        <li>Added Anthropic API support [<a href="https://github.com/micz/ThunderAI/issues/349">#349</a>].</li>
        <li>Added the <i>{%selected_html%}</i> placeholder to retrieve the HTML portion of the selected text [<a href="https://github.com/micz/ThunderAI/issues/368">#368</a>].</li>
        <li><i>[OpenAI Comp API]</i> Added a shortcut to select configurations for known AI services. Currently, <i>Grok AI</i> and <i>Mistral AI</i> are available [<a href="https://github.com/micz/ThunderAI/issues/378">#378</a>]. <a href="https://github.com/micz/ThunderAI/issues/new?template=feature_request.md">Open an issue</a> to request additional services.</li>
        <li><i>[All APIs]</i> In the API WebChat is now possibile to select a part of the answer and use only that [<a href="https://github.com/micz/ThunderAI/issues/356">#356</a>].</li>
        <li><i>[All APIs]</i> Setting the "Max prompt length" to zero on the options page will disable the length check when sending a prompt to the AI. [<a href="https://github.com/micz/ThunderAI/issues/380">#380</a>].</li>
        <li><i>[All APIs]</i> Added a button to the options page to reset the 'Max prompt length' value to its default.</li>
        <li><i>[All APIs]</i> Adding tags automatically or with the context menu will now use also tags not created by ThunderAI [<a href="https://github.com/micz/ThunderAI/issues/390">#390</a>].</li>
        <li>Fix: in the Spamfilter page the unsaved changes warning is now correctly shown.</li>
        <li>Fix: The default keyboard shortcut is no longer enforced at every Thunderbird startup [<a href="https://github.com/micz/ThunderAI/issues/384">#384</a>].</li>
        <li>Fix: Incoming email processing now works correctly when auto-tagging is enabled and the full tagging feature is subsequently disabled.</li>
        <li>Fix: The reply type is correctly saved in the options. [<a href="https://github.com/micz/ThunderAI/issues/387">#387</a>].</li>
      </ul>
<h2>Version 3.4.1 - 12/05/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Fix: correctly assigning tags when receiving mails. Thanks to <a href="https://github.com/jdkio">jdkio</a> [<a href="https://github.com/micz/ThunderAI/issues/374">#374</a>].</li>
      </ul>
<h2>Version 3.4.0 - 07/04/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Added a special prompt to get tasks data from emails [<a href="https://github.com/micz/ThunderAI/issues/333">#333</a>]. To use this feature, you must install also the <a href="https://addons.thunderbird.net/it/thunderbird/addon/thunderai-sparks/">Sparks</a> add-on.</li>
        <li><i>[ChatGPT Web]</i> It is now possible to define a Custom GPT or a Project in the options page to be used by default, or directly in a custom prompt to be used only for that prompt [<a href="https://github.com/micz/ThunderAI/issues/168">#168</a>, <a href="https://github.com/micz/ThunderAI/issues/277">#277</a>].</li>
        <li>The chatgpt.com access permission is no more requested when installing the addon. It's mandatory to give this permission to use the ChatGPT Web Interface integration [<a href="https://github.com/micz/ThunderAI/issues/293">#293</a>].</li>
        <li>Added the <i>{%mail_quoted_text%}</i> placeholder to get the quoted text when composing a new message [<a href="https://github.com/micz/ThunderAI/issues/324">#324</a>].</li>
        <li>Fix: correctly choosing the right account when replying [<a href="https://github.com/micz/ThunderAI/issues/369">#369</a>].</li>
        <li>Fix: In the <i>{%mail_typed_text%}</i> placeholder text on different lines is now separated by a space.</li>
        <li>Fix: correctly showing text differences when using {%mail_typed_text%} placeholder.</li>
        <li>Added a default proofread prompt [<a href="https://github.com/micz/ThunderAI/issues/21">#21</a>].</li>
        <li>Added the <i>{%empty%}</i> placeholder to prevent the email body from being automatically appended at the end of the prompt [<a href="https://github.com/micz/ThunderAI/issues/345">#345</a>].</li>
        <li>Added a check for the presence of the correct version of ThunderAI Sparks [<a href="https://github.com/micz/ThunderAI/issues/315">#315</a>].</li>
        <li><i>[All APIs]</i> Improved the form asking for additional text [<a href="https://github.com/micz/ThunderAI/issues/97">#97</a>].</li>
        <li><i>[All APIs]</i> Fix: Ensure HTML body is generated from plain text if no parts are available when processing incoming messages for tags or spam.</li>
        <li>Fix a condition when using a prompt from the compose window with a "Do reply" action that is changed in "Substitute Text" [<a href="https://github.com/micz/ThunderAI/issues/353">#353</a>].</li>
        <li>Custom Prompts form improved.</li>
        <li>Various improvements.</li>
      </ul>
<h2>Version 3.3.5 - 22/04/2025</h2>
      <ul>
        <li>Using a prompt from the compose window with a "Do reply" action is changed in "Substitute Text", asking also to insert text if none is selected [<a href="https://github.com/micz/ThunderAI/issues/353">#353</a>].</li>
        <li>Added an option when composing in plain text to remove the extra empty lines [<a href="https://github.com/micz/ThunderAI/issues/350">#350</a>].</li>
        <li><i>[Ollama API]</i> It's now possibile to define the default context length (the <i>num_ctx</i> parameter) in the options page [<a href="https://github.com/micz/ThunderAI/issues/351">#351</a>].</li>
        <li><i>[ChatGPT Web]</i> Updated the list of available models in the option page.</li>
        <li><i>[ChatGPT Web]</i> Opening the ChatGPT webpage from the options now enforce the selected model, if any.</li>
        <li><i>[All APIs]</i> Fix: Really correctly getting the message body even in multilevel subpart messages when processing incoming messages for tags or spam [<a href="https://github.com/micz/ThunderAI/issues/335">#335</a>].</li>
        <li>Minor improvements.</li>
      </ul>
<h2>Version 3.3.4 - 14/04/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Fixed a blocking error with the " character in the mail text [<a href="https://github.com/micz/ThunderAI/issues/344">#344</a>].</li>
      </ul>
<h2>Version 3.3.3 - 12/04/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Fix: Correctly getting the message body even in multilevel subpart messages when processing incoming messages for tags or spam [<a href="https://github.com/micz/ThunderAI/issues/335">#335</a>].</li>
        <li>Minor improvements.</li>
      </ul>
<h2>Version 3.3.2 - 08/04/2025</h2>
      <ul>
        <li><i>[Ollama API][OpenAI Comp API]</i> Added an info panel to the options page about CORS, along with a button to request the "All URLs" optional permission to avoid potential CORS issues. [<a href="https://github.com/micz/ThunderAI/issues/330">#330</a>, <a href="https://github.com/micz/ThunderAI/issues/331">#331</a>]. Thanks to <a href="https://github.com/jobisoft">John Bieling</a> for the hint.</li>
      </ul>
<h2>Version 3.3.1 - 06/04/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> The "Show diff" button is now shown only when correctly set up [<a href="https://github.com/micz/ThunderAI/issues/321">#321</a>].</li>
        <li><i>[ChatGPT Web]</i> The additional text field is now focused [<a href="https://github.com/micz/ThunderAI/issues/323">#323</a>].</li>
        <li>Added a warning in the options page for linux users [<a href="https://github.com/micz/ThunderAI/issues/318">#318</a>].</li>
        <li><i>[All APIs]</i> Fix: Correctly not showing the "Add tags menu" soon after installation if the option is not checked [<a href="https://github.com/micz/ThunderAI/issues/329">#329</a>].</li>
        <li>Czech (cs) translation updated, thanks to <a href="https://hosted.weblate.org/user/jaroush/">Jaroslav Staněk</a>.</li>
      </ul>
<h2>Version 3.3.0 - 31/03/2025</h2>
      <ul>
        <li>Added the <i>{%mail_folder_name%}</i> placeholder to get the mail folder name [<a href="https://github.com/micz/ThunderAI/issues/253">#253</a>].</li>
        <li>Added the <i>{%mail_folder_path%}</i> placeholder to get the mail folder path [<a href="https://github.com/micz/ThunderAI/issues/253">#253</a>].</li>
        <li>Added the <i>{%account_email_address%}</i> placeholder to get the current account mail address [<a href="https://github.com/micz/ThunderAI/issues/272">#272</a>].</li>
        <li><i>[ChatGPT Web][All APIs]</i> Added a diff viewer to compare the old and new text. This feature could be activated at prompt level, and it's useful for "rewrite" prompts [<a href="https://github.com/micz/ThunderAI/issues/109">#109</a>].</li>
        <li><i>[All APIs]</i> Added a context menu to automatically add tags and run the spam filter on selected messages. [<a href="https://github.com/micz/ThunderAI/issues/262">#262</a>].</li>
        <li><i>[All APIs]</i> It's now possibile to define a timezone in the calendar event settings page [<a href="https://github.com/micz/ThunderAI/issues/250">#250</a>].</li>
        <li><i>[All APIs]</i> It's now possibile to add the attendees in the calendar event, be sure to update the prompt in the settings [<a href="https://github.com/micz/ThunderAI/issues/258">#258</a>].</li>
        <li>The button icon now shows a loading indicator when ThunderAI is performing an operation [<a href="https://github.com/micz/ThunderAI/issues/295">#295</a>].</li>
        <li>Improved the handling of null or undefined placeholders [<a href="https://github.com/micz/ThunderAI/issues/288">#288</a>].</li>
        <li>Czech (cs) translation added, thanks to <a href="https://hosted.weblate.org/user/jaroush/">Jaroslav Staněk</a> and <a href="https://hosted.weblate.org/user/Fjuro/">Fjuro</a>.</li>
        <li>Simplified Chinese (zh_Hans) translation added, thanks to <a href="https://github.com/jeklau">jeklau</a>.</li>
        <li>Some old strings are now translated in the API webchat [<a href="https://github.com/micz/ThunderAI/issues/298">#298</a>].</li>
      </ul>
<h2>Version 3.2.3 - 06/03/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Fixed hiding the Spam Filter options [<a href="https://github.com/micz/ThunderAI/issues/284">#284</a>].</li>
        <li>Unchecking the "Add tags" and "Spam Filter" options if the user revokes the related optional permissions [<a href="https://github.com/micz/ThunderAI/issues/286">#286</a>].</li>
        <li>The permission to 'List message tags' is now mandatory; otherwise, the tags-related placeholder won't be usable. The permission to modify tags is optional and required to tag emails.</li>
        <li>Various improvements.</li>
      </ul>
<h2>Version 3.2.2 - 05/03/2025</h2>
      <ul>
        <li>Fixed compatibility with Thunderbird 115 [<a href="https://github.com/micz/ThunderAI/issues/281">#281</a>].</li>
        <li>Fixed a bug with the optional permissions not retained at startup [<a href="https://github.com/micz/ThunderAI/issues/279">#279</a>]</li>
        <li>Fixed a race condition in saving the report data of the Spam Filter.</li>
      </ul>
<h2>Version 3.2.1 - 03/03/2025</h2>
      <ul>
        <li>Fix calling a prompt without giving tags related permissions [<a href="https://github.com/micz/ThunderAI/issues/275">#275</a>].</li>
        <li>Deactivating the add tags feature if the related permissions are revoked [<a href="https://github.com/micz/ThunderAI/issues/276">#276</a>].</li>
        <li>Minor bugs fixed.</li>
      </ul>
<h2>Version 3.2.0 - 27/02/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Added an option to automatically tag incoming emails [<a href="https://github.com/micz/ThunderAI/issues/237">#237</a>].</li>
        <li><i>[All APIs]</i> Added an configurable antispam filter for incoming emails [<a href="https://github.com/micz/ThunderAI/issues/231">#231</a>].</li>
        <li>Tags related permissions are now optional and asked for only when the user activates the tags feature [<a href="https://github.com/micz/ThunderAI/issues/259">#259</a>].</li>
        <li>Added the <i>{%thunderai_def_sign%}</i> placeholder to get the default signature as defined in the options [<a href="https://github.com/micz/ThunderAI/issues/248">#248</a>].</li>
        <li>Added the <i>{%thunderai_def_lang%}</i> placeholder to get the default language as defined in the options [<a href="https://github.com/micz/ThunderAI/issues/248">#248</a>].</li>
        <li>Croatian (hr) translation added, thanks to Petar Jedvaj.</li>
        <li>German (de) translation errors fixed.</li>
        <li>Translations improved thanks to Hosted Weblate. <a href="https://micz.it/thunderbird-addon-thunderai/translate/">Help translating ThunderAI!</a>.</li>
        <li>Various minor improvements.</li>
      </ul>
<h2>Version 3.1.3 - 02/02/2025</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Correctly hiding the "Download Sparks" message when using [<a href="https://github.com/micz/ThunderAI/issues/245">#245</a>].</li>
        <li><i>[ChatGPT Web]</i> Added support to autochoose the new <i>o1</i>, <i>o3-mini</i> and <i>o3-mini-high</i> models [<a href="https://github.com/micz/ThunderAI/issues/244">#244</a>].</li>
      </ul>
<h2>Version 3.1.2 - 29/01/2025</h2>
      <ul>
        <li>Forcing ThunderAI menu reload when installing Sparks [<a href="https://github.com/micz/ThunderAI/issues/240">#240</a>].</li>
        <li>Fixed a bug in translating special prompts.</li>
      </ul>
<h2>Version 3.1.1 - 29/01/2025</h2>
      <ul>
        <li>Polish (pl) translation improved, thanks to <a href="https://github.com/neexpl">neexpl</a>.</li>
        <li>Fixed the text in the add calendar event settings page.</li>
      </ul>
<h2>Version 3.1.0 - 27/01/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Added a special prompt to get calendar events data from emails [<a href="https://github.com/micz/ThunderAI/issues/182">#182</a>]. To use this feature, you must install also the <a href="https://addons.thunderbird.net/it/thunderbird/addon/thunderai-sparks/">Sparks</a> add-on.</li>
        <li>Added Google Gemini API support [<a href="https://github.com/micz/ThunderAI/issues/204">#204</a>, <a href="https://github.com/micz/ThunderAI/issues/217">#217</a>].</li>
        <li>Added the <i>{%mail_typed_text%}</i> placeholder to get the text inserted before the quoted mail body when replying [<a href="https://github.com/micz/ThunderAI/issues/196">#196</a>].</li>
        <li>Using the <i>{%mail_typed_text%}</i> placeholder the typed text inserted before the quoted mail body will be selected automatically to be replaced afterwards with the AI response [<a href="https://github.com/micz/ThunderAI/issues/229">#229</a>].</li>
        <li>Added the <i>{%mail_datetime%}</i> placeholder to get the date and time of the email [<a href="https://github.com/micz/ThunderAI/issues/223">#223</a>].</li>
        <li>Added the <i>{%current_datetime%}</i> data placeholder to get the current date and time [<a href="https://github.com/micz/ThunderAI/issues/224">#224</a>].</li>
        <li>Added an info text about using the new <i>{%tags_full_list%}</i> placeholder in the "Add Tags Prompt" page [<a href="https://github.com/micz/ThunderAI/issues/215">#215</a>].</li>
      </ul>
<h2>Version 3.0.0 - 05/01/2025</h2>
      <ul>
        <li><i>[All APIs]</i> Added a special prompt to apply tags to emails [<a href="https://github.com/micz/ThunderAI/issues/183">#183</a>].</li>
        <li>Default prompts text has been translated [<a href="https://github.com/micz/ThunderAI/issues/185">#185</a>].</li>
        <li>Added the <i>{%tags_full_list%}</i> data placeholder for the full available tags list added [<a href="https://github.com/micz/ThunderAI/issues/197">#197</a>].</li>
        <li>Added the <i>{%tags_current_email%}</i> data placeholder for the single mail tags list added [<a href="https://github.com/micz/ThunderAI/issues/198">#198</a>].</li>
        <li>User <a href="https://forms.gle/1qK2wcbuhaRzhwyt9">survey link</a> added [<a href="https://github.com/micz/ThunderAI/issues/202">#202</a>].</li>
        <li><i>[OpenAI Comp API]</i> Added a button in the options page to manually insert the model [<a href="https://github.com/micz/ThunderAI/issues/205">#205</a>].</li>
        <li>Polish (pl) translation added, thanks to <a href="https://github.com/neexpl">neexpl</a>.</li>
        <li>The Custom Prompts tab has now an icon.</li>
        <li>The red border in the Custom Prompts configuration page that highlights a needed prompt configuration that is not selected is now removed when the corresponding placeholder is removed [<a href="https://github.com/micz/ThunderAI/issues/201">#201</a>].</li>
        <li>Minor bugs fixed.</li>
      </ul>
<h2>Version 2.3.4 - 06/12/2024</h2>
      <ul>
        <li><i>[ChatGPT API]</i> Correctly showwing an error message received from the ChatGPT API [<a href="https://github.com/micz/ThunderAI/issues/191">#191</a>].</li>
      </ul>
<h2>Version 2.3.3 - 29/11/2024</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Correctly sending the prompt even if the audio button is present on the web interface [<a href="https://github.com/micz/ThunderAI/issues/188">#188</a>].</li>
        <li><i>[ChatGPT Web]</i> The input field is always visibile [<a href="https://github.com/micz/ThunderAI/issues/189">#189</a>].</li>
      </ul>
<h2>Version 2.3.2 - 31/10/2024</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Clicking on one of the allowed model values in the options page, sets the corresponding field value.</li>
        <li><i>[ChatGPT Web]</i> Debug log improved.</li>
        <li><i>[ChatGPT Web]</i> Improved the default value for model enforcing [<a href="https://github.com/micz/ThunderAI/issues/176">#176</a>].</li>
      </ul>
<h2>Version 2.3.1 - 24/10/2024</h2>
      <ul>
        <li>Reverted the position of the action button in the compose window [<a href="https://github.com/micz/ThunderAI/issues/175">#175</a>].</li>
      </ul>
<h2>Version 2.3.0 - 23/10/2024</h2>
      <ul>
        <li>The action button in the compose window has been moved to the formatting toolbar [<a href="https://github.com/micz/ThunderAI/issues/173">#173</a>].</li>
        <li>On the custom prompts page, when editing a prompt, pressing the cancel button will revert any modified values in the form to their saved state.</li>
        <li>Implemented placeholders to add additional data to prompts [<a href="https://micz.it/thunderbird-addon-thunderai/data-placeholders/">More info</a>] [<a href="https://github.com/micz/ThunderAI/issues/146">#146</a>, <a href="https://github.com/micz/ThunderAI/issues/153">#153</a>].</li>
        <li>Text improved for the "Reply to this" prompt.</li>
        <li>Added an option to set the maximum number of characters in the prompt [<a href="https://github.com/micz/ThunderAI/issues/165">#165</a>].</li>
        <li>Added a workaround to show an alert message when needed [<a href="https://github.com/micz/ThunderAI/issues/166">#166</a>].</li>
        <li><i>[ChatGPT Web]</i> Added an option to set the model to use [<a href="https://github.com/micz/ThunderAI/issues/171">#171</a>].</li>
        <li><i>[ChatGPT Web]</i> Added an option to use the temporary chat [<a href="https://github.com/micz/ThunderAI/issues/169">#169</a>].</li>
        <li>A few typos fixed [<a href="https://github.com/micz/ThunderAI/issues/170">#170</a>].</li>
        <li>Added a loading indicator in the menu when sending a prompt.</li>
        <li>Added a new default prompt that uses the placeholders and allows replying to an email thread. It requires selecting the text of the first email to identify which is the one to reply to and the others in the thread [<a href="https://github.com/micz/ThunderAI/issues/150">#150</a>].</li>
     </ul>
<h2>Version 2.2.2 - 15/10/2024</h2>
      <ul>
        <li>APIs error handling improved.</li>
        <li><i>[OpenAI Comp API]</i> Added an option to remove the <i>v1</i> segment in the API calls path [<a href="https://github.com/micz/ThunderAI/issues/161">#161</a>].</li>
      </ul>
<h2>Version 2.2.1 - 11/10/2024</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Added a workaround to login in ChatGPT. See the new button in the options page.</li>
        <li>Brazilian Portuguese (pt-br) translation updated, thanks to Bruno Pereira de Souza.</li>
      </ul>
<h2>Version 2.2.0 - 07/10/2024</h2>
    <ul>
      <li><i>[ChatGPT Web]</i> Removed the option to force the ChatGPT4 model over ChatGPT3.5, since it was useless now.</li>
      <li><i>[ChatGPT Web]</i> Minor internal improvements.</li>
      <li><i>[OpenAI Comp API]</i> Added a new integration method to use a local LLM via an API compatible with OpenAI's API specifications [<a href="https://github.com/micz/ThunderAI/issues/126">#126</a>].</li>
      <li>Custom Prompts storage space incremented to 5MB, using <i>storage.local</i>. Added also the total occupied space at the bottom of the Custom Prompts page [<a href="https://github.com/micz/ThunderAI/issues/129">#129</a>].</li>
      <li><i>[ChatGPT Web]</i> Updated the information in the option page.</li>
      <li>A new dynamic menu for selecting prompts has been added. In addition to clicking the ThunderAI button, you can now use the CTRL+ALT+A keyboard shortcut [<a href="https://micz.it/thunderbird-addon-thunderai/dynamic-menu/">More info</a>] [<a href="https://github.com/micz/ThunderAI/issues/130">#130</a>].</li>
      <li>Added an option to order alphabetically the prompts in the menu.</li>
      <li>Allow 0 as the dimensions for the chat window in the options page to prevent issues, such as those encountered with NixOS/Hyprland [<a href="https://github.com/micz/ThunderAI/issues/137">#137</a>].</li>
      <li>Is now possible to ask for additional text before sending the prompts also for default prompts [<a href="https://github.com/micz/ThunderAI/issues/135">#135</a>].</li>
      <li>Fixed a bug that occurred when importing prompts after an export without closing the Custom Prompts page.</li>
      <li>Brazilian Portuguese (pt-br) translation added, thanks to Bruno Pereira de Souza.</li>
      <li><i>[Ollama API]</i> Added a link to the <a href="https://micz.it/thunderbird-addon-thunderai/ollama-cors-information/">CORS information page</a>.</li>
      <li><i>[All APIs]</i> Improved handling of streaming responses even in case of broken chunks [<a href="https://github.com/micz/ThunderAI/issues/147">#147</a>].</li>
      <li>Fixed a race condition that occurred when opening the chat window under certain circumstances. Thanks to <a href="https://github.com/jobisoft" target="_blank">@jobisoft</a> for helping refine the code, and to <a href="https://github.com/Mikilio" target="_blank">@Mikilio</a> and <a href="https://github.com/mattcaron" target="_blank">@mattcaron</a> for the extensive testing [<a href="https://github.com/micz/ThunderAI/issues/143">#143</a>].</li>
    </ul>
<h2>Version 2.1.5 - 23/09/2024</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Working again in Thunderbird 115. Implemented a workaround for <i>Intl.Segmenter</i> [<a href="https://github.com/micz/ThunderAI/issues/139">#139</a>].</li>
      </ul>
<h2>Version 2.1.4 - 11/09/2024</h2>
      <ul>
        <li><i>[ChatGPT API][Ollama API]</i> Fixed the colors of the light theme in the chat window status logger.</li>
        <li><i>[ChatGPT Web]</i> Correctly handling a change in the web interface [<a href="https://github.com/micz/ThunderAI/issues/133">#133</a>].</li>
      </ul>
  <h2>Version 2.1.3 - 04/09/2024</h2>
  <ul>
    <li><i>[ChatGPT Web]</i> Removed a link to the status page in an error message as requested by Thunderbird Addon Reviewer. Reverted [<a href="https://github.com/micz/ThunderAI/issues/123">#123</a>].</li>
  </ul>
<h2>Version 2.1.2 - 04/09/2024</h2>
  <ul>
    <li><i>[ChatGPT Web]</i> The URL in the prompt sending error message is now correctly clickable [<a href="https://github.com/micz/ThunderAI/issues/123">#123</a>].</li>
    <li><i>[ChatGPT Web]</i> If the web interface loads slowly, a button is now shown to retry sending the prompt [<a href="https://github.com/micz/ThunderAI/issues/122">#122</a>].</li>
    <li><i>[ChatGPT Web]</i> Improved the methods to open the ChatGPT window and interact with it.</li>
  </ul>
<h2>Version 2.1.1 - 28/08/2024</h2>
  <ul>
    <li><i>[ChatGPT API]</i> Fixed a bug in handling the chat window.</li>
  </ul>
<h2>Version 2.1.0 - 28/08/2024</h2>
  <ul>
    <li><i>[Ollama API]</i> It's now possible to use a local LMM using <a href="https://ollama.com/" target="_blank">Ollama</a> [<a href="https://github.com/micz/ThunderAI/issues/79">#79</a>].</li>
    <li><i>[ChatGPT API][Ollama API]</i> Added a "Stop" button to stop the current elaboration [<a href="https://github.com/micz/ThunderAI/issues/113">#113</a>].
    <li><i>[ChatGPT API]</i> If the configuration is missing the model or the API key, an error message is now provided, and there is no more fallback to the ChatGPT web interface [<a href="https://github.com/micz/ThunderAI/issues/111">#111</a>].</li>
    <li><i>[ChatGPT API][Ollama API]</i> Improved chat colors scheme for darkmode.</li>
    <li><i>[ChatGPT API][Ollama API]</i> Added a status message to give feedback to the user about the current operation [<a href="https://github.com/micz/ThunderAI/issues/119">#119</a>].</li>
    <li>Improved the internal messaging system between the background script and the chat windows [<a href="https://github.com/micz/ThunderAI/issues/117">#117</a>].</li>
    <li>Improved error messages for connection errors.</li>
  </ul>
<h2>Version 2.0.7 - 21/08/2024</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> Fixed an issue with automatically sending the prompt.</li>
      </ul>
<h2>Version 2.0.6 - 19/08/2024</h2>
  <ul>
    <li>Some minor improvements.</li>
  </ul>
<h2>Version 2.0.5 - 19/08/2024</h2>
  <ul>
    <li><i>[ChatGPT Web]</i> Modified the permissions for the ChatGPT web interface, now requiring only the <code>https://*.chatgpt.com/*</code> and not all sites.</li>
    <li><i>[ChatGPT Web]</i> Fixed a problem loading the web interface on Thunderbird 115 under some circumstances.</li>
  </ul>
<h2>Version 2.0.4 - 16/08/2024</h2>
      <ul>
        <li><i>[ChatGPT API]</i> Fixed the vertical scroolbar with long reponses [<a href="https://github.com/micz/ThunderAI/issues/108">#108</a>].</li>
      </ul>
<h2>Version 2.0.3 - 15/08/2024</h2>
      <ul>
        <li><i>[ChatGPT API]</i> Fixed a loading bug in Thunderbird 128+ [<a href="https://github.com/micz/ThunderAI/issues/107">#107</a>].</li>
      </ul>
<h2>Version 2.0.2 - 15/08/2024</h2>
<ul>
  <li><i>[ChatGPT Web]</i> Now, the ChatGPT response must be selected by the user to be retrieved by ThunderAI. A single click on the text should work, but it's also possible to select the text manually [<a href="https://github.com/micz/ThunderAI/issues/104">#104</a>].</li>
  <li>Added a better error message when there is an error fetching models.</li>
  <li>When selecting a correct model in the options page, the field is no more highlighted in red [<a href="https://github.com/micz/ThunderAI/issues/100">#100</a>].</li>
  <li>When using the ChatGPT API, the double quotes at the beginning and end of the response are removed [<a href="https://github.com/micz/ThunderAI/issues/99">#99</a>].</li>
  <li><i>[ChatGPT Web]</i>"Keep formatting" option removed.</li>
</ul>
<h2>Version 2.0.1 - 09/08/2024</h2>
      <ul>
        <li><i>[ChatGPT Web]</i> No more notifying a missing API Key or model when using the web interface.</li>
      </ul>
<h2>Version 2.0.0 - 30/07/2024</h2>
      <ul>
        <li>Added OpenAI ChatGPT API connection [<a href="https://github.com/micz/ThunderAI/issues/40">#40</a>].</li>
        <li>Information text in the options page improved.</li>
      </ul>
<h2>Version 1.2.1 - 20/07/2024</h2>
      <ul>
        <li>Fixed changes in the ChatGPT web interface when importing in plain text [<a href="https://github.com/micz/ThunderAI/issues/87">#87</a>].</li>
        <li>Added an option to the prompts to specify the default language for the response [<a href="https://github.com/micz/ThunderAI/issues/86">#86</a>].</li>
        <li>Not adding to the prompt the statement about using the default language if asking for a translation [<a href="https://github.com/micz/ThunderAI/issues/85">#85</a>].</li>
        <li><i>[Thunderbird 128+ only]</i> Added a warning message when closing the Custom Prompts page with unsaved changes [<a href="https://github.com/micz/ThunderAI/issues/88">#88</a>].</li>
      </ul>
<h2>Version 1.2.0 - 17/07/2024</h2>
    <ul>
      <li>If no default language is set in the options, the language present in the text sent to ChatGPT will be used [<a href="https://github.com/micz/ThunderAI/issues/53">#53</a>].</li>
        <li>Added the functionality to import and export custom prompts [<a href="https://github.com/micz/ThunderAI/issues/65">#65</a>].</li>
        <li>Showing the currently used prompt name in the ChatGPT window [<a href="https://github.com/micz/ThunderAI/issues/20">#20</a>].</li>
    </ul>
<h2>Version 1.1.4 - 28/06/2024</h2>
    <ul>
        <li>Added an option to import text with formatting from ChatGPT, set to false by default [<a href="https://github.com/micz/ThunderAI/issues/70">#70</a>], [<a href="https://github.com/micz/ThunderAI/issues/77">#77</a>].</li>
        <li>Improve the message warning to choose the right model [<a href="https://github.com/micz/ThunderAI/issues/76">#76</a>].</li>
        <li>Added a description in the Custom Prompts page about default prompts [<a href="https://github.com/micz/ThunderAI/issues/74">#74</a>].</li>
        <li>Added a link to the <a href="https://micz.it/thunderbird-addon-thunderai/translate/">translate page</a> in the options window [<a href="https://github.com/micz/ThunderAI/issues/68">#68</a>].</li>
      </ul>

<h2>Version 1.1.3 - 18/06/2024</h2>
  <ul>
    <li>Fixed a bug in replying to a message [<a href="https://github.com/micz/ThunderAI/issues/71">#71</a>].</li>
  </ul>

<h2>Version 1.1.2 - 23/05/2024</h2>
  <ul>
    <li>Minor improvements.</li>
  </ul>


<h2>Version 1.1.1 - 22/05/2024</h2>
  <ul>
    <li>Improved handling of CSS in the ChatGPT web interface.</li>
  </ul>

<h2>Version 1.1.0 - 21/05/2024</h2>
  <ul>
    <li>A prompt can be configured to request additional text from the user.</li>
    <li>Added custom prompts. See more info <a href="https://micz.it/thunderbird-addon-thunderai/custom-prompts/">here</a>.</li>
    <li>Dark mode added.</li>
    <li>Added some error messages to handle potential changes in the ChatGPT web interface.</li>
    <li>German translation added.</li>
    <li>French translation added.</li>
    <li>Log messages improved.</li>
  </ul>

<h2>Version 1.0.10 - 17/05/2024</h2>
  <ul>
    <li>Now using the new URL chatgpt.com.</li>
    <li>More improvements in handling the ChatGPT web interface.</li>
  </ul>

<h2>Version 1.0.9 - 16/05/2024</h2>
  <ul>
    <li>Improved handling of different versions of the ChatGPT web interface.</li>
  </ul>

<h2>Version 1.0.8 - 15/05/2024</h2>
  <ul>
    <li>Fixed changes in the ChatGPT web interface [<a href="https://github.com/micz/ThunderAI/issues/57">#57</a>, <a href="https://github.com/micz/ThunderAI/issues/62">#62</a>].</li>
    <li>Correctly handling the model ChatGPT-4o.</li>
  </ul>

<h2>Version 1.0.7 - 09/05/2024</h2>
<ul>
  <li>Improved the reply prompt to exclude comments and other text beside the mail text.</li>
  <li>Correctly keeping the signature in a reply even if it's above the quoted email [<a href="https://github.com/micz/ThunderAI/issues/45">#45</a>].</li>
</ul>

<h2>Version 1.0.6 - 08/05/2024</h2>
<ul>
  <li>Correctly handling a change in the ChatGPT web interface [<a href="https://github.com/micz/ThunderAI/issues/43">#43</a>].</li>
  <li>Added a button to force the completion to display the 'Use last answer' button if ChatGPT has finished its work but the button has not appeared.</li>
</ul>

<h2>Version 1.0.5 - 03/05/2024</h2>
<ul>
  <li>Fixed the handling of ChatGPT-4 in a large window [<a href="https://github.com/micz/ThunderAI/issues/38">#38</a>].</li>
</ul>

<h2>Version 1.0.4 - 01/05/2024</h2>
<ul>
  <li>Stripping the quotation marks from the response.</li>
  <li>Now it is possible to undo text modifications implemented by ChatGPT (CTRL+Z on Windows) [<a href="https://github.com/micz/ThunderAI/issues/34">#34</a>].</li>
  <li>Now closing the compose window after unsaved text modifications implemented by ChatGPT triggers the usual warning message [<a href="https://github.com/micz/ThunderAI/issues/30">#30</a>].</li>
  <li>Updated the "Important Information" section on the options page, as it is no longer possible to disable the ChatGPT chat history.</li>
</ul>

<h2>Version 1.0.3 - 27/04/2024</h2>
<ul>
  <li>Using the right identity when replying to a message [<a href="https://github.com/micz/ThunderAI/issues/31">#31</a>].</li>
</ul>

<h2>Version 1.0.2 - 18/04/2024</h2>
<ul>
  <li>New standard menus.</li>
  <li>Fixed a bug in importing replies text.</li>
  <li>Fixed the handling of the new change model button in the ChatGPT interface.</li>
  <li>Added an option to choose between GPT-3.5 and GPT-4 Models [<a href="https://github.com/micz/ThunderAI/issues/27">#27</a>].</li>
  <li>Added a link to the <a href="https://micz.it/thunderbird-addon-thunderai/status/">Status Page</a>, to check if there are known issues in interacting with the ChatGPT web interface.</li>
</ul>

<h2>Version 1.0.1 - 13/04/2024</h2>
<ul>
  <li>Italian addon description fixed.</li>
  <li>Improved the method to open the ChatGPT window. Thanks to <a href="https://github.com/jobisoft">John Bieling</a>.</li>
  <li>Fixed a bug in replying to a message. Now the quoted text is correctly displayed.</li>
  <li>Fixed a bug in the compose window. Now is correctly used only the selected text.</li>
  <li>If the prompt is more than 30.000 characters, do not proceed and give a message to the user.</li>
</ul>

<h2>Version 1.0 - 05/04/2024</h2>
<ul>
  <li>First release.</li>
</ul>
