## [Vrooboo! Wabbo!!](https://umatrix-rules.github.io/#ovagarava---toc)

As how it says in [uMatrix wiki](https://github.com/gorhill/uMatrix/wiki/Cookies), uMatrix will prevent cookies `from leaving your browser`.
By following rule sets bellow you do do further:

Add rule `* * cookie block`, which means to block cookies globally by default. You will then have to allow them manually in any scope where you are to login or where cookie use case ever exists helpful to you. Here is an example:

    * * cookie block
    google.com accounts.google.com cookie allow
    google.com google.com cookie block

In this case, `google.com google.com cookie block` prevent cookie-based tracking from Google search but, meanwhile, `google.com accounts.google.com cookie allow` can allow you to login to some Google service.

Such implement can be found in [here](https://github.com/uMatrix-Rules/uMatrix-Rules-Site/tree/Strict-Cookies).

### Reeshoova!
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>
Except where otherwise noted, all content in this org is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0 International License</a>
