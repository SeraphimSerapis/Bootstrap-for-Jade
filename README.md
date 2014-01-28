Bootstrap for Jade
==================

Enables you to use the Node templating engine Jade for Bootstrap by delivering a layout.jade file and the needed includes.

Special focus was made to match [Twitter's Bootstrap][bootstrap] 3.0.3 examples.

This project uses existing work from [Andy Jarett][l1] and [Dirk Krause][l2]

Usage
==================
To use this project you'll need [**Express**][exp] & [**Jade**][jade]. Installation of all dependencies is handled via npm:

	npm install

Configuration can be done by modifying the *app.js* & *routes/index.js* files.

The footer can be modified by changing *views/inc/footer.jade*.

Contact
==================
GitHub: [github.com/SeraphimSerapis][github]
Twitter: [@SeraAndroid][twitter]
Mail: <tmesserschmidt@paypal.com>

[bootstrap]: http://twitter.github.com/bootstrap/
[github]: https://github.com/SeraphimSerapis
[twitter]: https://twitter.com/seraandroid
[l1]: http://www.andyjarrett.co.uk/blog/index.cfm/2011/12/21/layoutjade-for-Twitters-Bootstrap
[l2]: https://gist.github.com/1771035
[exp]: http://expressjs.com/guide.html
[jade]: http://jade-lang.com/
