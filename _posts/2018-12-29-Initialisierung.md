---
layout: post
title: Initialisierung
---

```ruby
public class Documentation
  def initialize(topics, author, language, coding_language)
    @topics = "Scripting, IT-Sicherheit, persönliche Projekte, Linux, Dark Themes"
    @author = 'Marcel Artz'
    @language = "Deutsch"
    @coding_language = "Englisch"
  end
end
```

`»»» Arguments accepted`

```ruby
marcelsSite = Documentation.new
```

`»»» Engine starting... 
 »»» checking for updates...
 »»» Documentation succesfully started!`
