# Nginx more headers dynamic module builder

## What is this?
A repository to build [nginx more headers module](https://github.com/openresty/headers-more-nginx-module/) with a corresponding nginx version.

## How to use?
Every week on 1 day 0000hrs UTC it will a github action will be triggered to build the latest more headers module with the latest nginx source code.

To build a specific version, you can fork this repo and run the action with tag names taken from [nginx repo](https://github.com/nginx/nginx/tags) and [more headers module repo](https://github.com/openresty/headers-more-nginx-module/tags)
