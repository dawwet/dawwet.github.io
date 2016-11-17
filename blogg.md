---
layout: post
title: Blogg
permalink: /blogg/
---

# Vad är Plex?

Plex är ett användarvänligt program som gör det enkelt att sätta upp din alldeles egna streaming tjänst, oavsätt om det är bilder, musik eller filmer!
Det går enkelt att komma åt allt matrial via mobiltelefoner, surfplattor, datorn, spelkonsoler eller TV. Det går även att dela med sig till vänner och
familj genom att enkelt bjuda in dem via ett e-post meddelande.

![Plex](http://core0.staticworld.net/images/article/2016/06/plex_on_nvidia-100669283-large.jpg)

# Hur fungerar det?

För att kunna använda Plex så måste man installera Plex Media Server, (se länk: https://www.plex.tv/downloads/) på din Dator/Server eller Nas. Beroende på CPU kraften
så varierar det vilket sorts kvalité du kan streama i, se minimum krav:

* No transcoding: Core 2 Duo 1.6GHz (NAS devices based on ARM or PowerPC processors should also be capable of at least one stream with no transcoding)
* Single 720p transcode: Core 2 Duo 2.0 GHz
* Single 1080p transcode: Core 2 Duo 2.4GHz

Om du väljer att lägga till yttligare ljudfiler eller undertexter så kommer Plex transcoding använda extra mycket CPU kraft då servern måste transcoda om
filen innan den streamas till klienterna.

# Hur ser gränssnittet ut?

Gränssnittet varierar lite mellan olika klienter, men senaste standarden för TV ser ut såhär:

![Plex GUI](https://services.tegrazone.com/sites/default/files/article-feature-images/plex-media-server.jpg)

Blogg om Plex, dawwet.

# Posts!

* What do you think of pre-compiling your CSS? 
    * Det verkar bra, jag har precis börjat testat mig på SASS och det är ju exakt samma sak som att skapa vanlig CSS kod, men med möjligheten att spara ner variablar och skapa funktioner. Jag
    behöver till exempel inte leta upp en speciell färgkod flera gånger utan kan skapa upp $standard-text-color: xxxxx; och sedan återanvända den flera gånger.<br>
    * Jag återanvände koden som redan fanns med i template upplägget, men ändrade efter eget behov tills jag blev nöjd.
    * Jag ser ingen nackdel med SASS, tycker det verkar riktigt intressant för att det implementerar mer programmering till vanlig tråkig CSS.
    
* What do you think of static site generators?
    * Jag tycker det är bra att skapa static site generators, framför allt då jag kan spara all information under en template och EJ
    behöva hämta information från en databas vilket kan resultera i en långsammare webbplats, därför gillar jag static site generators.

* What type of projects are they suitable for?
    * Static site generators är en bra lösning för till exempel företag som endast vill visa vilka tjänster dom erbjuder och inte använder en databas där stor information
       behöver hämtas.

* What is robots.txt and how have you configure it for your site?
    * Det är en txt fil som placeras i root katalogen och som sedan nämns i head, sökmotorn kommer då först att söka efter robots.txt, till exempel
    www.example.com/robot.txt, där kommer robots.txt be sökmotorn följa de angivna 'reglerna'.

* What is humans.txt and how have you configure it for your site?
    * Det är bara en text fil som innehåller information om personerna som har skapat webbplatsen, vilka verktyg och extern hjälp som används.
    
* How did you implements comments to blog posts?
    * Jag följde DISQUS guide för att lägga till comments på min webbplats, skapade först upp ett konto på DISQUS, implementerade den rekommenderade koden i post.html och refererar till post i 
    md filerna layout på de sidorna jag vill att comments ska vara tillgänliga.

* What is Open Graph and how do you make use of it?
    * Open Graph används av webbplatser för att kunna visa mer information än bara en länk, man implementerar open graph som meta taggar i head och kommer då att läsas av när någon länkar
    till webbplatsen, då kommer istället en vald bild synas, men titel och beskrivning, det går även att använda på video länkar.
