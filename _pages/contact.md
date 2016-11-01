---
title: Contact
layout: post
permalink: /contact/
---


<style>
.contact-li {
    list-style: none;
}

.contact-input {
    border:none;
    border-bottom: 1px solid #eee;
    width: 12em;
}

.contact-input:focus {
    outline:none;
    border-bottom: 1px solid #ea6111;
}

.contact-label {
    display: block;
}

ul.contact-ul {
    margin: 0;
    padding: 10px;
}

#submit {
    border:none;
    background-color: #ea6111;
    padding: 5px 15px;
    color: #eee;
    opacity: 0.8;
}

#submit:hover {
    opacity: 1;
    cursor: pointer;
}


#contact-form {
    border: 1px solid #aaa;
    display: inline-flex;
    margin-bottom: 1em;
}

</style>

You can send me your feedback or suggestion here. If there is something missing in the theme then you can ask me to add. 

Also, if you are willing to add it yourself then feel free to open a pull request after making changes.

<form id="contact-form" class="form" action="https://getsimpleform.com/messages?form_api_token={{site.api-token}}" method="POST" enctype="multipart/form-data">
        <ul class="contact-ul">
            <li class="contact-li">
                <label class="contact-label" for="name">Name:</label>
                <input type="text" placeholder="Your name" id="name" class="contact-input" name="name" tabindex="1"/>
            </li>
            <li class="contact-li">
                <label class="contact-label" for="email">Email:</label>
                <input type="email" placeholder="Your email" id="email" class="contact-input" name="email" tabindex="2"/>
            </li>
            <li class="contact-li">
                <label class="contact-label" for="message">Message:</label>
                <textarea class="contact-textarea" placeholder="Your message" class="contact-input" rows="4" id="message" name="message" tabindex="3"></textarea>
            </li>
            
        </ul>
        <input type="submit" value="Send" id="submit"/>
        <input type="hidden" name='redirect_to' value="http://blog.webjeda.com/thank-you/" />
        
</form>

This form is setup using [SimpleForm](https://getsimpleform.com){: target="_blank" rel="nofollow"}. You can get your own API token and update it in the **_config.yml** file.

But remember, php forms will not work on Jekyll.

More about jekyll forms here: [https://blog.webjeda.com/jekyll-subscribe-form/](https://blog.webjeda.com/jekyll-subscribe-form/)

The styles for the form is included in this page. I haven't included it in the main css because the form has at least 25 lines of css and it is used only on this page. So including it in main css file doesn't make sense.


<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.8&appId=1409800599270506";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>


<div class="fb-page" data-href="https://www.facebook.com/webjeda/" data-small-header="true" data-adapt-container-width="false" data-hide-cover="true" data-show-facepile="true"><blockquote cite="https://www.facebook.com/webjeda/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/webjeda/">WebJeda</a></blockquote></div>