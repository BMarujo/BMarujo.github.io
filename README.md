cp /home/marujo/NPUA/app/build/outputs/apk/release/app-release.apk /home/marujo/fdroid/repo/
source venv/bin/activate
fdroid update --create-metadata --pretty
gitdefault
