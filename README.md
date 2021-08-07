# jsonFormatter

This is a very basic JSON formatter. It can prettyify and uglify JSON text, with a few options as to how to handle indentation when prettifying.

**Everything happens *entirely* on the client side!** [View Demo][demo]

I created this because I was frustrated with other online JSON formatters that require the data to be submitted to the server, and don't provide formatting options. The browser can already handle this with the [JSON.stringify()][stringify] method that is built-in on every modern browser. Plus this way you don't have to worry about where your data goes when you hit submit, and you don't have to wait for it to upload when you have a very large chunk of data.

No internet connection is even required - written entirely in [Vanilla JS][vanillajs].


[demo]: https://tilde.ampersand.space/json-formatter/
[stringify]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify
[vanillajs]: http://vanilla-js.com/
