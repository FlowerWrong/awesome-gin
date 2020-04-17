# awesome-gin

Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance -- up to 40 times faster. If you need smashing performance, get yourself some Gin. https://gin-gonic.github.io/gin/

## Middlewares

* [gin-contrib/cors](https://github.com/gin-contrib/cors) Gin's CORS middleware
* [gin-contrib/pprof](https://github.com/gin-contrib/pprof) Gin's pprof middleware
* [ulule/limiter](https://github.com/ulule/limiter/tree/master/examples/gin) Gin's rate limit middleware
* [aviddiviner/gin-limit](https://github.com/aviddiviner/gin-limit) Stay under the limit with this handy Gin middleware.
* [imtoori/gin-redis-ip-limiter](https://github.com/imtoori/gin-redis-ip-limiter) Simple gin middleware ip limiter
* [gin-contrib/cache](https://github.com/gin-contrib/cache) Gin's page cache middleware
* [gin-contrib/multitemplate](https://github.com/gin-contrib/multitemplate) Gin's custom HTML render to support multi templates
* [appleboy/gin-jwt](https://github.com/appleboy/gin-jwt) Gin's jwt middleware
* [gin-contrib/authz](https://github.com/gin-contrib/authz) Authz is an authorization middleware for Gin, it's based on https://github.com/casbin/casbin.
* [gin-contrib/gzip](https://github.com/gin-contrib/gzip) Gin's gzip middleware
* [gin-contrib/sentry](https://github.com/gin-contrib/sentry) Middleware to integrate with [sentry](https://getsentry.com/) crash reporting
* [gin-contrib/sessions](https://github.com/gin-contrib/sessions) Gin's middleware for session management with multi-backend support (currently cookie, Redis, Memcached, MongoDB)
* [gin-contrib/static](https://github.com/gin-contrib/static) Gin's static middleware, `r.Use(static.Serve("/static", static.LocalFile("/tmp", true)))`
* [gin-contrib/secure](https://github.com/gin-contrib/secure) Gin's secure middleware
* [swaggo/gin-swagger](https://github.com/swaggo/gin-swagger) Gin's middleware to automatically generate RESTful API documentation with Swagger 2.0
* [appleboy/gin-status-api](https://github.com/appleboy/gin-status-api) Gin's middleware for golang cpu, memory, gc, etc information api handler
* [gin-contrib/location](https://github.com/gin-contrib/location) Gin's middleware to expose the server's hostname and scheme
* [fatihkahveci/gin-inspector](https://github.com/fatihkahveci/gin-inspector) Gin's middleware for investigating http request.
* [yasaricli/gah](https://github.com/yasaricli/gah) Gin's authentication handlers.

## Log

* [Bose/go-gin-logrus](https://github.com/Bose/go-gin-logrus) Gin Web Framework for using Logrus as the Gin logger with Tracing middleware
* [gin-contrib/zap](https://github.com/gin-contrib/zap) Alternative logging through uber-go/zap

## HTML Templates

* [foolin/goview](https://github.com/foolin/goview) Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. Supports ginview, echoview and gorice.
* [foolin/gin-template](https://github.com/foolin/gin-template) :fire: (Deprecated) Golang template for gin framework with layout, cache, partial, multiple templates support.
* [html/template](https://golang.org/pkg/html/template/) Gin's default HTML template
* [robvdl/pongo2gin](https://github.com/robvdl/pongo2gin) Gin's [pongo2](https://github.com/flosch/pongo2) HTML template plugin, if you like django, you will like it also
* [FlowerWrong/plushgin](https://github.com/FlowerWrong/plushgin) Gin's [plush](https://github.com/gobuffalo/plush) HTML template plugin, if you like erb, you will like it also

## websocket

* gin + [gorilla/websocket](https://github.com/gorilla/websocket): `conn, err := wsupgrader.Upgrade(w, r, nil)`
* [olahol/melody](https://github.com/olahol/melody): Melody is websocket framework based on [gorilla/websocket](github.com/gorilla/websocket) and gin.

## metrics

* [zsais/go-gin-prometheus](https://github.com/zsais/go-gin-prometheus) Gin Web Framework Prometheus metrics exporter
* [szuecs/gin-gomonitor](https://github.com/szuecs/gin-gomonitor) Gin middleware for monitoring
* [semihalev/gin-stats](https://github.com/semihalev/gin-stats) Gin middleware for request stats

## Gin project in real world

* [Massad/gin-boilerplate](https://github.com/Massad/gin-boilerplate) Gin Framework with a structured starter project that defaults to PostgreSQL database and Redis as the session storage.
* [wangsongyan/wblog](https://github.com/wangsongyan/wblog) Blog based on gin and gorm
* [b3log/pipe](https://github.com/88250/pipe) A small and beautiful blogging platform, [demo](http://pipe.b3log.org/)
* [TeaMeow/KitSvc](https://github.com/TeaMeow/KitSvc) Microservice framework based on gin, consul, prometheus, eventStore, gorm and NSQ
* [gin-gonic/examples](https://github.com/gin-gonic/examples) A repository to host examples and tutorials for Gin. https://gin-gonic.com/docs/
* [appleboy/gorush](https://github.com/appleboy/gorush) A push notification server written in Go
* [ErikJiang/market_monitor](https://github.com/ErikJiang/market_monitor) go starter kit with(gin,redigo,gorm,zerolog,cron,viper,jwt-go,swaggo)

## Aritcles

* [go-web-applications-and-microservices-using-gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) Building Go Web Applications and Microservices Using Gin

## Framework based on gin

* [go-ego/ego](https://github.com/go-ego/ego) A full-stack web framework written in Go, lightweight and efficient front-end component solutions, based on gin. The front-end is compiled, does not affect the back-end.
* [LyricTian/gin-admin](https://github.com/LyricTian/gin-admin) RBAC scaffolding based on Gin + Casbin + Ant Design React
* [chenhg5/morningo](https://github.com/chenhg5/morningo) A Web develop project skeleton base on Gin
* [vsouza/go-gin-boilerplate](https://github.com/vsouza/go-gin-boilerplate) A starter project with Golang, Gin and DynamoDB
* [ribice/gorsk-gin](https://github.com/ribice/gorsk-gin) Idiomatic Golang Restful Starter Kit using Gin
* [xiaobopang/go_init](https://github.com/xiaobopang/go_init) Scaffolding based on gin, goredis, gorm, websocket, rabbitmq

## Generator

* [dcu/gin-scaffold](https://github.com/dcu/gin-scaffold) Gin scaffold is CLI to generate scaffolds for the gin gonic framework.

## Project layout

 https://medium.com/wtf-dial/wtf-dial-domain-model-9655cd523182

  Application design is a hard problem. There are so many design decisions to make and without a set of solid principles to guide you the problem is made even worse. We’ve looked at several current approaches to Go application design and we’ve seen many of their flaws.
  I believe approaching design from the standpoint of dependencies makes code organization simpler and easier to reason about. First we design our domain language. Then we isolate our dependencies. Next we introduce mocks to isolate our tests. Finally, we tie everything together within our main package.
