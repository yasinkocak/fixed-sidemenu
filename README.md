
Easiest way for creating side menus CSS3 transitions

## Getting Started

Set up on your body the position

**Left sidemenu**
'''php
<body class="sidemenu-left">
''
**Right sidemenu**
'''php
<body class="sidemenu-right">
''

After body
**Side menu**
'''php
<div id="sidemenu">
	...
</div>
'''

jQuery for toggle sidemenu
'''php
<script>
    $("#sidemenu-toggle").click(function(e) {
        e.preventDefault();
        $("body").toggleClass("toggle-sidemenu");
    });
</script>
'''

See example: [http://yasinkocak.github.io/fixed-sidemenu](http://yasinkocak.github.io/fixed-sidemenu)

## Development

- Source hosted at [GitHub](https://github.com/yasinkocak/fixed-sidemenu)
- Report issues, questions, feature requests on [GitHub Issues](https://github.com/yasinkocak/fixed-sidemenu/issues)

Pull requests are very welcome!

## Licensing

Released under the MIT License [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)

Copyright © 2014 Yasin Kocak ([http://www.yasinkocak.com](http://www.yasinkocak.com))