# ASP.NET Core: From Zero to overkill

![logo](https://github.com/AspNetCoreFromZeroToOverkill/Home/blob/master/assets/aspnet-core-from-zero-to-overkill.jpg)

This is the home repository for the series of videos/posts I'll be making on ASP.NET Core and friends.

The goal of this series will be to build a complex application using ASP.NET Core, starting simple and complicating along the way.

The end result will probably be on the over-engineered side (hence the “overkill” on the title), because the application will be developed as an excuse to try a whole lot of technologies and concepts. If the application wasn’t being developed with educational purposes in mind, the outcome would certainly be simpler.

For a more detailed intro check out [this post](https://blog.codingmilitia.com/2018/10/02/aspnet-000-from-zero-to-overkill-intro).

## Repositories:
- [GroupManagement](https://github.com/AspNetCoreFromZeroToOverkill/GroupManagement) - repository containing the component responsible for everything group related, from creating and editing its details, associating users, managing players, etc.
- [WebFrontend](https://github.com/AspNetCoreFromZeroToOverkill/WebFrontend) - repository containing the application's frontend components, namely a Vue.js single page application and an ASP.NET Core backend for frontend, acting as a facade between the SPA and the backend services.
- [Auth](https://github.com/AspNetCoreFromZeroToOverkill/Auth) - repository containing the authentication logic, centralized in a standalone application. It's an OpendID Connect provider, allowing for the web frontend to delegate the user authentication to it (and, if needed, also other applications, for instance, mobile implementations).
- [Deplyment](https://github.com/AspNetCoreFromZeroToOverkill/Deployment) - General deployment tooling for the application.
- [EpisodeNotes](https://github.com/AspNetCoreFromZeroToOverkill/EpisodeNotes) - repository containing episode notes in presentation format, used at the start of the videos to introduce what we'll be doing in each one.

## Various links
- [Blog posts](https://blog.codingmilitia.com/category/fromzerotooverkill/) - lists the posts on the Coding Militia blog, filtered just for this series
- [YouTube playlist](https://www.youtube.com/playlist?list=PLN0oN9Azm_MMAjk3nhRnmHdr1l0160Dhs) - playlist on the Coding Militia channel with all the videos recorded for this series

## Planning
You can check out the (not set in stone) planning of the series [here](https://github.com/AspNetCoreFromZeroToOverkill/Home/projects/1).
