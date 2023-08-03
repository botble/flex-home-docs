# API

## Overview

API package is located in `/platform/packages`. It's using Laravel Passport. Learn more
here: https://laravel.com/docs/6.x/passport.

## Install

```bash
php artisan passport:install
```

## Generate API document

We're using https://github.com/knuckleswtf/scribe to make API document. Run below command to generate docs.

```bash
php artisan scribe:generate
```

Go to `http://your-domain/docs` to see API document.
