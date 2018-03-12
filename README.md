# awesome-gin

Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance -- up to 40 times faster. If you need smashing performance, get yourself some Gin. https://gin-gonic.github.io/gin/

## Middlewares

* [gin-contrib/cors](https://github.com/gin-contrib/cors) Gin's CORS middleware
* [gin-contrib/pprof](https://github.com/gin-contrib/pprof) Gin's pprof middleware
* [ulule/limiter](https://github.com/ulule/limiter/tree/master/examples/gin) Gin's rate limit middleware
* [gin-contrib/cache](https://github.com/gin-contrib/cache) Gin's page cache middleware
* [gin-contrib/multitemplate](https://github.com/gin-contrib/multitemplate) Gin's custom HTML render to support multi templates
* [appleboy/gin-jwt](https://github.com/appleboy/gin-jwt) Gin's jwt middleware
* [gin-contrib/gzip](https://github.com/gin-contrib/gzip) Gin's gzip middleware
* [gin-contrib/sentry](https://github.com/gin-contrib/sentry) Middleware to integrate with [sentry](https://getsentry.com/) crash reporting
* [gin-contrib/sessions](https://github.com/gin-contrib/sessions) Gin's middleware for session management with multi-backend support (currently cookie, Redis, Memcached, MongoDB)
* [gin-contrib/static](https://github.com/gin-contrib/static) Gin's static middleware, `r.Use(static.Serve("/static", static.LocalFile("/tmp", true)))`
* [gin-contrib/secure](https://github.com/gin-contrib/secure) Gin's secure middleware
* [swaggo/gin-swagger](https://github.com/swaggo/gin-swagger) Gin's middleware to automatically generate RESTful API documentation with Swagger 2.0
* [appleboy/gin-status-api](https://github.com/appleboy/gin-status-api) Gin's middleware for golang cpu, memory, gc, etc information api handler

## HTML Templates

* [foolin/gin-template](https://github.com/foolin/gin-template) :fire: Golang template for gin framework with layout, cache, partial, multiple templates support.
* [html/template](https://golang.org/pkg/html/template/) Gin's default HTML template
* [foolin/gin-template](https://github.com/foolin/gin-template) html/template syntax + layout + include + cache + reload support
* [robvdl/pongo2gin](https://github.com/robvdl/pongo2gin) Gin's [pongo2](https://github.com/flosch/pongo2) HTML template plugin, if you like django, you will like it also
* [FlowerWrong/plushgin](https://github.com/FlowerWrong/plushgin) Gin's [plush](https://github.com/gobuffalo/plush) HTML template plugin, if you like erb, you will like it also

## websocket

* gin + [gorilla/websocket](https://github.com/gorilla/websocket): `conn, err := wsupgrader.Upgrade(w, r, nil)`
* [olahol/melody](https://github.com/olahol/melody): Melody is websocket framework based on [gorilla/websocket](github.com/gorilla/websocket) and gin.

## metrics

* [zsais/go-gin-prometheus](https://github.com/zsais/go-gin-prometheus) Gin Web Framework Prometheus metrics exporter

## Gin project in real world

* [Massad/gin-boilerplate](https://github.com/Massad/gin-boilerplate) Gin Framework with a structured starter project that defaults to PostgreSQL database and Redis as the session storage.
* [wangsongyan/wblog](https://github.com/wangsongyan/wblog) Blog based on gin and gorm
* [b3log/pipe](https://github.com/b3log/pipe) A small and beautiful blogging platform, [demo](http://pipe.b3log.org/)
* [TeaMeow/KitSvc](https://github.com/TeaMeow/KitSvc) Microservice framework based on gin, consul, prometheus, eventStore, gorm and NSQ

## Framework based on gin

* [go-ego/ego](https://github.com/go-ego/ego) a full-stack web framework written in Go, lightweight and efficient front-end component solutions, based on gin. The front-end is compiled, does not affect the back-end.

## Generator

* [dcu/gin-scaffold](https://github.com/dcu/gin-scaffold) Gin scaffold is CLI to generate scaffolds for the gin gonic framework.
