**Mailchimp is used to send email blasts. It's very useful but also can be very annoying. Here's my tips for how to use Mailchimp.**

## Setting it up
### Billing
- Mailchimp is one of the few expenses for Marketing. You'll need to **put a payment method (like credit card) on file**. Go to Account > Billing > Billing Information and there should be an option to put a payment method.
- Every month, your payment method will be charged. The amount depends on how many current subscribers there are (Mailchimp sets different ranges and in my experience, it's been based on the *highest* number of subscribers for the month so keep a watch on that!!).
- The Billing History section is very useful. **Save a copy of the invoice** so each month you can send it to the HackRU Treasurer (on Finance) and they'll get you reimbursed! Reimbursements come via a physical check usually given to you by the Treasurer at Directors meetings!
- Remember to **pause the Mailchimp account when you don't need to send emails** (usually in early summer and winter months) so you don't get charged for the month.
### Contacts list
- Try to maintain the list so that it's up-to-date with people who sign up for the mailing list on the HackRU website (get CSVs of new subscribers' emails from RnD-- I always bugged them and they'll do it :))
- To **add contacts**, go to Audience > All Contacts > Add contacts > Import contacts. Then, check the correct settings (RnD usually gives a CSV file) and make sure that if there's duplicate emails, it'll just update existing rather than adding new contacts. 
- Keep a watch on that audience count! One month the cost jumped like $20 because I imported a ton of new contacts without cleaning some outdated ones first (see below for more info on how to do that). The count went over 2500 or whatever so it bumped up to the next range, even though there were many contacts that were actually inactive that I could have removed first!! Sad times for me and my bank account.

## Maintaining contacts
### Yeeting contacts away
- Mailchimp might remove emails that hard bounced (such as email addresses that don't exist) but it's good to once in a while look through the contacts list and see if any emails are obviously not real.
- If there's any obvious typos in email addresses (like *@rutgesr.edu*, which I've seen a lot lol), you can edit it.
- Larger audience = more expensive as mentioned earlier :( so try to **remove any contacts that don't open emails or where emails bounced**. You can do this by using Segments. Take a look at Mailchimp's documentation or feel free to ask me how to use Segments. An example of a useful Segment condition is: [Campaign Activity] : [did not open] [All of the last 5 campaigns] AND [Campaign Activity] : [was sent] [All of the last 5 campaigns]
- To remove contacts, **select 'Archive'** because that takes them out of the audience count.
### Keeping track of specific audiences
- Since HackRU does waves of acceptances (RnD will give CSV lists), I always used Tags to keep track of email addresses (like f19-wave1, f19-wave2, etc.)
- I would get a CSV file of email addresses, import them (make sure you're updating existing contacts) and select the option to add a certain tag to these addresses.
- There are probably other ways to do this, so feel free to experiment with what works!

## Creating emails
This is the fun part!
### Design
- As of Spring 2020, our official font was [Titillium Web](https://fonts.google.com/specimen/Titillium+Web?preview.text=HackRU&preview.text_type=custom) and our color palette was red (`#C85151`) as our main color and yellow (`#F1BA43`) and green (`#4FAB5F`) as our accent colors. Since the red was our main color, the emails I created were mainly black font with red accents.
- Use a template as a base and then just change the content. Take a look at the HackRU Spring 2020 campaign template as an example and feel free to take inspiration from past templates if you want to make a new email template.
### Writing an email
- In Mailchimp, anything you send out is called a campaign. An email is one type of campaign. You should be naming campaigns something like "Spring 2020 Registration Open" so you know what it is when you want to look at it later.
- When creating an email, you'll need:
    - To field: this is where those Tags can come in handy. You can select specific audiences to send emails to.
    - From field: make sure it says the right semester. The email address should stay the same (info@).
    - Subject Line: keep it brief but descriptive (like "Confirm your Attendance for HackRU Spring 2020")
    - Content: whatever needs to be in the email. Use buttons and links and formatting to make the important parts of the email easy to read.
### Tips
- K.I.S.S.: Keep it short and sweet (or keep it simple, stupid). This was one thing I had trouble with (and feedback I got from other Directors): the emails were too long and I wrote too much. Keep the emails short and simple. Most of the info should be on our website anyway, so no need to put blocks of text in an email. If people have questions, they should be aware that they can contact us.
- Spell check and especially check important details (dates and locations especially). Send test emails to yourself (and other HackRU teams) to make sure everything is correct and looks OK before email blasting to the whole contact list.
- Coordinate social media blasts with the emails (for example, when registration is open).

## Tracking campaigns
- You can look at how campaigns are performing in terms of opens and clicks (if you have any links).
- Go to Campaigns and then click the 'View Report' button next to the campaign you want to look at.
- It also shows the reach of the campaign. Some emails will bounce and you can investigate if any contacts need to be updated or removed. Also some people might unsubscribe so you can remove those too.
