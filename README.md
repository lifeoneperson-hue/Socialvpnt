Phone-only build (no computer):
1. Extract this zip in your phone's Files app.
2. github.com -> sign up -> New repository (name: socialvpn).
3. Add file -> Upload files -> select ALL extracted files EXCEPT build.yml -> Commit.
4. Add file -> Create new file -> name it:  .github/workflows/build.yml
   Paste the content of build.yml -> Commit.
5. Actions tab -> "Build APK" -> wait ~5 min until green.
6. Open the finished run -> Artifacts -> SocialVpn-apk -> download, unzip, install app-debug.apk.
   (Allow "Install unknown apps" for your browser/Files app.)
