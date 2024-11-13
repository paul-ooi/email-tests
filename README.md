# Email templates
Create Email templates using [MJML framework](https://github.com/mjmlio/mjml)

## Email Tests
Use [Putsmail](https://putsmail.com/) to send test emails
- Copy and paste HTML code into the body of the Test email
- Add your recipients to Test 
- Make sure your email looks great on mobile and Desktop
- Don't forget to test with a Screen Reader too like Voice Over, Navigator, NVDA, JAWS, etc.


## To build new templates
- Create new file with `.mjml` extension
- Use MJML markup to build page
- use `npx mjml -w [working-file].mjml -o [output-file].html` to watch for changes on the MJML file and output to an HTML file