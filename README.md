This repository contains a basic Razor Pages application integrated with Auth0 authentication.

Check out the article [Securing Razor Pages Applications with Auth0](https://auth0.com/blog/securing-razor-pages-applications-with-auth0/) for the implementation details.

# Requirements

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0) installed on your machine
- Visual Studio 2022 (optional)

# To run this application

1. Clone the repo with the following command:

   ```bash
   git clone https://github.com/auth0-blog/acme-aspnet-razor.git
   ```

2. Move to the `acme-aspnet-razor` folder.

3. Add your Auth0 domain and client id to the `appsettings.json` configuration file (see [Register with Auth0](https://auth0.com/blog/securing-razor-pages-applications-with-auth0/#Register-with-Auth0) for more details).

4. Type `dotnet run` in a terminal window to launch the application.

5. Point your browser to the [https://localhost:7204](https://localhost:7204) address. You should see a web page like the following:

![acme-homepage-login](acme-homepage-login-razor.png)
