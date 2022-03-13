# Go
I am working with the Go language since late 2017 and now, it evolved to my most used language for my personal projects. Also, since April 2022, I am now as well part of a Go development team in a company here in Germany. 🥳

I also created some packages myself which I am also using a lot in my projects, so I've also listed them here even though it is kind of a shameless plug. 😅

## Learn Go
- [Go Tour](https://go.dev/tour)
- [Go by Example](https://gobyexample.com/)
- [Go Source Code](https://github.com/golang/go/)  
  *If you are already a bit into go, don't be shy to read the official sources of the Go language and built-in packages. It is well structured and documented. Also, there is no better source of best practices as from the developers themselves!*

## Useful Packages
- [paerser](https://github.com/traefik/paerser)  
  *My way-to-go configuration package for many config sources like YAML, JSON, env vars or CLI params.*
- [godotenv](https://github.com/joho/godotenv)  
  *Dead simple .env file parsing package.*
- [fiber](https://github.com/gofiber/fiber)  
  *An easy to use web framework inspired by express using [fasthttp](https://github.com/valyala/fasthttp) under the hood.*
- [fiber/websocket](https://github.com/gofiber/websocket)  
  *Websocket server for fiber.*
- [snowflake](https://github.com/bwmarrin/snowflake)  
  *My way-to-go package to generate unique, sortable and numeric IDs with embedded creation timestamps.*
- [xid](https://github.com/rs/xid)  
  *My second way-to-go package to generate unique, sortable IDs when I am not using snowflakes.*
- [logrus](https://github.com/sirupsen/logrus)  
  *Extensive logging package with a very intuitive and developer friendly API.*
- [testify](https://github.com/stretchr/testify)  
  *Unit test toolkit with assertion and mocking utilities.*
- [jwt](https://github.com/golang-jwt/jwt)  
  *One of the many JWT implementations for go.*
- [service](https://github.com/kardianos/service)  
  *Need to pack your go app into a windows service or linux daemon?*
- [nutsdb](https://github.com/xujiajun/nutsdb)  
  *Simple and easy to use local file key-value database as a great alternative to sqlite3.*
- [mimetype](https://github.com/gabriel-vasile/mimetype)  
  *Guess mime types from file streams.*
- [vibrant](https://github.com/dayvonjersen/vibrant)  
  *Get the most prominent colors from an image.*
- [fuzzy](https://github.com/sahilm/fuzzy)  
  *Fuzzy string matching.*
- [go-chart](https://github.com/wcharczuk/go-chart)  
  *Generate charts and export them as an image.*
- [cron](https://github.com/robfig/cron)  
  *Use crontab like expressions to schedule tasks.*
- [promptui](https://github.com/manifoldco/promptui)  
  *Build interactive CLI tools with this package.*
- [tablewriter](https://github.com/olekukonko/tablewriter)  
  *Print data in ASCII tables.*
- [resize](https://github.com/nfnt/resize)  
  *Resize / Rescale images.*
- [go-qrcode](https://github.com/skip2/go-qrcode)  
  *Create QR Codes.*
- [pinger](https://github.com/chenjiandongx/pinger)  
  *IMCP network ping implementation.*

## My self-created Packages
- [timedmap](https://github.com/zekrotja/timedmap)  
  *A very simple, thread safe in-memory key-value map with entry expiration.*
- [ken](https://github.com/zekroTJA/ken)  
  *An interaction (slash) command wrapper for [discordgo](https://github.com/bwmarrin/discordgo).*
- [dgrs](https://github.com/zekroTJA/dgrs)  
  *An alternative state manager for [discordgo](https://github.com/bwmarrin/discordgo) using Redis to make state persistent and syncable across shards.*
- [sop](https://github.com/zekroTJA/sop)  
  *A Go 1.18+ package which brings functional abstractions like `map`, `filter`, `first`, `flat` and much more to slices.*
- [di](https://github.com/zekroTJA/di)  
  *A very prototype dependency injection package for Go 1.18+ using generics and reflection.*
- [seiteki](https://github.com/zekroTJA/seiteki)  
  *A package and application to easily serve static files of an SPA which uses [fasthttp](https://github.com/valyala/fasthttp) under the hood.*
- [ratelimit](https://github.com/zekroTJA/ratelimit)  
  *Very simple implementation of a token bucket based rate limiter.*
- [slicerdicer](https://github.com/zekroTJA/slicerdicer)  
  *Slices an image into smaller parts of this image.*