n8n Project:
What does it do?
This n8n workflow first takes the inserted data from an HTML form with a webhook, then archives that data in a Google sheet, sends me a mail to notify me of the sent form, and then the respond to webhook module sends a success message to the browser to notify the user that the form was sent.

What makes it useful?
It allows the potential visitors of the page to send forms regarding petitions or bug reports on my page and stores those messages in a Google sheet for easy access

What challenges were found?
During the incorporation of the Gmail node i had some issues with the creation of the OAuth2 credentials and later i had problems with the form content not reaching the Google sheet because of JSON mismanagement