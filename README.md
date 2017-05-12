# Social Gems

Sometimes we need to make our project more 'social', so we add 'share' ability, log in with (Facebook, Twitter, Instagram, etc), duplicating posts in social networks. There is a bit set of gems and articles in this field.

## Omniauth
[Habr post: devise + Omniauth + Facebook + VK (RUS)](https://habrahabr.ru/post/142128/),
[Devise wiki](https://github.com/plataformatec/devise/wiki/OmniAuth:-Overview)

Although you can add 'log in with ...' links to devise forms if add this code to:

```rhtml
  <!-- app/views/devise/shared/_links.html.erb -->

  <% if devise_mapping.omniauthable? %>
    <% resource_class.omniauth_providers.each do |provider| %>
      <%= link_to "Sign in with #{OmniAuth::Utils.camelize(provider)}", omniauth_authorize_path(resource_name, provider) %><br />
  <% end %>
```

## Social 'share' buttons

Flexible gem with cute button images. Supports: Facebook, Twitter, Douban, Google+, Weibo, QZone, Google Bookmark, Delicious, Tumblr, Pinterest, Email, LinkedIn, WeChat (Weixin), Vkontakte, Odnoklassniki, Xing, Reddit, Hacker News, Telegram.

![btns](https://cloud.githubusercontent.com/assets/5518/19097657/ea7c0a20-8ad8-11e6-953f-83354d9a6384.png)

[Github](https://github.com/huacnlee/social-share-button)

## Set of rest clients for Social

* RC::Dropbox (via OAuth 1.0a)
* RC::Facebook (via OAuth 2, most completed)
* RC::Github (via OAuth 2)
* RC::Instagram (via OAuth 2)
* RC::Linkedin (via OAuth 1.0a)
* RC::StackExchange (via OAuth 2)
* RC::Twitter (via OAuth 1.0a)

[Github](https://github.com/godfat/rest-more)

## Facebook and Twitter integration tutorial

[koala gem](https://github.com/arsduo/koala),
[twitter gem](http://sferik.github.io/twitter/)

[Tutorial link](https://github.com/rdurgarao/Facebook-Twitter-posts-with-rails-example)
