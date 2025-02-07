<p align="center">
    <a href="https://smartproxy.com/"><img src="https://smartproxy.com/wp-content/themes/smartproxy/images/smartproxy-logo.svg" alt="Smartproxy logo" width="200" height="50"></a>
  </a>
</p>

<p align="center">
    <a href="https://github.com/Smartproxy/Smartproxy"> :house: Main Repository :house: </a>
</p>

### Disclaimer

Selenium is a browser automation tool. This particular repository only covers Selenium setup for Ruby based programming language.

To continue further development with this tool, make sure to read their [documentation](https://ruby-doc.org/).

*Unfortunately, Selenium itself does not support `username:password` authentication for `HTTP/HTTPs` proxies, thus you will need to have your IP whitelisted.*

You can do that by following guidlines listed [here](https://help.smartproxy.com/docs/proxy-authentication).

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/)
- [Selenium](https://rubygems.org/gems/selenium-webdriver)

### Installation

1. Once you have all the required prerequisites ready, create your project folder:

```
mkdir selenium_ruby
cd selenium_ruby
```
<img src="https://i.imgur.com/mylk9t7.png">

2. When project directory is setup, you can now download one of our example scripts for proxy setup with Selenium:

*Firefox*

```curl https://raw.githubusercontent.com/Smartproxy/Selenium/master/ruby/firefox/example.rb > example.rb```

*Chrome*

```curl https://raw.githubusercontent.com/Smartproxy/Selenium/master/ruby/chrome/example.rb > example.rb```

3. You should now see your project folder populated with *example.rb* file.

### Configuration

To configure the endpoint you would like to use, change the example Gate endpoint in within punctuation marks(''):

<img src="https://i.imgur.com/irXotBO.png" alt="smartproxy selenium ruby http proxy configuration example">

### Usage

If you did everything correctly, you can simply test our script by running `ruby example.rb` command while in your project folder.

A browser window will apear with the targeted website, and a proxy IP should be visible in the console output:

<img src="https://i.imgur.com/0pthFxs.png">

## How to get started with Smartproxy?
[<img src="https://smartproxy.com/wp-content/uploads/2019/04/How-to-buy-Smartproxy-plans-now.svg">](https://dashboard.smartproxy.com/register)
<br><br><center>Accepted payment methods:
<br><img src="https://smartproxy.com/wp-content/uploads/2018/09/payment-methods-smartproxy-residential-rotating-proxies.svg" alt="" width="250" height="50"></center>

## Need help?
Email - sales@smartproxy.com
<br><a href="https://smartproxy.com">Live chat 24/7</a>

