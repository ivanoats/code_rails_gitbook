# Email on Rails

<script async class="speakerdeck-embed" data-id="1dcb446035d90131644176ede1a85f95" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

* Watch the Railscast on [Active Model](http://railscasts.com/episodes/219-active-model)
* Homework: Add a simple contact form to your portfolio.
* Watch / [Read Rails API versioning](http://railscasts.com/episodes/350-rest-api-versioning?view=asciicast)
* Send out some email from your Portfolio or Class Project, based on an
appropriate controller action, like sign up, or a new post.

Note: Rails, in development mode, will not actually send outgoing email. It will
dump the text of the email to the development log. If you want a nice HTML
preview of your outgoing mail, use Ryan Bates’ letter_opener gem. Here’s a
[tutorial](http://www.sitepoint.com/preview-your-rails-mail-with-letter-opener/) on how to use it.
Also check out the Railscast on [Sending Email (revised)](http://railscasts.com/episodes/61-sending-email-revised).

* Homework: Process an incoming email via the
[Postmark API](https://devcenter.heroku.com/articles/postmark#using-postmark-inbound)
(or other inbound email like [Sendgrid](https://devcenter.heroku.com/articles/sendgrid)
if you have more experience with that) For example, a special email on your
domain for a contact request, or to create a new blog post. You'll need an email
address on your own domain name (or @uw.edu) for this assignment. Postmark
doesn't work with Gmail or Yahoo addresses.

Example Code from class is in this pull request: https://github.com/UW-Advanced-Rails-2014/portfolio/pull/4 

* Turn in the assignment by making a Pull Request to your code, as usual, on a
 feature branch named appropriately. 
* Comment with "Done", a question or reflection, and let me know if you had collaborators.