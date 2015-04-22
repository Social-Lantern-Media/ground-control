## Ground Control

Ground control is an experimental blogging platform, built in [Meteor](http://meteor.com). See an example of it in action at http://groundcontrol.meteor.com.

### Install

Ground Control is a vanilla meteor app. To install it, simply [download meteor](http://docs.meteor.com/#quickstart), then download Ground Control.

### Customization

Customization is fairly limited at this point. Edit `lib/configuration.js` and `server/configuration.js` and set the configuration variables there.

### Running

Simply run `meteor`.

### Creating the initial user

When you first browse to your Ground Control install, you'll be prompted to configure the google oauth provider, and sign in with a google account, or use an email address / password account.

### Creating Posts

Later, you (or others) can login to Ground Control at `/admin`. Admin account signup is limited to two options:
  - email address matching a domain set via the admin control panel.
  - email addresses invited via the admin control panel.

### Further customization

To do any meaningful customization, fork this repository and have fun! For example, take a look at the `percolate` branch for an example of the changes made for the [Percolate Studio Blog](http://blog.percolatestudio.com).

Pull Requests will be appreciated! 

### Coming soon

Ground Control is always a work in progress. Expect to see things like:

1. Real time viewing stats
2. Theming / pages support
3. Commenting support

Feel free to make any contributions that you like!

## License 

MIT. (c) Percolate Studio, maintained by Tom Coleman (@tmeasday).
