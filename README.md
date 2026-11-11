# Publish app-ads.txt at your website root

Prepared for publisher **pub-3732046801217814**. No hosting was published here.
Compare the supplied line with **AdMob → Apps → View all apps → app-ads.txt →
How to set up app-ads.txt** before publishing it.

1. For the existing GitHub hostname, the required URL is
   `https://thantsinnanda0-sudo.github.io/app-ads.txt`.
2. Use the GitHub user-site repository named
   **thantsinnanda0-sudo.github.io**. If it does not exist, create it as a public
   repository. Upload this `app-ads.txt` at the repository root. Enable GitHub
   Pages from that branch/root and wait for deployment.
3. Open the URL above. It must publicly show the single plain-text line, with
   no sign-in or HTML wrapper. This is separate from the policy repository:
   `.../eain-chet-privacy/app-ads.txt` is not the expected root URL.
4. Set the developer website in Play Console's **Store settings → Store listing
   contact details** to the matching website hostname. Keep the full privacy
   policy URL separately in App content; these are different fields.
5. When the public app-store listing is eligible and linked in AdMob, check the
   **app-ads.txt** status. Allow crawl time; a successful browser view does not
   itself prove AdMob verified the file.

If this hostname cannot be used or verified, Google's guide offers Firebase
Hosting as an alternative. Changing hosting also requires updating the website
in the app-store listing. Do not put the private upload key or passwords in any
public repository.

[Google's root-hosting guide](https://support.google.com/admob/answer/9363762)
and [Google's app-ads.txt format](https://developers.google.com/admob/ios/app-ads).
