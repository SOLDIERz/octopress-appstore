# edit by techlux 

- added only German App Store Support - there is still some Bug that some Apps does not show the German App Market. Didn't know why
- added Price and Artistname
- Price will be shown in � ord if it not work in $

THX @Otavio Cordeiro for the cool Plugin

# Octopress AppStore Plugin

An octopress plugin that displays app info from the AppStore. Please note that it only works with apps availables at the US AppStore.

## Syntax

```ruby
{% app_store app_id %}
```

## Example

Magically this:

```ruby
{% app_store 364709193 %}
```

will become this:

```html
<p id='app-widget-com-apple-ibooks'>
  <img src='http://a368.phobos.apple.com/us/r1000/110/Purple/v4/a0/93/08/a0930815-e79b-fb7a-8ea0-8793ddba49f9/Icon-iPhone.png' class='app-icon' style='width:60px; height:60px; vertical-align:middle; margin: 0.1em; border: 0em' />
    <span class='app-name'>
        <a class='com-apple-ibooks' href='https://itunes.apple.com/us/app/ibooks/id364709193?mt=8&uo=4' target='_blank'>iBooks</a>
    </span>
</p>
```

and rendered as this:

![](http://25.media.tumblr.com/20428a0a47a660ce7682ef3a70048e4d/tumblr_mhp3o0iAv31qz4eico1_1280.jpg)

## License

Copyright (c) 2013 Otavio Cordeiro. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
