# OMDB Movie Search in React.js

This is a simple React app that lets you search Open Movie Database for movie titles. It's heavily based on the [React.js tutorial.](https://facebook.github.io/react/docs/tutorial.html)

All the dependencies are included in `lib`:

- [Skeleton.css](http://getskeleton.com/)
- [React.js](https://facebook.github.io/react/) & JSX Transformer
- [jQuery](https://jquery.com) for AJAX

Just clone the repository, open `index.html` in your favorite browser, and search to your heart's content.

There is a bug where movie titles change, but the details don't. To duplicate:

1. Enter a search query
2. Expand the details for any of the movies
3. Enter another search query
4. Notice that the expanded details for remain expanded and are associated with the wrong title

I'm not entirely certain what the React convention is that would prevent this bug, but it warrants investigation.