# Event Jekyll Theme
Event Jekyll Theme is a theme that is designed to be used for conference and event purposes. The index page is a modification and built on top of [Agency Jekyll Theme](https://github.com/y7kim/agency-jekyll-theme). Unlike most Jekyll Themes, Event Jekyll Theme is not meant to be a single page theme. This theme is a package that you can use for your organization's event as it come with almost everything you need. I reorganized all the files to make sure that you can easily reuse the same template each year (or each month, depending on how you organize the path), assuming that you event is once a year.

Big thanks to the creator of Agency as this theme would not be possible without their hard work! You are always welcome to contribute to this repository to make it better!

**Example Site**
- [Malaysian Students' Technology Conference](https://msiastc.github.io)
- [Event Jekyll Theme](https://event-jekyll-theme.github.io)

## Features
### Index Page
- Event's title, location, and date
- Welcoming remark section with video
- Speaker with name, title, pop up profile section
- About section with options to navigate to subpages
- Event Sponsors' pictures section
- Contact Us section
  - Refer to [Formspree](https://formspree.io/) on how to setup the contact form.
### Agenda Page
- Table with time and event title columns
- Speaker's name is hilighted in different color and speaker's position/title is in italic.
### Team's Profile Page
Two different design:
-  profile picture with name and email
-  user profile with picture, title, position, and profile
### Event's Location
- Google Map (need to replace it with your own API key)
### FAQs Page
- Just a typical FAQs page
### Mission, Vision, and Objectives Page
- Sections to talk about mission, vision, objectives, and history about your event
### Register Page
- A page to redirect to a sign up page
### More features
- Google Analytics built in (replace `UA-xxxxxxxx-x` with your personal analytics verification key in `_includes/2016_data/head.html`)
- SEO (check `_config.yml`)
- Customized 404 Page Not Found Page
- Designed to be futureproof as you can create a subpages for each year (eg. YOUR-LINK.github.io/2015, YOUR-LINK.github.io/2016, etc)
- Header with icon logo defined, but removed from source code. 
- Website logo in SVG defined, but removed from source code.
- Display PDF from Google Drive

## Installation
1. For first time user, you have to install Ruby and NodeJS. You may follow my installation guide in my [Jekyll tutorial](http://melvinchng.github.io/jekyll/installation.html#ruby-and-nodejs-installation) or [Ruby on Rails Tutorial](http://melvinchng.github.io/jekyll/RubyOnRailsInstallation.html) for Windows, Linux, and MacOS (installation videos are included).
2. Install Jekyll by using the command `gem install jekyll`.
3. Then, install Jekyll Sitemap and Jekyll SEO gems by using the command `gem install jekyll-sitemap` and `gem install jekyll-seo-tag`.
4. Start your localhost server by using the command `jekyll serve`. Make sure that you are at the root directory of your folder before using this command.
5. Your site should be accessible at `localhost:4000`.
6. For additional information about Jekyll, refer to the [official website](http://jekyllrb.com/). 

_Note: If you forked it and edited `_config.yml` via the online editor on Github, the Github pages may not work. In that case, you will make any changes (add a new line, etc) and push the changes from your local machine via CLI or GUI git._

## Files Structure
- The main stylesheet is stored `/css/2016_style`. Both `2016` and `2017` are sharing the same stylesheet.
- In `/css/2016_style/img` you will find where the pictures in `/2016` are stored at. You will find the images of speakers in `/css/2017_style/img`. This setup is to ensure that we can easily to move from year to year by creating new folders.
- `_2016_pages` and `_2017_pages` are the folders that store subpages.
- `_2016_data` and `_2017_data` are the folders that store each sections in home page. Those sections are can be removed by removing or commenting out the `include` code in `_layout/2016_home.html` or `_layout/2017_home.html`.
- `_data/twenty_16/` and `_data/twenty_17/` contains `data` files for agenda, faqs, home about section data, speakers, and team members information. The data file is in the format of `.yml`. The reason why the folders are named `twenty_16` and `twenty_17` are due to liquid syntax will throw errors if the name contains integer. 
- In order to view PDF correctly, sharing setting in Google Drive must set to "Public on the web".

## Enjoy!
소라이 아루 나니카오 미츠메테타라  
소레와 호시닷테 키마가 오시에테 쿠라타  
마루데 소레와 보쿠라미타이니 요리솟테루  
소레오 나이타리 와랏타리 츠나이데이쿠  
난쥬카이 난뱌쿠카이 부츠카리앗테  
난쥬넨 난뱌쿠넨 무카시노 히카리가  
호시 지신모 와스레타 코로니  
보쿠라니 토도이테루  
보쿠라 미츠케앗테 타구리앗테 오나지 소라  
카가야쿠노 닷테 후타리닷테 야쿠소쿠시타  
하루카 토오쿠 오와라나이 베테루기우스  
다레카니 츠나구 마호  
보쿠라 카타나라베 테도리앗테 스슨데쿠  
츠라이토키닷테 나카나잇테 치캇타다로  
하루카 토오쿠 오와라나이 베테루기우스  
키미니모 미에루다로 이노리가  
키오쿠오 타도루 타비 요미가에루요  
키미가 이츠닷테 소코니 이테쿠레루 코토  
