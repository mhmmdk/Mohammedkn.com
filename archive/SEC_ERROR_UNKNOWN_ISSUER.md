### How I solved SEC_ERROR_UNKNOWN_ISSUER for my subdomain.
I had this error when I access my subdomain [file](https://file.mohammedkn.com). I abled to access the site by adding the site to exceptions. What I couldn't is making my site not to show the error for others like you.

#### Solution.
- My site is enabled indexing. I selected no index in my cpanel. This worked.
- I enabled indexing but deleted cgi-bin folder in my cpanel. Now it indexes and shows no error.
