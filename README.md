# Avicenna Theme
A minimal academic page for academics built with Hugo.

> This theme hugely benefits from `Ezhil Theme`. I just made some changes to create `avicenna`.

<!-- # Demo -->
<!-- [View demo](https://ezhil-hugo.netlify.com/) -->

<!-- ![Screenshot](images/screenshot.png "Avicenna") -->

# Features
* Minimal, Responsive, and Clean
* Single File Configuration
* Supports Social Links
* Supports Publication Listing
* Supports Project Listing
* Supports Google Analytics
* Supports Hugo RSS feeds

# How To Install `Avicenna`?
> I assume that you know to start with `Hugo`. If you do not know how to run a website with `Hugo`, please read its [quick start](https://gohugo.io/getting-started/quick-start/).

```bash
cd themes
git clone https://github.com/hadisinaee/avicenna.git
```

# Sample Configuration
```toml
# your page address
baseURL = "https://example.edu"
languageCode = "en-us"
title = "Your Name"
theme = "avicenna"
googleAnalytics = "UA-1234-6"
timeout=3000

[params]
  # your profile picture should be under "static" folder
  profile_image="YourProfileImage.jpg"
  subtitle= "PhD Student"
  interests="Deep Reinforcement Learning, Machine Learning "
  # your cv file should be under "static" folder
  cv_name= "YourCVNameFile.pdf"
  blog="http://myblog.edu"

[[params.affilation]]
  name = "Stanford University"
  position = "PhD Student"
  contact = "hadi@cs.stanford.edu"

[[params.affilation]]
  name = "MyCoolStartup"
  position = "Co-Founder"
  contact = "hadi@mycoolstartup.ai"

[[params.social]]
  name = "GitHub"
  icon = "github"
  url = "https://github.com/hadisinaee"

[[params.social]]
  name = "Twitter"
  icon = "twitter"
  url = "https://twitter.com/hadisinaee"


[[params.social]]
  name = "LinkedIn"
  icon = "linkedin"
  url = "https://linkedin.com/in/hadisinaee/"

[[params.introduction.paragraph]]
  text="""Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
	 Nunc scelerisque viverra mauris in aliquam sem fringilla ut morbi. Integer feugiat scelerisque varius morbi enim.
	  A diam maecenas sed enim ut sem viverra. Orci eu lobortis elementum nibh tellus.
		Egestas sed sed risus pretium quam vulputate dignissim suspendisse in.
		Accumsan sit amet nulla facilisi morbi tempus iaculis urna. Condimentum lacinia quis vel eros donec.
   """
[[params.introduction.paragraph]]
  text=""" Pellentesque nec nam aliquam sem et tortor consequat id porta.
	Viverra suspendisse potenti nullam ac. Leo vel orci porta non pulvinar neque laoreet.
	Nulla facilisi nullam vehicula ipsum a arcu. Tempus egestas sed sed risus pretium quam vulputate dignissim suspendisse.
	Ullamcorper velit sed ullamcorper morbi tincidunt ornare. Dui sapien eget mi proin sed libero.
	Quam pellentesque nec nam aliquam sem et tortor consequat id. Aliquet lectus proin nibh nisl.
  """


[[params.projects]]
	[[params.projects.project]]
		name = "my first cool project title"
		description  = "Enim facilisis gravida neque convallis a. Suspendisse potenti nullam ac tortor vitae purus faucibus ornare suspendisse.Velit egestas dui id ornare arcu odio ut sem. Nec nam aliquam sem et tortor. In nisl nisi scelerisque eu ultrices vitae auctor."
		project_page = "https://myprojecthomepage.com"
		code_link = "https://coderepo.com"
		blog_link = "https://ablogpost.com"

 [[params.projects.project]]
		name = "my second cool project title"
		description  = ""
		project_page = "https://myprojecthomepage.com"
		code_link = "https://coderepo.com"
		blog_link = ""

 [[params.projects.project]]
		name = "my third cool project title"
		description  = ""
		project_page = "https://myprojecthomepage.com"
		code_link = ""
		blog_link = "https://ablogpost.com"

[[params.publications]]
  year="Preprint"

  [[params.publications.paper]]
    name = "My Publication Title 1"
    authors = "Author 1, Author 2, __ME__"
    dest  = "Journal/Conference"
    link = "https://mypaperishere.com"
    code_link = "https://thecoderepo.com"
    blog_link = "https://myblogaboutit.com"

  [[params.publications.paper]]
    name = "My Publication Title 2"
    authors = "__ME__, Author 1, Author 2"
    dest  = "Journal/Conference"
    link = "https://mypaperishere.com"
    code_link = "https://thecoderepo.com"
    blog_link = "https://myblogaboutit.com"

[[params.publications]]
  year="2019"

  [[params.publications.paper]]
		name = "My Publication Title 1"
		authors = "Author 1, __ME__ Author 2"
		dest  = "Journal/Conference"
		link = "https://mypaperishere.com"
		code_link = "https://thecoderepo.com"
		blog_link = ""

  [[params.publications.paper]]
		name = "My Publication Title 2"
		authors = "Author 1, __ME__ "
		dest  = "Journal/Conference"
		link = "https://mypaperishere.com"
		code_link = ""
		blog_link = "https://myblogaboutit.com"

  [[params.publications.paper]]
		name = "My Publication Title 3"
		authors = "__ME__, Author 1 "
		dest  = "Journal/Conference"
		link = "https://mypaperishere.com"
		code_link = ""
		blog_link = ""

  [[params.publications.paper]]
		name = "My Publication Title 4"
		authors = "__ME__"
		dest  = "Journal/Conference"
		link = ""
		code_link = ""
		blog_link = ""
```

# Any Idea?
I am using `avicenna` for my personal uses. Therefore, I will update it regularly. If you need something that doesn't exists, let's discuss it over an issue :)

# Credits
* [Ezhil Theme](https://github.com/vividvilla/ezhil)
* [Feather Icons](https://feathericons.com/)
