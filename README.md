dotnet dev-certs https -ep aspnetapp.pfx -p { password here }

Then copy the new generated file "aspnetapp.pfx" to %USERPROFILE%\.aspnet\https

dotnet dev-certs https --trust

Add %USERPROFILE%\.aspnet to "Path" environment variable