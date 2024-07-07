Hey are you facing the following error?
> Cloning into '<repo_name>'...
fatal: unable to access '<git_repo_link>': SSL certificate problem: unable to get local issuer certificate

- Configure Git to Use SChannel (Windows): Beginning with Git for Windows 2.14, you can configure Git to use SChannel, the built-in Windows networking layer, as the crypto backend. This means it will use the Windows certificate storage mechanism, and you won’t need to explicitly configure the curl CA storage mechanism1.
To enable this, update your Git installation to a version that supports SChannel.
```powershell
git config --global http.sslbackend schannel
```