# z_widget
[Demo here](https://mauricekindermann.github.io/z_widget/)! Z_Widget is a super-lightweight Zendesk help button/contact form widget using PHP, Twitter Bootstrap, and jQuery. Just add your own API key and credentials to zendesk.php and you'll be up and running in no time.

I value page-load speed, so I built this widget into my own site. It adds 0 extra http requests and maybe 1 to 2 kb to the total page size. The normal Zendesk Widget is great, but it comes at the cost of 2+ MB of JS code, several HTTP requests, at least 2 to 3 seconds of extra total load time on each page load.

## Files included
- index.php: All the HTML, CSS and JS you'll need
- zendesk.php: Based on [Zendesks own PHP API Library](https://developer.zendesk.com/rest_api/docs/api-clients/php) with a few adjustments to add the **web_widget** tag and **Submitted from: link**
- tick_success.png: A custom made tick to display when a message sends successfully

## Libraries Used
- [Zendesk API PHP Library](https://developer.zendesk.com/rest_api/docs/api-clients/php)
- [Twitter Bootstrap 3.3.X](http://getbootstrap.com/getting-started/) for the Modal
- [jQuery](https://jquery.com/) for customer modal interactions
- [1000hz/bootstrap-validator](https://github.com/1000hz/bootstrap-validator) for simple modal validation
- [Floating Help Button](https://www.elegantthemes.com/blog/community/free-divi-code-snippets-and-a-growing-github-resource-repo-by-andy-tran-the-divi-nation-podcast-episode-21) by Elegant Themes

## Disclaimer
This widget as no affiliation with Zendesk. [The real Zendesk Widget](https://www.zendesk.com/embeddables/) supports much more functionality, like searching help center and file uploads. Use this code at your own risk, be smart and test it thoroughly in your own environment. I take no responsibility for any issues ecountered in any capacity.

## Credits
This widget was put together by [Maurice Kindermann](https://dribbble.com/maurice_k) for [Golden Carers](https://www.goldencarers.com). 