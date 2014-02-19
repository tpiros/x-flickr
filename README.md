# Custom Polymer element for retrieving photos from flickr

Inspired by <a href="https://github.com/addyosmani/x-instagram/" target="_blank">Addy Osomani's x-instagram</a>

To see this demo in action please register for a <a href="http://www.flickr.com/services/apps/create/apply/" target="_blank">Flickr API key</a>. Once done, update <code>src/x-flickr.html</code> file with the right API key (<a href="https://github.com/tamaspiros/x-flickr/blob/master/src/x-flickr.html#L43">line 43</a>).

## Usage
Add the custom <code>&lt;x-flickr></code> tag to your HTML page (along with the necessary Polymer libraries). You have access to the following options:

<ul>
  <li><strong>apikey</strong>: your API key can be specified as an attribute as well - e.g. &lt;x-flickr apikey="yourkey">&lt;/x-flickr></li>
  <li><strong>tag</strong>: tag to search for - e.g. &lt;x-flickr tag="rome">&lt;/x-flickr></li>
  <li><strong>amount</strong>: number of photos to be returned - e.g. &lt;x-flickr amount=15>&lt;/x-flickr></li>
</ul>