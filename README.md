SANKI VIDTUBE - GITHUB PAGES QUICK START

FILES
- index.html: complete mobile-friendly demo website.

PUBLISH FROM ANDROID
1. Open https://github.com in Chrome and sign in/create an account.
2. Tap +, choose New repository.
3. Repository name: sanki-vidtube. Choose Public. Create repository.
4. In the repository, choose Add file > Create new file.
5. Name the file index.html.
6. Open the supplied index.html on your phone, copy all its contents, paste into GitHub's editor, then Commit changes.
   Alternative: use the repository's Add file > Upload files if you can select the downloaded index.html file.
7. Open repository Settings > Pages.
8. Under Build and deployment choose Deploy from a branch; select main and /(root), then Save.
9. Wait a minute or two. Your site should be at https://YOUR-GITHUB-USERNAME.github.io/sanki-vidtube/ .

IMPORTANT LIMITS
- This is a static frontend demo. Login/signup is not real authentication.
- Admin panel is not secure; anyone can open it. Do not use for private data.
- Videos/products are saved in the current browser localStorage only and do not sync across devices.
- The demo's UPI button opens a UPI app; it does not verify payments. Replace the placeholder UPI ID with your own before testing, and use a payment gateway plus server-side verification for real sales.
- Use only videos you have rights to share. Sample YouTube IDs are illustrative; replace them with your own valid videos.
- GitHub Pages cannot run a private server or backend. For production authentication, shared database, protected admin access, uploads, and verified payments, connect a backend service.
