<p align="center"><a href="https://docker2saas.app" target="_blank"><img src="icons/apple-touch-icon.png" width="300"></a></p>

<p align="center">
<a href="https://github.com/saasio/saasio-api/actions"><img src="https://github.com/saasio/saasio-api/actions/workflows/test.yml/badge.svg" alt="Build Status"></a>
<a href="https://github.com/saasio/saasio-api"><img src="https://img.shields.io/github/v/release/saasio/saasio-api" alt="Latest Stable Version"></a>
<a href="https://github.com/saasio/saasio-api"><img src="https://img.shields.io/badge/license-MIT-green" alt="License"></a>
</p>

# About
> An open source tool that lets you create SaaS websites from images in as
little as 10 minutes.

---

📖 [**Saasio Documentation**](./docs/INSTALL.md)

🌟 [**Saasio Screenshots**](./docs/SCREENSHOTS.md)

🚀 [**Saasio App Demo**](https://docker2saas.app/)

---

Saasio is a tool that enables multi-tenancy through virtualization
technology (calling cloud platform api ) with tenant management and subscription
managment.  It helps web application and service developers to quickly build
websites for sale or subscription. All you need to do is make an image of your application and
then set up and configure a Saasio site to start selling your application as a service.

When a user's subscription is successful, it automatically creates a VPS from
the image as configured; when the user cancels the subscription and it expires,
it automatically deletes the VPS. Users can login to the site and see their
subscription, host IP information, and other details. Additional extensions can be
added.

The diagram below shows how Saasio interacts between:
End Users  
Payment provider: Stripe 
Cloud service provider: DigitalOcean.

![](./_image/mm1.png)

# Target Users of Saasio

Saasio is aimed at developers of cloud applications, providing them with a
solution to quickly monetize their applications.

Let's say you develop a nice little web app and open source it to Github.
Developers easily build it and use it on their own, but as the app becomes more
popular, so do non-technical users. But even if they have already made a docker
file, it is still difficult for them.

At this point you may want to provide a cloud hosting version. On the one hand,
you can solve the details of the build for non-technical users, and on the other
hand, hosting can bring some profit, so you can get a financial return.

However, this can create an additional amount of development, and it doesn't
seem wise to spend weeks on development before you know if cloud hosting will be
popular.

Fortunately, the open source Saasio solves this problem, and it only takes
ten minutes to configure and you can get a simple and usable cloud hosting sales
site. It's **immediately ready for early sales**, and you can modify the source code
to add more business-related features as user demand increases. 

Of course, it can also be used to build a third-party sales site under the
license of a cloud application developer. But overall, Saasio is designed
for developers and does not take into account the experience of non-technical
users, so if you don't have a technical background, it's better to use a
Saasio site that someone else has built rather than building it yourself.

PS: Saasio is built on Laravel, and while no knowledge is required for a
simple deployment, if you want to customize and add features, then you need to
have a little Laravel development knowledge.

Saasio is licensed under the MIT LICENSE. 

## Demo

You can view a <a href="https://docker2saas.app" target="_blank">live demo here</a>, which will also allow you to preview the software</a>.

## Documentation

Checkout the [official documentation here](./docs/INSTALL.md).

## Sponsors ❤️

Saasio is proudly supported by our amazing sponsors. A big thank you to:

[![DigitalOcean Referral Badge](https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg)](https://www.digitalocean.com/?refcode=46bcaedf5140&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)

[![Laravel Forge Site Deployment Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fforge.laravel.com%2Fsite-badges%2F060b3802-0b55-4e69-91fd-dbfc58287e40&style=plastic)](https://forge.laravel.com/servers/878209/sites/2591533)

# License

The MIT License (MIT)

Copyright (c) Saasio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
