<!---
    @title         OpenResty
    @creator       Yichun Zhang
    @created       2011-06-21 04:03 GMT
    @modifier      YichunZhang
    @modified      2015-12-30 20:21 GMT
    @changecount   34
--->

OpenResty (aka. ngx_openresty) is a full-fledged web platform by integrating the standard [Nginx](nginx/) core, [LuaJIT](luajit/), many carefully written Lua libraries, lots of high quality [3rd-party Nginx modules](components/), and most of their external dependencies. It is designed to help developers easily build scalable web applications, web services, and dynamic web gateways.

By taking advantage of various well-designed [Nginx](nginx/) modules (most of which are developed by the OpenResty team themselves), OpenResty effectively turns the nginx server into a powerful web app server, in which the web developers can use the Lua programming language to script various existing nginx C modules and Lua modules and construct extremely high-performance web applications that are capable to handle 10K ~ 1000K+ connections in a single box.

OpenResty aims to run your server-side web app completely in the [Nginx](nginx/) server, leveraging [Nginx](nginx/)'s event model to do non-blocking I/O not only with the HTTP clients, but also with remote backends like MySQL, PostgreSQL, Memcached, and Redis.

OpenResty is //not// an [Nginx](nginx/) fork. It is just a software bundle. Most of the patches applied to the [Nginx](nginx/) core in OpenResty have already been submitted to the official [Nginx](nginx/) team and most of the patches submitted have also been accepted. We are trying hard //not// to fork [Nginx](nginx/) and always to use the latest best [Nginx](nginx/) core from the official [Nginx](nginx/) team.

See [Components](components/) for the complete list of software bundled in OpenResty.

See [GettingStarted](getting-started/) on how to quickly setup an OpenResty server that can say hello world over HTTP. Or you can go to the [Download](download/) section to grab OpenResty's source code tarball directly.

We provide free technical support in the openresty and openresty-en mailing lists. See [Community](community/).